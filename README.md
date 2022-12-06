# Awesome-N-ary-Relation-Extraction

![](http://img.shields.io/badge/Status-building-brightgreen)

## Contributor

Resource Contributed by [Jingqi Kang](https://github.com/JingqiKang), [Runzhe Wang](https://github.com/sid0527).

## Quick path
- [Resources](#resources)
- [Dataset](#dataset)

## Resources
1. **Cross-Sentence N-ary Relation Extraction with Graph LSTMs** `TACL 2017` [[pdf]](https://aclanthology.org/Q17-1008.pdf) [[code]](https://github.com/VioletPeng/GraphLSTM_release) 
2. **N-ary Relation Extraction using Graph State LSTM**`EMNLP 2018` [[pdf]](https://aclanthology.org/D18-1246.pdf) [[code]]( https://github.com/freesunshine0316/nary-grn) 
3. **Attention Guided Graph Convolutional Networks for Relation Extraction**`ACL 2019` [[pdf]](https://aclanthology.org/P19-1024.pdf) [[code]](https://github.com/Cartus/AGGCN) 
4. **Document-Level N -ary Relation Extraction with Multiscale Representation Learning**`NAACL 2019` [[pdf]](https://arxiv.org/abs/1904.02347) [[code]](https://hanover.azurewebsites.net/downloads/naacl2019.aspx) 
5. **A Dataset for N-ary Relation Extraction of Drug Combinations**`NAACL 2022` [[pdf]](https://arxiv.org/abs/2205.02289) [[code]](https://huggingface.co/allenai/drug-combo-classifier-pubmedbert-dapt) 

## Dataset
<div style="overflow-x: auto; overflow-y: auto; height: auto; width:100%;">
<table style="width:100%" border="2">
<thead>
  <tr>
    <th>Name</th>
    <th>Intro</th>
    <th>Links</th>
    <th>Detail</th>
    <th>Size & Stats</th>
    <th>Used</th>
  </tr>
</thead>
<tbody >
<tr>
	<td><code> Peng</code> </td>
    <td> The dataset in Cross-Sentence N-ary Relation Extraction with Graph LSTMs (Peng  et al., 2017) is widely used in N-ary-Relation-Extraction </td>
    <td> Download: 1. https://drive.google.com/drive/folders/1Jgw6A08nh-4umCV7tfqQ6HFg7mtDwo67?usp=sharing  |  2. https://github.com/freesunshine0316/nary-grn/tree/master/peng_data  </td>
    <td>The triples is from GDKD and CIVIC using distant supervision and the text is from PubMed. </td>
    <td>6987 triples, 6087 binary relations.</td>
    <td>Resources 1|2|3|4</td>
</tr>


<tr>
	<td><code>TACRED</code> </td>
    <td>One of the two sentence level datasets used in AGGCN (Attention Guided Graph Convolutional Networks for Relation Extraction) dataset (Guo et al., 2019) </td>
    <td> Download:https://nlp.stanford.edu/projects/tacred/ </td>
    <td>The dataset is introduced in Graph Convolution over Pruned Dependency Trees Improves Relation Extraction(Zhang et al., 2018) and can be used as a sentence level relation extraction task. </td>
    <td>106K instances, 41 relation types+ 'none' </td>
    <td>Resources 3</td>
</tr>

<tr>
	<td><code>Semeval-10 Task 8</code> </td>
    <td>Another sentence level dataset used in AGGCN (Attention Guided Graph Convolutional Networks for Relation Extraction) dataset (Guo et al., 2019) </td>
    <td> Download: https://www.kaggle.com/datasets/drtoshi/semeval2010-task-8-dataset</td>
    <td>The dataset is introduced in Graph Convolution over Pruned Dependency Trees Improves Relation Extraction(Zhang et al., 2018) and can be used as a sentence level relation extraction task. </td>
    <td>10717 instances, 9 relation types+ 'none'</td>
    <td>Resources 3</td>
</tr>

<tr>
	<td><code>CKB</code> </td>
    <td>It is a gold-standard test set used in Document-Level N-ary Relation Extraction with Multiscale Representation Learning (Jia et al., 2019).</td>
    <td> Download:   https://hanover.azurewebsites.net/downloads/naacl2019.aspx</td>
    <td>The dataset contains document-level annotation of drug-gene-mutation interactions manually curated by JAX. It is a high-quality KB containing facts from a few hundred PubMed articles for 86 genes </td>
    <td> Documents: 118+225 | Facts: 701+1324</td>
    <td>Resources 4</td>
</tr>

<tr>
	<td><code>Drug-combo</code> </td>
    <td>The dataset is introduced in A Dataset for N-ary Relation Extraction of Drug Combinations (Tiktinsky at al., 2022).</td>
    <td>  https://huggingface.co/datasets/allenai/drug-combo-extraction</td>
    <td> It can be used for variable-length n-ary relations and the relation information is of long range dependencies(cross-sentence).</td>
    <td> 1362 train, 272 test instances and  1248 relations.</td>
    <td>Resources 5</td>
</tr>


</tbody >
</table>
</div>
