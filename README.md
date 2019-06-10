# NetEmb Datasets
A collection of real-world networks/graphs for Network Embedding

by Chengbin HOU 2018

## Why this repository
As a beginner who has just entered this field, it is time-consuming to find datasets from different websites. And it might be painful to transform different formats in some required format. In this repository, we directly provide one of commonly-used formats as used in [OpenANE](https://github.com/houchengbin/OpenANE) and [OpenNE](https://github.com/thunlp/OpenNE). We hope this saves your time.

### One of commonly-used formats:
```
*--------------- Structural Info (each row) --------------------*
adjlist: node_id1 node_id2 node_id3 ... (neighbors of node_id1)
or edgelist: node_id1 node_id2 weight (weight is optional)
*--------------- Attribute Info (each row) ---------------------*
node_id1 attr1 attr2 ...
*--------------- Label Info (each row) -------------------------*
node_id1 label1 label2 ...
```

Please consider citing the following paper if this repository is useful for your research.
```
@article{hou2019abrw,
  title={Attributed Network Embedding for Incomplete Attributed Networks},
  author={Hou, Chengbin and He, Shan and Tang, Ke},
  journal={arXiv preprint arXiv:1811.11728v2},
  year={2019}
}
```

## Original datasets
Due to the storage limit in Github, we only provide well-transformed files in the format as described above.
<br> Nevertheless, we also offer the hyper-links to the corresponding original datasets before transformation: [cora](https://github.com/thunlp/OpenNE), [citeseer](https://github.com/kimiyoung/planetoid), [pubmed](https://github.com/kimiyoung/planetoid), [dblp](https://github.com/shiruipan/TriDNR/tree/master/data), and [mit, stanford, nyu, uIllinois](https://www.sciencedirect.com/science/article/pii/S0378437111009186). 

Contact me chengbin.hou10@foxmail.com, if you need python script for such transformation or any other questions.

## Contribution
Please consider to contribute if you have dataset in the format as described above. We will announce your contribution in this repository.

## Useful links to network/graph datasets
https://snap.stanford.edu/data/ <br>
https://linqs.soe.ucsc.edu/data <br>
https://aminer.org/data <br>
http://socialcomputing.asu.edu/pages/datasets <br>
http://networkrepository.com/ <br>
http://cnets.indiana.edu/resources/data-repository/ <br>
https://sites.google.com/site/ucinetsoftware/datasets <br>
http://vlado.fmf.uni-lj.si/pub/networks/data/ <br>
http://konect.uni-koblenz.de/ <br>
http://www.sociopatterns.org/datasets/ <br>



