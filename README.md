# Datasets
[![repo size](https://img.shields.io/github/repo-size/NDS-VU/signed-network-datasets.svg)](https://github.com/NDS-VU/signed-network-datasets/archive/master.zip) [![nds_vu](https://img.shields.io/twitter/follow/nds_vu?style=social&logo=twitter)](https://twitter.com/intent/follow?screen_name=nds_vu)⠀

Signed network datasets collected for network science, deep learning, and social network analysis research.

<p align="center">
  <img width="600" src="images/logo_nds.png">
</p>

##### Contents   

1. [Balance of Thrones](#balance-of-thrones)
2. [Bitcoin Alpha](#bitcoin-alpha)
3. [Bitoin OTC](#bitcoin-otc)
4. [Bitcoin OTC (Synthetic)](#bitcoin-otc-synthetic)
5. [Bonanza](#bonanza)
6. [Bundesliga](#bundesliga)
7. [Chess](#chess)
8. [Cloister](#cloister)
9. [Congress](#congress)
10. [Dutch College](#dutch-college)
11. [Epinions](#epinions)
12. [Highland Tribes](#highland-tribes)
13. [Libimseti](#libimseti)
14. [Ligue 1](#ligue1)
15. [Network Village](#network-village)
16. [Premier League](#premier-league)
17. [Pro League](#proleague)
18. [Real Bitcoin Alpha](#real-bitcoin-alpha)
19. [Real Bitcoin OTC](#real-bitcoin-otc)
20. [Slashdot](#slashdot)
21. [Twitter Italian Referendum](#twitter-italian-referendum)
22. [Wikipedia Conflict](#wikipedia-conflict)
23. [Wikipedia Elections](#wikipedia-elections)
24. [Wikipedia Politics](#wikipedia-politics)
25. [World War III](#world-war-iii)


## Balance of Thrones
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/128951607-1952d9f8-4a56-4901-a68c-b44e95d20fa9.jpg">
</p>


### Description
<p align="justify">
Balance of Thrones is a directed signed network whose edges are representative of the noble houses of the fantasy drama TV show, Game of Thrones. This dataset was collected as a part of a study published in 2017 entitled "Balance of Thrones: a network study on the Game of Thrones" completed by Dianbo Liu and Luca Albergante. Further description of the study can be found <a href="https://arxiv.org/abs/1707.05213">here.</a> Defining characteristics of each episode contained within the dataset are listed below in a [season].[episode] format — each set of characteristics representing its respective .csv file in a Episode[season].[episode].csv format.
</p>


### Links

- [Balance of Thrones](https://github.com/NDS-VU/signed-network-datasets/files/6965121/balanceofthrones.zip)

### Properties

- **Domain:** Fictional Social\Trust.
- **Node labels:** Yes.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.


|   | **Episode1.1** | **Episode1.2** | **Episode1.3** | **Episode1.4** | **Episode1.5** | **Episode1.6** | **Episode1.7** | **Episode1.8** | **Episode1.9** | **Episode1.10** |
|---|---|---|---|---|---|---|---|---|---|---|
| **Nodes** | 6 | 6 | 7 | 7 | 7 | 7 | 7 | 5 | 8 | 8 |
| **Positive Edges** | 9 | 9 | 11 | 11 | 11 | 11 | 11 | 6 | 10 | 10 |
| **Negative Edges** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **Clustering Coefficient** |  0.338889 |  0.338889 | 0.273810 | 0.273810 | 0.273810 | 0.273810 | 0.273810 | 0.300000 | 0.300000 | 0.300000 |

### Citing
```bibtex
@inproceedings{liu2018balance,
      title={Balance of thrones: a network study on Game of Thrones}, 
      author={Dianbo Liu and Luca Albergante},
      year={2018},
      eprint={1707.05213},
}
```




## Bitcoin Alpha
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129050154-f04f8161-a772-483a-80c7-c40cd5089642.png">
</p>


### Description
<p align="justify">
Bitcoin Alpha is a directed signed trust network of people who trade using Bitcoin on the platform Bitcoin-Alpha. It was collected from publicly available data on the <a href="https://btc-alpha.com/en/">Bitcoin-Alpha's website.</a> Due to the anonymity of the users’ Bitcoin accounts, profile reputations are built in interest of establishing a safety net of trusted users. Arising from the need to maintain a record of each user to prevent fraudulent and risky accounts, members of Bitcoin-Alpha rate other users in the range of [-10, -1] and [1, 10] if distrusted or trusted, respectively. Bitcoin-Alpha was the first explicit weighted signed directed network available for research when these positive and negative tie strength values were compiled and visible on every Bitcoin-Alpha user profile.
</p>


### Links

- [Bitcoin Alpha](https://github.com/NDS-VU/signed-network-datasets/files/6969330/bitcoinalpha.csv)

### Properties

- **Domain:** Online Social\Trust \& Financial.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.


|   | **Bitcoin Alpha** |
|---|---|
| **Nodes** |3,784 |
| **Positive Edges** | 22,650 |
| **Negative Edges** | 1,536 |
| **Clustering coefficient** | 0.158303 |

### Citing
```bibtex
@inproceedings{konect:kumar2016wsn,
	title = {Edge Weight Prediction in Weighted Signed Networks},
	author = {Kumar, Srijan and Spezzano, Francesca and Subrahmanian, V. S. and Faloutsos, Christos},
	booktitle = {Proc. Int. Conf. Data Min.},
	year = {2016},
	pages = {221--230},
}
```



## Bitcoin OTC
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129082188-4d63dde2-3bad-40bc-85f0-ca571dc588fb.jpg">
</p>


### Description
<p align="justify">
Bitcoin OTC is a directed signed trust network of people who trade using Bitcoin on the platform Bitcoin-Alpha. It was collected from publicly available data on <a href="http://www.bitcoin-otc.com/">Bitcoin OTC's website.</a> Due to the anonymity of the users’ Bitcoin accounts, profile reputations are built in interest of establishing a safety net of trusted users. Arising from the need to maintain a record of each user to prevent fraudulent and risky accounts, members of Bitcoin OTC rate other users in the range of [-10, -1] and [1, 10] if distrusted or trusted, respectively. Bitcoin-OTC was the first explicit weighted signed directed network available for research when these positive and negative tie strength values were compiled and visible on every Bitcoin-OTC user profile.
</p>

### Links

- [Bitcoin-OTC](https://github.com/NDS-VU/signed-network-datasets/files/6970437/bitcoinotc.csv)


### Properties

- **Domain:** Online Social\Trust \& Financial. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Bitcoin OTC**  |
|---|---|
| **Nodes** |5,881  | 
| **Positive Edges** | 32,029  |
| **Negative Edges** | 3,563 |
| **Clustering Coefficient** | 0.15107 |


### Citing
```bibtex
@inproceedings{konect:kumar2016wsn,
	title = {Edge Weight Prediction in Weighted Signed Networks},
	author = {Kumar, Srijan and Spezzano, Francesca and Subrahmanian, V. S. and Faloutsos, Christos},
	booktitle = {Proc. Int. Conf. Data Min.},
	year = {2016},
	pages = {221--230},
}
```





## Bitcoin OTC (Synthetic)
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129082050-c9abd194-88c2-4bac-bd42-33b9658a3418.png">
</p>


### Description
<p align="justify">
Bitcoin OTC (Synthetic) is a signed network whose directed edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the <a href="https://dl.acm.org/doi/10.1145/3366423.3380212">International World Wide Web Conference.</a> In the study, vertices of the Bitcoin signed network were removed in search of two perfectly opposing subsets to model phenomena such as the existence of polarized communities in social media. This specific network originally came from Bitcoin OTC, a trading platform that created a who-trusts-whom network that assigned a positive or negative value to a user's profile if a transaction was successful or unsuccessful, respectively.
</p>

### Links

- [Bitcoin OTC (Synthetic)](https://github.com/NDS-VU/signed-network-datasets/files/6970493/bitcoinotc.synthetic.csv)


### Properties

- **Domain:** Online Social\Trust \& Financial. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Bitcoin OTC (Synthetic)**  |
|---|---|
| **Nodes** |5,882  | 
| **Positive Edges** | 3,259  |
| **Negative Edges** | 18,233 |
| **Clustering Coefficient** | 0.08873 |


### Citing
```bibtex
@inproceedings{10.1145/3366423.3380212,
author = {Ordozgoiti, Bruno and Matakos, Antonis and Gionis, Aristides},
title = {Finding Large Balanced Subgraphs in Signed Networks},
year = {2020},
isbn = {9781450370233},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3366423.3380212},
doi = {10.1145/3366423.3380212},
abstract = {Signed networks are graphs whose edges are labelled with either a positive or a negative
sign, and can be used to capture nuances in interactions that are missed by their
unsigned counterparts. The concept of balance in signed graph theory determines whether
a network can be partitioned into two perfectly opposing subsets, and is therefore
useful for modelling phenomena such as the existence of polarized communities in social
networks. While determining whether a graph is balanced is easy, finding a large balanced
subgraph is hard. The few heuristics available in the literature for this purpose
are either ineffective or non-scalable. In this paper we propose an efficient algorithm
for finding large balanced subgraphs in signed networks. The algorithm relies on signed
spectral theory and a novel bound for perturbations of the graph Laplacian. In a wide
variety of experiments on real-world data we show that our algorithm can find balanced
subgraphs much larger than those detected by existing methods, and in addition, it
is faster. We test its scalability on graphs of up to 34 million edges.},
booktitle = {Proceedings of The Web Conference 2020},
pages = {1378–1388},
numpages = {11},
keywords = {dense subgraph, graph mining, community detection, signed graphs},
location = {Taipei, Taiwan},
series = {WWW '20}
}
```




## Bonanza
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129091029-9c01a402-0a07-4ba9-b92f-a8a5c2f05d82.png">
</p>


### Description
<p align="justify">
Bonanza is a directed signed network of people who participate in transactions on the online marketplace <a href="https://www.bonanza.com">Bonanza.</a> The two files included in the repository represent rating values given to the sellers by the buyers of the transactions and rating values given to the buyers by the sellers of the transactions — the files are named bonanza-buyer-to-seller.csv and bonanza-seller-to-buyer.csv, respectively. The ratings are 1,0, and -1 for positive, neutral, and negative options on Bonanza. Both files are in the format: date, seller_id, buyer_id, rating, item_link, item_name, user_comment. 
</p>

### Links

- [Bonanza](https://too_large-is-not-included-in-the-list)

### Properties

- **Domain:** Online Social\Trust \& Financial.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **bonanza-buyer-to-seller.csv**  | **bonanza-seller-to-buyer.csv** |
|---|---|---|
| **Nodes** | 346976 | 277234 |
| **Positive Edges** | 541917 | 546751 |
| **Negative Edges** | 32824 | 2186 |
| **Clustering Coefficient** | 0.001898 | 0.002715 |


### Citing
```bibtex
@inproceedings{vunds
author = {Sam Libaire and Tyler Derr},
title = {Bonanza},
year = {2021},
organization = {Vanderbilt University; Nashville, TN},
}
```



## Bundesliga
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129087314-b80d304f-9dee-4dbd-8e15-07028e9ef523.png">
</p>


### Description
<p align="justify">
Bundesliga is a directed signed network that is the result of football (American soccer) games in Germany from the Bundesliga in the season 2016/2017. This network was sourced from the the Koblenz Network Collection. In this network, nodes are teams, and each directed edge from A to B denotes that team A played at home against team B. The edge weights are the goal difference — positive if the home team wins, negative when the away team wins, and zero for a draw. The exact game results are not represented; only the goal differences are.
</p>

### Links

- [Bundesliga](https://github.com/NDS-VU/signed-network-datasets/files/6970766/bundesliga.csv)


### Properties

- **Domain:** Physical Social &/ Sports.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Bundesliga** |
|---|---|
| **Nodes** | 19 |
| **Positive Edges** | 224 |
| **Negative Edges** | 18 |
| **Clustering Coefficient** | 0.941086 |


### Citing
```bibtex
@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}
```



## Chess
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129088039-0d4e5d16-83ba-4c67-9f98-7d6d004b5efc.jpeg">
</p>


### Description
<p align="justify">
Chess is a directed signed network that is the result of chess games. Each node is a chess player, and a directed edge represents a game, with the white player having an outgoing edge and the black player having an ingoing edge. The edge weights are in the range [-1, +1] with -1 representing black win, 0 representing draw, and +1 representing white win.
</p>

### Links

- [Chess](https://github.com/NDS-VU/signed-network-datasets/files/6970785/chess.csv)


### Properties

- **Domain:** Physical Social &/ Sports.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Chess** |
|---|---|
| **Nodes** | 7301 |
| **Positive Edges** | 49829 |
| **Negative Edges** | 15224 |
| **Clustering Coefficient** | 0.12584 |


### Citing
```bibtex
@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}
```



## Cloister
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129089618-41d3567c-1d52-4f89-a010-f08b6bb2c4d2.jpg">
</p>


### Description
<p align="justify">
Cloister is a directed signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the <a href="https://dl.acm.org/doi/10.1145/3366423.3380212">International World Wide Web Conference.</a> In the study, vertices of the cloister signed network were removed in search of two perfectly opposing subsets to model phenomena such as the existence of polarized communities in social media. This specific network was sourced from crisis in a cloister, a directed signed network that contains ratings between monks living in a cloister (monastery) in New England (USA). The networks aggregates several ratings [(dis)esteem, (dis)liking, positive/negative influence, praise/blame] into one rating — positive if all ratings were positive, negative if all ratings were negative, and 0 if there were mixed opinions amongst the monks.
</p>

### Links

- [Cloister](https://github.com/NDS-VU/signed-network-datasets/files/6970846/cloister.csv)


### Properties

- **Domain:** Physical Social. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Cloister**  |
|---|---|
| **Nodes** | 19 | 
| **Positive Edges** | 56 |
| **Negative Edges** | 69 |
| **Clustering Coefficient** | 0.399032 |


### Citing
```bibtex
@inproceedings{10.1145/3366423.3380212,
author = {Ordozgoiti, Bruno and Matakos, Antonis and Gionis, Aristides},
title = {Finding Large Balanced Subgraphs in Signed Networks},
year = {2020},
isbn = {9781450370233},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3366423.3380212},
doi = {10.1145/3366423.3380212},
abstract = {Signed networks are graphs whose edges are labelled with either a positive or a negative
sign, and can be used to capture nuances in interactions that are missed by their
unsigned counterparts. The concept of balance in signed graph theory determines whether
a network can be partitioned into two perfectly opposing subsets, and is therefore
useful for modelling phenomena such as the existence of polarized communities in social
networks. While determining whether a graph is balanced is easy, finding a large balanced
subgraph is hard. The few heuristics available in the literature for this purpose
are either ineffective or non-scalable. In this paper we propose an efficient algorithm
for finding large balanced subgraphs in signed networks. The algorithm relies on signed
spectral theory and a novel bound for perturbations of the graph Laplacian. In a wide
variety of experiments on real-world data we show that our algorithm can find balanced
subgraphs much larger than those detected by existing methods, and in addition, it
is faster. We test its scalability on graphs of up to 34 million edges.},
booktitle = {Proceedings of The Web Conference 2020},
pages = {1378–1388},
numpages = {11},
keywords = {dense subgraph, graph mining, community detection, signed graphs},
location = {Taipei, Taiwan},
series = {WWW '20}
}
```





## Congress
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129089932-5374e3a9-46e7-439c-9f0f-51bddf31f083.png">
</p>


### Description
<p align="justify">
Congress is a directed signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the <a href="https://dl.acm.org/doi/10.1145/3366423.3380212">International World Wide Web Conference. </a> This specific network was sourced from congress votes, a directed signed network that represents politicians speaking in the United States Congress as nodes and mentions between speakers as directed edges. The weight of an edge (-1 or +1) represents if the source speaker is in support or disagreement with the mentioned politician. Multiple parallel edges are possible (i.e., can be weighted); self-loops are allowed (i.e., speakers can mention themselves).
</p>

### Links

- [Congress](https://github.com/NDS-VU/signed-network-datasets/files/6970859/congress.csv)


### Properties

- **Domain:** Physical Social. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Congress**  |
|---|---|
| **Nodes** | 220 | 
| **Positive Edges** | 414 |
| **Negative Edges** | 107 |
| **Clustering Coefficient** | 0.126588 |


### Citing
```bibtex
@inproceedings{konect:convote,
	author = {Matt Thomas and Bo Pang and Lillian Lee},
	title = {Get the Out Vote: Determining Support or Opposition from
                  Congressional Floor-Debate Transcripts},  
	booktitle = {Proc. Conf. on Empir. Methods in Nat. Lang. Process.},
	pages = {327--335},
	year = {2006},
}
```




## Dutch College
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129090627-b97fe679-87e6-43f7-9e62-c78e67ce0481.jpg">
</p>


### Description
<p align="justify">
Dutch College is a directed signed network that is the result of friendship ratings between 32 university freshmen who did not know each other before starting university in the Netherlands. Each student was asked to rate the other student at seven different time points (column D) — the origin of the timestamps is not accurately known but the distance between two timestamps is correct. A node represents a student and an edge between two students shows that the left rated the right one The edge weights show how good their friendship is in the eye of the left node. The weight of each edge is in the range [-1, +3] for risk of getting into conflict to best friend, respectively.
</p>

### Links

- [Congress](https://github.com/NDS-VU/signed-network-datasets/files/6970909/dutchcollege.csv)


### Properties

- **Domain:** Physical Social. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Dutch College**  |
|---|---|
| **Nodes** | 32 | 
| **Positive Edges** | 3005 |
| **Negative Edges** | 57 |
| **Clustering Coefficient** | 0.903676 |


### Citing
```bibtex
@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}
```



## Epinions
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129092082-0f5c4451-6d16-465d-84c2-77eb594e6f60.png">
</p>


### Description
<p align="justify">
Epinions is a directed signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the <a href="https://dl.acm.org/doi/10.1145/3366423.3380212">International World Wide Web Conference.</a> In the study, vertices of the Epinions signed network were removed in search of two perfectly opposing subsets to model phenomena such as the existence of polarized communities in social media. This specific network was sourced from Epinions.com, a trading platform that created a who-trusts-whom network that assigned a positive or negative value to a user's profile if a transaction was successful or unsuccessful. If the transaction was completed, both participating user accounts are given the option to "trust" each other. In the case where both both user accounts opt to trust each other, the link between the two accounts are assigned a value of 1, while if one user opts to not trust the other, the respective link is assigned a value of -1.
</p>

### Links

- [Epinions](https://github.com/NDS-VU/signed-network-datasets/files/6970960/epinions.csv)

### Properties

- **Domain:** Online Social\Trust \& Product Review.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** No.

|   | **Epinions**  |
|---|---|
| **Nodes** | 131,580 | 
| **Positive Edges** | 589,888  |
| **Negative Edges** | 121,322 |
| **Clustering Coefficient** | 0.064093 |


### Citing
```bibtex
@inproceedings{konect:massa05,
        title = {Controversial Users Demand Local Trust Metrics: an
                  Experimental Study on {epinions.com} Community},
        author = {Paolo Massa and Paolo Avesani},
        booktitle = {Proc. American Association for Artif. Intell. Conf.},
        year = {2005},
        pages = {121--126},
}
```





## Highland Tribes
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129092569-5db31ac9-38f5-4c4f-a87b-dc14d84443ec.jpg">
</p>


### Description
<p align="justify">
Highland tribes is an undirected signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from sixteen tribes in the Eastern Central Highlands of New Guinea from Kenneth Read in 1954. By analyzing the signed social network of tribes in the Gahuku-Gama alliance structure, Read was able to represent relationships between individual tribes by positive (+1) and negative (-1) weighted edges. Positive edges signify tribes connected by friendship ('rova') while negative edge signify tribes connected by enmity ('hina').
</p>

### Links

- [Highland Tribes](https://github.com/NDS-VU/signed-network-datasets/files/6970964/highlandtribes.csv)


### Properties

- **Domain:** Physical Social \& Civilization.
- **Node labels:** No.
- **Directed:** No.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Highland Tribes**  |
|---|---|
| **Nodes** | 16  | 
| **Positive Edges** | 29  |
| **Negative Edges** | 29 |
| **Clustering Coefficient** | 0.240733 |


### Citing
```bibtex
@inproceedings{vunds
author = {Derr, Tyler and Libaire, Sam},
title = {Bonanza},
year = {2021},
organization = {Vanderbilt University; Nashville, TN},
}
```



## Libimseti
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129093881-d7488bb8-450f-4ad2-ba77-2b4db9163507.jpg">
</p>


### Description
<p align="justify">
Libimseti is a directed signed network representing ratings given by users of Libimseti.cz to other users. Libimseti.cz was sourced from a study completed by Ryan A. Rossi and Nesreen K. Ahmed in 2015 entitled "The Network Data Repository with Interactive Graph Analytics and Visualization." The network is representative of the Czech dating site, Libimseti, where nodes are users and edges are ratings on a scale from 1 to 10.
</p>

### Links

- [Libimseti](https://too_large-is-not-included-in-the-list)


### Properties

- **Domain:** Online Social\Trust.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Libimseti**  |
|---|---|
| **Nodes** | 220970 | 
| **Positive Edges** | 17359346 |
| **Negative Edges** | 0 |
| **Clustering Coefficient** | 0.007337 |


### Citing
```bibtex
@inproceedings{nr,
     title={The Network Data Repository with Interactive Graph Analytics and Visualization},
     author={Ryan A. Rossi and Nesreen K. Ahmed},
     booktitle={AAAI},
     url={https://networkrepository.com},
     year={2015}
}
```



## Ligue 1
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129094208-bf49a71f-791e-4823-990c-3ec322d05510.png">
</p>


### Description
<p align="justify">
Ligue 1 is a directed signed network that is the result of football (American soccer) games in France from the Ligue 1 in the season 2016/2017. This network was sourced from the the Koblenz Network Collection. In this network, nodes are teams, and each directed edge from A to B denotes that team A played at home against team B. The edge weights are the goal difference — positive if the home team wins, negative when the away team wins, and zero for a draw. The exact game results are not represented; only the goal differences are.
</p>

### Links

- [Ligue 1](https://github.com/NDS-VU/signed-network-datasets/files/6971047/ligue1.csv)


### Properties

- **Domain:** Physical Social \& Sports.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Ligue 1**  |
|---|---|
| **Nodes** | 21 | 
| **Positive Edges** | 281 |
| **Negative Edges** | 99 |
| **Clustering Coefficient** | 0.947303 |


### Citing
```bibtex
@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}
```


## Network Village
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129098629-ea8bd320-cbd1-40e5-a91e-c55d64f75ec8.png">
</p>


### Description
<p align="justify">
Network village is a directed signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a publication cited: "A. Isakov, J.H. Fowler, E. Airoldi, and N. A. Christakis, “The Structure of Negative Ties in Rural Village Networks,” Sociological Science, Vol. 6, p197-218 (Mar 2019) DOI: 10.15195/v6.a8." In the publication, village networks titled in the format network_village_X.csv (A-K) represent 11 different villages with a tie type of +1 representing friend and -1 representing enemy, 0 does not occur. Another file in the directory is triad_templates.csv. This file is the triad census template with all 138 possible isomorphisms (row numbers are "iso.class"), the naming as in the paper, and the number of observations of triad types (fff, ffe, etc.) they correspond to. A note here: "XYZ" stands for "the Y of my X is my Z" (e.g. "fef" stands for "the enemy of my friend is my friend"). This can be used to classify your own graph with positive and negative ties into the 138 classes shown in the paper. Additionally, real_triad_census_on_11_villages.csv contains the real triad census on the real villages. This file is organized by iso.class (# of triangles of type 1, 2, 3, ... 138 observed in villages A-K). 
</p>


### Links

- [Network Village](https://github.com/NDS-VU/signed-network-datasets/files/6971116/Network_Village.zip)


### Properties

- **Domain:** Physical Social \& Civilization.
- **Node labels:** Yes.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.


|   | **Network_village_A** | **Network_village_B** | **Network_village_C** | **Network_village_D** | **Network_village_E** | **Network_village_F** | **Network_village_G** | **Network_village_H** | **Network_village_I** | **Network_village_J** | **Network_village_K** |
|---|---|---|---|---|---|---|---|---|---|---|---|
| **Nodes** | 149 | 109 | 61 | 160 | 278 | 126 | 249 | 114 | 113 | 122 | 226 |
| **Positive Edges** | 1252 | 467 | 352 | 450 | 796 | 440 | 963 | 560 | 315 | 548 | 746 |
| **Negative Edges** | 187 | 32 | 42 | 75 | 66 | 72 | 155 | 82 | 42 | 186 | 194 |
| **Clustering Coefficient** |  0.221497 |  0.184506 | 0.275973 | 0.118155 | 0.129528 | 0.153793 | 0.149817 | 0.238083 | 0.163867 | 0.161895 | 0.148356 |

### Citing
```bibtex
@inproceedings{Isakov_2019,
author = {Alexander Isakov and James H. Fowler and Edoardo M. Airoldi and Nicholas A. Christakis },
title = {The Structure of Negative Social Ties in Rural Village Networks},
journal = {Sociological Science},
volume = {6},
number = {8},
issn = {2330-6696},
url = {http://dx.doi.org/10.15195/v6.a8},
doi = {10.15195/v6.a8},
pages = {197--218},
year = {2019},
}
```



## Premier League
[top](#datasets)
<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/71398034/129098835-eb6627f7-4904-4312-b281-4ac176955c35.png">
</p>


### Description
<p align="justify">
Premier League is a directed signed network that is the result of football (American soccer) games in England and Wales from the Premier League in the season 2013/2014. This network was sourced from the the Koblenz Network Collection. In this network, nodes are teams, and each directed edge from A to B denotes that team A played at home against team B. The edge weights are the goal difference — positive if the home team wins, negative when the away team wins, and zero for a draw. The exact game results are not represented; only the goal differences are.
</p>

### Links

- [Premier League](https://github.com/NDS-VU/signed-network-datasets/files/6971225/premierleague.csv)


### Properties

- **Domain:** Physical Social \& Sports.
- **Node labels:** Yes.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Premier League**  |
|---|---|
| **Nodes** | 21 | 
| **Positive Edges** | 257 |
| **Negative Edges** | 123 |
| **Clustering Coefficient** | 0.947303 |


### Citing
```bibtex
@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}
```


## Pro League
[top](#datasets)
<p align="center">
  <img width="200" src="![Uploading Unknown-3.png…]()">
</p>


### Description
<p align="justify">
Pro league is a directed signed network that is the result of football (American soccer) games in Belgium from the Pro League in the season 2016/2017. This network was sourced from the the Koblenz Network Collection. In this network, nodes are teams, and each directed edge from A to B denotes that team A played at home against team B. The edge weights are the goal difference — positive if the home team wins, negative when the away team wins, and zero for a draw. The exact game results are not represented; only the goal differences are.
</p>

### Links

- [Pro League](https://github.com/NDS-VU/signed-network-datasets/files/6971278/proleague.csv)



### Properties

- **Domain:** Physical Social \& Sports.
- **Node labels:** Yes.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Pro League**  |
|---|---|
| **Nodes** | 16 | 
| **Positive Edges** | 179 |
| **Negative Edges** | 60 |
| **Clustering Coefficient** | 0.995833 |


### Citing
```bibtex
@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}
```



## Real Bitcoin Alpha
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Real Bitcoin Alpha is a directed signed network of people who trade using Bitcoin on the platform Bitcoin-Alpha. It was collected from publicly available data on <a href="https://btc-alpha.com/en/">Bitcoin-Alpha's website.</a> Members of Bitcoin-Alpha rate other users in the range of [-10, -1] and [1, 10] if distrusted or trusted, respectively after a transition on the site has been flagged as completed. Bitcoin-Alpha was the first explicit weighted signed directed network available for research when these positive and negative tie strength values were compiled and visible on every Bitcoin-Alpha user profile. The repository includes multiple data files to be utilized: real_bitcoin_alpha.csv in the format [source, target, edge weight]; real_bitcoin_alpha_user_mapping.csv in the format [node, user_name]; and real_bitcoin_alpha_user.txt in the format [seller buyer timestamp rating description(if applicable)].
</p>

### Links

- [Real Bitcoin Alpha](https://github.com/NDS-VU/signed-network-datasets/files/6971327/realBitcoinAlpha.zip)



### Properties

- **Domain:** Online Social\Trust \& Financial.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.


|   | **Real Bitcoin Alpha**  |
|---|---|
| **Nodes** | 3784 | 
| **Positive Edges** | 22651 |
| **Negative Edges** | 1556 |
| **Clustering Coefficient** | 0.158188 |


### Citing
```bibtex
@inproceedings{vunds
author = {Sam Libaire and Tyler Derr},
title = {Bonanza},
year = {2021},
organization = {Vanderbilt University; Nashville, TN},
}
```


## Real Bitcoin OTC
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Real Bitcoin OTC is a directed signed trust network of people who trade using Bitcoin on the platform Bitcoin-Alpha. It was collected from publicly available data on <a href="http://www.bitcoin-otc.com/">Bitcoin OTC's website.</a> Members of Bitcoin OTC rate other users in the range of [-10, -1] and [1, 10] if distrusted or trusted, respectively after a transition on the site has been flagged as completed. The repository includes multiple data files to be utilized: real_bitcoin_otc.csv in the format [source, target, edge weight]; real_bitcoin_otc_user_mapping.csv in the format [node, user_name]; and real_bitcoin_otc_user.txt in the format [seller buyer timestamp rating description(if applicable)].
</p>

### Links

- [Real Bitcoin OTC](https://github.com/NDS-VU/signed-network-datasets/files/6971328/realBitcoinOTC.zip)


### Properties

- **Domain:** Online Social\Trust \& Financial.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.


|   | **Real Bitcoin OTC**  |
|---|---|
| **Nodes** | 5901 | 
| **Positive Edges** | 32271 |
| **Negative Edges** | 3438 |
| **Clustering Coefficient** | 0.152591 |


### Citing
```bibtex
@inproceedings{vunds
author = {Sam Libaire and Tyler Derr},
title = {Bonanza},
year = {2021},
organization = {Vanderbilt University; Nashville, TN},
}
```



## Slashdot
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Slashdot is a directed signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the <a href="https://dl.acm.org/doi/10.1145/3366423.3380212">International World Wide Web Conference.</a> In the study, vertices of the Slashdot signed network were removed in search of two perfectly opposing subsets to model phenomena such as the existence of polarized communities in social media. This specific network was sourced from Slashdot Zoo <slashdot.org>, a technology news sight that connects users by directed friend and foe relations. On the UI of Slashdot, users are given the option to mark users as friends or foes to influence the scores as seen by each user. If a user took action to mark another account as a friend or foe (+1 or -1, respectively) the score of the recipient's posts will be increased/decreased as shown to the acting user. The network contains 82141 nodes, 380933 positive links, 119548 negative links, an average clustering coefficient of 0.029393129579407727, and an overall reciprocity of 0.0.
</p>

### Links

- [Slashdot](https://github.com/NDS-VU/signed-network-datasets/files/6971382/slashdot.csv.zip)



### Properties

- **Domain:** Online Social\Trust \& Product Review.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Slashdot**  |
|---|---|
| **Nodes** | 82,141  | 
| **Positive Edges** | 380,933  |
| **Negative Edges** | 119,548 |
| **Clustering Coefficient** | 0.029393 |


### Citing
```bibtex
@inproceedings{10.1145/3366423.3380212,
author = {Ordozgoiti, Bruno and Matakos, Antonis and Gionis, Aristides},
title = {Finding Large Balanced Subgraphs in Signed Networks},
year = {2020},
isbn = {9781450370233},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3366423.3380212},
doi = {10.1145/3366423.3380212},
abstract = {Signed networks are graphs whose edges are labelled with either a positive or a negative
sign, and can be used to capture nuances in interactions that are missed by their
unsigned counterparts. The concept of balance in signed graph theory determines whether
a network can be partitioned into two perfectly opposing subsets, and is therefore
useful for modelling phenomena such as the existence of polarized communities in social
networks. While determining whether a graph is balanced is easy, finding a large balanced
subgraph is hard. The few heuristics available in the literature for this purpose
are either ineffective or non-scalable. In this paper we propose an efficient algorithm
for finding large balanced subgraphs in signed networks. The algorithm relies on signed
spectral theory and a novel bound for perturbations of the graph Laplacian. In a wide
variety of experiments on real-world data we show that our algorithm can find balanced
subgraphs much larger than those detected by existing methods, and in addition, it
is faster. We test its scalability on graphs of up to 34 million edges.},
booktitle = {Proceedings of The Web Conference 2020},
pages = {1378–1388},
numpages = {11},
keywords = {dense subgraph, graph mining, community detection, signed graphs},
location = {Taipei, Taiwan},
series = {WWW '20}
}
```




## Twitter Italian Referendum
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Twitter Italian referendum is an undirected signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the <a href="https://dl.acm.org/doi/10.1145/3366423.3380212">International World Wide Web Conference.</a> In the study, vertices representing Twitter user sentiments of the 2016 Italian Referendum were removed in search of two perfectly opposing subsets to model phenomena such as the existence of polarized communities in social media. This specific network was sourced from Twitter users in 2016 as thousands of individuals tweeted about the controversial 2016 Italian Referendum that would amend the Italian Constitution to reform the composition and powers of <a href="https://en.wikipedia.org/wiki/2016_Italian_constitutional_referendum">the Parliament of Italy.</a> An interaction is marked with an edge weight of -1 if two users are classified with different stances, and +1 otherwise.
</p>

### Links

- [Twitter Italian Referendum](https://github.com/NDS-VU/signed-network-datasets/files/6971376/twitterreferendum.csv)


### Properties

- **Domain:** Online Social.
- **Node labels:** No.
- **Directed:** No.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Twitter Italian Referendum**  |
|---|---|
| **Nodes** | 10,885  | 
| **Positive Edges** | 238,612  |
| **Negative Edges** | 12,794 |
| **Clustering Coefficient** | 0.117110 |


### Citing
```bibtex
@inproceedings{10.1145/3366423.3380212,
author = {Ordozgoiti, Bruno and Matakos, Antonis and Gionis, Aristides},
title = {Finding Large Balanced Subgraphs in Signed Networks},
year = {2020},
isbn = {9781450370233},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3366423.3380212},
doi = {10.1145/3366423.3380212},
abstract = {Signed networks are graphs whose edges are labelled with either a positive or a negative
sign, and can be used to capture nuances in interactions that are missed by their
unsigned counterparts. The concept of balance in signed graph theory determines whether
a network can be partitioned into two perfectly opposing subsets, and is therefore
useful for modelling phenomena such as the existence of polarized communities in social
networks. While determining whether a graph is balanced is easy, finding a large balanced
subgraph is hard. The few heuristics available in the literature for this purpose
are either ineffective or non-scalable. In this paper we propose an efficient algorithm
for finding large balanced subgraphs in signed networks. The algorithm relies on signed
spectral theory and a novel bound for perturbations of the graph Laplacian. In a wide
variety of experiments on real-world data we show that our algorithm can find balanced
subgraphs much larger than those detected by existing methods, and in addition, it
is faster. We test its scalability on graphs of up to 34 million edges.},
booktitle = {Proceedings of The Web Conference 2020},
pages = {1378–1388},
numpages = {11},
keywords = {dense subgraph, graph mining, community detection, signed graphs},
location = {Taipei, Taiwan},
series = {WWW '20}
}
```





## Wikipedia Conflict
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Wiki conflict is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from a study done by <a href="https://snap.stanford.edu/data">SNAP</a> on the English Wikipedia website. This dataset represents a network of users editing English Wikipedia pages; nodes represent individual users, and edges represent agree or disagreement of information (-1 or 1 representing disagreement or agreement, respectively).
</p>

### Links

- [Wikipedia Conflict](https://github.com/NDS-VU/signed-network-datasets/files/6971525/wikiconflict.csv.zip)


### Properties

- **Domain:** Online Social.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** No.

|   | **Wikipedia Conflict**  |
|---|---|
| **Nodes** | 7,116  | 
| **Positive Edges** | 533,439  |
| **Negative Edges** | 515,137 |
| **Clustering Coefficient** | 0.0703455 |


### Citing
```bibtex
@inproceedings{konect:maniu2011,
	title = {Casting a Web of Trust over {Wikipedia}: An Interaction-based Approach},
	author = {Maniu, Silviu and Abdessalem, Talel and Cautis, Bogdan},
	booktitle = {Proc. Int. Conf. on World Wide Web Posters},
	year = {2011},
	pages = {87--88},
}
```





## Wikipedia Elections
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Wiki elections is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from a study done by <a href="https://snap.stanford.edu/data">SNAP</a> on the English Wikipedia website. This dataset represents a network of users that voted for and against each other in admin elections; nodes represent individual users, and edges represent votes (-1 or 1 representing a vote in favor or against, respectively).
</p>

### Links

- [Wikipedia Elections](https://github.com/NDS-VU/signed-network-datasets/files/6971521/wikielections.csv)


### Properties

- **Domain:** Online Social.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** No.

|   | **Wikipedia Elections**  |
|---|---|
| **Nodes** | 7,116  | 
| **Positive Edges** | 78,440  |
| **Negative Edges** | 22,253 |
| **Clustering Coefficient** | 0.070345 |


### Citing
```bibtex
@inproceedings{konect:maniu2011,
	title = {Casting a Web of Trust over {Wikipedia}: An Interaction-based Approach},
	author = {Maniu, Silviu and Abdessalem, Talel and Cautis, Bogdan},
	booktitle = {Proc. Int. Conf. on World Wide Web Posters},
	year = {2011},
	pages = {87--88},
}
```





## Wikipedia Politics
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
Wiki politics is an undirected signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from a study done by <a href="https://snap.stanford.edu/data">SNAP</a> on the English Wikipedia website. This dataset represents a network of users editing English Wikipedia pages; nodes represent individual users, and edges represent agree or disagreement of information changed after the edit was completed (-1 or 1 representing disagreement or agreement, respectively). Note that a user may revert their own edits, leading to negatively weighted loops.
</p>

### Links

- [Wikipedia Politics](https://github.com/NDS-VU/signed-network-datasets/files/6971514/wikipolitics.csv)


### Properties

- **Domain:** Online Social
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** No.

|   | **Wikipedia Politics**  |
|---|---|
| **Nodes** | 138,588  | 
| **Positive Edges** | 628,000  |
| **Negative Edges** | 87,883 |
| **Clustering Coefficient** | 0.115152 |


### Citing
```bibtex
@inproceedings{konect:maniu2011,
	title = {Casting a Web of Trust over {Wikipedia}: An Interaction-based Approach},
	author = {Maniu, Silviu and Abdessalem, Talel and Cautis, Bogdan},
	booktitle = {Proc. Int. Conf. on World Wide Web Posters},
	year = {2011},
	pages = {87--88},
}
```


## World War III
[top](#datasets)
<p align="center">
  <img width="200" src="!!!">
</p>


### Description
<p align="justify">
WWIII is a directed network in the format: [Source, Target, Export, Import, Diplomatic, War, Border, International Cases, Treaties, Exchange Rate, Religion_conflicts]. This network was created by GitHub user shivi98g in a repository entitled "WorldWarIII_Scomp."

### Links

- [WWIII][wwIII.csv](https://github.com/NDS-VU/signed-network-datasets/files/6971523/wwIII.csv)



### Properties

- **Domain:** Physical Social \& Civilization.
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** No.

|   | **World War III**  |
|---|---|
| **Nodes** | 198  | 
| **Positive Edges** | NA |
| **Negative Edges** | NA |
| **Clustering Coefficient** | 0.994898 |


### Citing
```bibtex
https://github.com/worldWarIII-scomp/WorldWarIII_Scomp
}
