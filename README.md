# Datasets [![repo size](https://img.shields.io/github/repo-size/NDS-VU/signed-network-datasets.svg)](https://github.com/NDS-VU/signed-network-datasets/archive/master.zip) [![nds_vu](https://img.shields.io/twitter/follow/nds_vu?style=social&logo=twitter)](https://twitter.com/intent/follow?screen_name=nds_vu)⠀

Signed network datasets collected for network science, deep learning, and social network analysis research.

<p align="center">
  <img width="600" src="/images/repo_figure.png">
</p>

##### Contents   

1. [Bitcoin Alpha](#bitcoin-alpha)
2. [Bitoin OTC](#bitcoin-otc)
3. [Bitcoin OTC (Synthetic)](#bitcion-otc-(synthetic))
4. [Cloister](#cloister)
5. [Congress](#congress)
6. [Epinions](#epinions)
7. [Highland Tribes](#highland-tribes)
8. [Slashdot](#slashdot)
9. [Twitter Italian Referendum](#twitter-italian-referendum)
10. [Wikipedia Conflict](#wikipedia-conflict)
11. [Wikipedia Elections](#wikipedia-elections)
12. [Wikipedia Politics](#wikipedia-politics)


## Bitcoin Alpha
<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Bitcoin Alpha is a directed signed trust network of people who trade using Bitcoin on the platform Bitcoin-Alpha. It was collected from publicly available data on the Bitcoin-Alpha's website <https://btc-alpha.com/en/>. Due to the anonymity of the users’ Bitcoin accounts, profile reputations are built in interest of establishing a safety net of trusted users. Arising from the need to maintain a record of each user to prevent fraudulent and risky accounts, members of Bitcoin-Alpha rate other users in the range of [-10, -1] and [1, 10] if distrusted or trusted, respectively. Bitcoin-Alpha was the first explicit weighted signed directed network available for research when these positive and negative tie strength values were compiled and visible on every Bitcoin-Alpha user profile.
</p>


### Links

- [Bitcoin Alpha](https://to-be-added)

### Properties

- **Domain:** Online Social\Trust \& Financial
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.


|   | **Bitcoin Alpha**  |
|---|---|
| **Nodes** |3,784   |
| **Positive Edges** | 22,650 |
| **Negative Edges** | 1,536 |
| **Clustering coefficient** |  0.15830 |

### Citing
```bibtex
>@misc{to be added
       }
```





## Bitcoin OTC

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Bitcoin OTC is a directed signed trust network of people who trade using Bitcoin on the platform Bitcoin-Alpha. It was collected from publicly available data on the Bitcoin OTC's website <http://www.bitcoin-otc.com/>. Due to the anonymity of the users’ Bitcoin accounts, profile reputations are built in interest of establishing a safety net of trusted users. Arising from the need to maintain a record of each user to prevent fraudulent and risky accounts, members of Bitcoin OTC rate other users in the range of [-10, -1] and [1, 10] if distrusted or trusted, respectively. Bitcoin-OTC was the first explicit weighted signed directed network available for research when these positive and negative tie strength values were compiled and visible on every Bitcoin-OTC user profile.
</p>

### Links

- [Bitcoin-OTC](https://to-be-added)

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
@inproceedings{to-be-added
}
```





## Bitcoin OTC (Synthetic)

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Bitcoin OTC (Synthetic) is a signed network whose directed edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the International World Wide Web Conference <https://dl.acm.org/doi/10.1145/3366423.3380212>. In the study, vertices of the Bitcoin signed network were removed in search of two perfectly opposing subsets to model phenomena such as the existence of polarized communities in social media. This specific network originally came from Bitcoin OTC, a trading platform that created a who-trusts-whom network that assigned a positive or negative value to a user's profile if a transaction was successful or unsuccessful, respectively.
</p>

### Links

- [Bitcoin OTC (Synthetic)](https://to-be-added)

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
@inproceedings{to-be-added
}
```





## Cloister

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Cloister is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from crisis in a cloister, a directed signed network that contains ratings between monks living in a cloister (monastery) in New England (USA). The networks aggregates several ratings [(dis)esteem, (dis)liking, positive/negative influence, praise/blame] into one rating — positive if all ratings were positive, negative if all ratings were negative, and 0 if there were mixed opinions amongst the monks.
</p>

### Links

- [Cloister](https://to-be-added)

### Properties

- **Domain:** Physical Social. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** Yes.

|   | **Cloister**  |
|---|---|
| **Nodes** | 19  | 
| **Positive Edges** | 56  |
| **Negative Edges** | 69 |
| **Clustering Coefficient** | 0.39903 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Congress

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Congress is a directed signed network whose edges are labels with either a positive or a negative sign. It was collected as a part of a study titled "Finding Large Balances Subgraphs in Signed Networks" by Aristides Gionis, Anonis Matakos, and Bruno Ordozgoiti published on 4/20/2020 for the International World Wide Web Conference <https://dl.acm.org/doi/10.1145/3366423.3380212>. This specific network was sourced from congress votes, a directed signed network that represents politicians speaking in the United States Congress as nodes and mentions between speakers as directed edges. The weight of an edge (-1 or +1) represents if the source speaker is in support or disagreement with the mentioned politician. Multiple parallel edges are possible (i.e., can be weighted); self-loops are allowed (i.e., speakers can mention themselves). The network contains 220 nodes, 414 positive links, 107 negative links, an average clustering coefficient of 0.12658831239852403, and an overall reciprocity of 0.0.
</p>

### Links

- [Congress](https://to-be-added)

### Properties

- **Domain:** Physical Social. 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** Yes.

|   | **Congress**  |
|---|---|
| **Nodes** | 220  | 
| **Positive Edges** | 414  |
| **Negative Edges** | 107 |
| **Clustering Coefficient** | 0.12659 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Epinions
[top](#contents)
<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Epinions is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from Epinions.com, which was a product review website where users could label other users as those they trust or distrust according to their reviews. 
</p>

### Links

- [Epinions](https://to-be-added)

### Properties

- **Domain:** Online Social\Trust \& Product Review 
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** Yes.
- **Weighted:** No.

|   | **Epinions**  |
|---|---|
| **Nodes** | 131,580  | 
| **Positive Edges** | 589,888  |
| **Negative Edges** | 121,322 |
| **Clustering Coefficient** | 0.06409 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Highland Tribes

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Highland tribes is an undirected signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from sixteen tribes in the Eastern Central Highlands of New Guinea from Kenneth Read in 1954. By analyzing the signed social network of tribes in the Gahuku-Gama alliance structure, Read was able to represent relationships between individual tribes by positive (+1) and negative (-1) weighted edges. Positive edges signify tribes connected by friendship ('rova') while negative edge signify tribes connected by enmity ('hina').
</p>

### Links

- [Highland Tribes](https://to-be-added)

### Properties

- **Domain:** Physical Social
- **Node labels:** No.
- **Directed:** No.
- **Temporal:** No.
- **Weighted:** No.

|   | **Highland Tribes**  |
|---|---|
| **Nodes** | 16  | 
| **Positive Edges** | 29  |
| **Negative Edges** | 29 |
| **Clustering Coefficient** | 0.24073 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Slashdot

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Slashdot is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from Slashdot Zoo <slashdot.org>, a technology news sight that connects users by directed friend and foe relations. On the UI of Slashdot, users are given the option to mark users as friends or foes to influence the scores as seen by each user. If a user took action to mark another account as a friend or foe (+1 or -1, respectively) the score of the recipient's posts will be increased/decreased as shown to the acting user.
</p>

### Links

- [Slashdot](https://to-be-added)

### Properties

- **Domain:** Online Social\Trust
- **Node labels:** No.
- **Directed:** No.
- **Temporal:** No.
- **Weighted:** No.

|   | **Slashdot**  |
|---|---|
| **Nodes** | 82,141  | 
| **Positive Edges** | 380,933  |
| **Negative Edges** | 119,548 |
| **Clustering Coefficient** | 0.02939 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Twitter Italian Referendum

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Twitter referendum is an undirected signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from Twitter users in 2016 as thousands of individuals tweeted about the controversial 2016 Italian Referendum that would amend the Italian Constitution to reform the composition and powers of the Parliament of Italy <https://en.wikipedia.org/wiki/2016_Italian_constitutional_referendum>. An interaction is marked with an edge weight of -1 if two users are classified with different stances, and +1 otherwise.
</p>

### Links

- [Twitter Italian Referendum](https://to-be-added)

### Properties

- **Domain:** Online Social
- **Node labels:** No.
- **Directed:** No.
- **Temporal:** No.
- **Weighted:** No.

|   | **Twitter Italian Referendum**  |
|---|---|
| **Nodes** | 10,885  | 
| **Positive Edges** | 238,612  |
| **Negative Edges** | 12,794 |
| **Clustering Coefficient** | 0.11711 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Wikipedia Conflict

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Wiki conflict is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from a study done by SNAP <https://snap.stanford.edu/data> on the English Wikipedia website. This dataset represents a network of users editing English Wikipedia pages; nodes represent individual users, and edges represent agree or disagreement of information (-1 or 1 representing disagreement or agreement, respectively).

The network contains 7116 nodes, 533439 positive links, 515137 negative links, an average clustering coefficient of 0.07034547221365893, and an overall reciprocity of 0.0.
</p>

### Links

- [Wikipedia Conflict](https://to-be-added)

### Properties

- **Domain:** Online Social
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** No.

|   | **Wikipedia Conflict**  |
|---|---|
| **Nodes** | 7,116  | 
| **Positive Edges** | 533,439  |
| **Negative Edges** | 515,137 |
| **Clustering Coefficient** | 0.07035 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Wikipedia Elections

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Wiki elections is a directed signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from a study done by SNAP <https://snap.stanford.edu/data> on the English Wikipedia website. This dataset represents a network of users that voted for and against each other in admin elections; nodes represent individual users, and edges represent votes (-1 or 1 representing a vote in favor or against, respectively).
</p>

### Links

- [Wikipedia Elections](https://to-be-added)

### Properties

- **Domain:** Online Social
- **Node labels:** No.
- **Directed:** Yes.
- **Temporal:** No.
- **Weighted:** No.

|   | **Wikipedia Elections**  |
|---|---|
| **Nodes** | 7,116  | 
| **Positive Edges** | 78,440  |
| **Negative Edges** | 22,253 |
| **Clustering Coefficient** | 0.07035 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```





## Wikipedia Politics

<p align="center">
  <img width="200" src="/images/network-to-be-added.png">
</p>


### Description
<p align="justify">
Wiki politics is an undirected signed network whose edges are labels with either a positive or a negative sign. This specific network was sourced from a study done by SNAP <https://snap.stanford.edu/data> on the English Wikipedia website. This dataset represents a network of users editing English Wikipedia pages; nodes represent individual users, and edges represent agree or disagreement of information changed after the edit was completed (-1 or 1 representing disagreement or agreement, respectively). Note that a user may revert their own edits, leading to negatively weighted loops.
</p>

### Links

- [Wikipedia Politics](https://to-be-added)

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
| **Clustering Coefficient** | 0.11515 |


### Citing
```bibtex
@inproceedings{to-be-added
}
```