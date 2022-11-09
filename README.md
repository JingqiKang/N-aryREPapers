# Awesome-N-ary-Relation-Extraction

![](https://img.shields.io/badge/Status-building-brightgreen)

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
  </tr>
</thead>
<tbody >
<tr>
	<td><code> Peng</code> </td>
    <td> The dataset in Cross-Sentence N-ary Relation Extraction with Graph LSTMs (Peng  et al., 2017) is widely used in N-ary-Relation-Extraction </td>
    <td> Download: 1. https://drive.google.com/drive/folders/1Jgw6A08nh-4umCV7tfqQ6HFg7mtDwo67?usp=sharing  |  2. https://github.com/freesunshine0316/nary-grn/tree/master/peng_data  |  Paper: https://aclanthology.org/Q17-1008.pdf </td>
    <td>The triples is from GDKD and CIVIC using distant supervision and the text is from PubMed. </td>
    <td>6987 triples, 6087 binary relations.</td>
</tr>


<tr>
	<td><code>AGGCN</code> </td>
    <td>The sentence level dataset used in AGGCN (Attention Guided Graph Convolutional Networks for Relation Extraction) dataset (Guo  et al., 2019) </td>
    <td> Download:    TACRED:https://nlp.stanford.edu/projects/tacred/  |  Semeval-10 Task 8: https://www.kaggle.com/datasets/drtoshi/semeval2010-task-8-dataset  |  Paper: https://aclanthology.org/P19-1024.pdf </td>
    <td>The dataset is introduced in Graph Convolution over Pruned Dependency Trees Improves Relation Extraction(Zhang et al., 2018) and can be used as a sentence level relation extraction task. </td>
    <td>TACRED:106K instances, 41 relation types+ 'none'    |  Semeval-10 Task 8：10717 instances, 9 relation types+ 'none'</td>
</tr>



</tbody >
</table>
</div>
