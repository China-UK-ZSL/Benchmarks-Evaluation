# Benchmarks-Evaluation



# Open Benchmarks of Zero-shot Learning (ZSL)

## [Content](#content)

<table>
<!-- <tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr>  -->

<tr><td colspan="2"><a href="#computer-vision">1. Computer Vision</a></td></tr>
<tr>
    <td>&emsp;<a href="#image-classification">1.1 Image Classification</a></td>
    <td></td>
    <!-- <td>&ensp;<a href="#graph-types">1.2 Image Recognition (Multi-label)</a></td> -->
</tr>
<tr>
    <td>&emsp;<a href="#">1.3 Action Recognition</a></td>
    <td>&ensp;<a href="#analysis">1.4 Visual Quesition Answer</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#efficiency">1.5 Image Retrieval</a></td>
    <td></td>
</tr>
<tr>
    <td colspan="2"><a href="#natural-language-processing">2. Natural Language Processing</a></td></tr> 
<tr>
    <td>&emsp;<a href="#text-classification">2.1 Text Classification</a></td>
    <td>&ensp;<a href="#chemistry-and-biology">2.2 Fine-grained Named Entity Typing</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#knowledge-graph">2.3 Relation Extraction</a></td>
    <td></td>
</tr>
<tr>
    <td colspan="2"><a href="#applications">3. Knowledge Graph Refinement</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#computer-vision">3.1 Link Prediction with unseen relations</a></td>
    <td>&ensp;<a href="#natural-language-processing">3.2 Link Prediction with unseen entities</a></td>
</tr> 
<tr>
    <td colspan="2"><a href="#applications">4. Graph</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#generation">4.1 </a></td>
    <td></td>
</tr> 

</table>




## [Computer Vision](#content)

### [Image Classification](#content)

| Dataset | Size | Granularity | Split (Seen/Unseen) | # Images | Side Information | Sources |
| :----: | :----: | :----: | :----: | :----: | :---- | :----: |
| Attribute Pascal and Yahoo (aPY) | small | coarse | 20/12 | 15339 | attribute | [Paper](https://www.cs.cmu.edu/~afarhadi/papers/Attributes.pdf) [Data](https://vision.cs.uiuc.edu/attributes/)|
| Animals with Attributes1 (AwA1) | medium | coarse | 40/10 | 30475 | attrbute | [Paper](https://hannes.nickisch.org/papers/articles/lampert13attributes.pdf) [Data](http://pub.ist.ac.at/~chl/AwA/)|
| Animals with Attributes2 (AwA2) | medium | coarse | 40/10 | 37322 | attrbute | [Paper](https://arxiv.org/pdf/1707.00600.pdf) [Data](http://cvml.ist.ac.at/AwA2/)|
| Caltech-UCSD- Birds 200-2011 (CUB) | medium | fine | 150/50 | 11788 | attribute, hierarchy| [Paper](http://www.vision.caltech.edu/visipedia/papers/WelinderEtal10_CUB-200.pdf) Data|
| North America Birds (NAB) |  |  |  |  | attribute, hierarchy | [Paper](https://gvanhorn38.github.io/assets/papers/building_a_bird_recognition_app.pdf) Data|
| SUN | medium | fine | 645/72 | 14340 | attribute | [Paper](https://cs.brown.edu/~gmpatter/pub_papers/SUN_Attribute_Database_CVPR2012.pdf) Data|
| ImageNet | large | coarse & fine |  |  | class hierarchy from WordNet, word embeddings of class names | Paper Data|

- The datasets of aPY, AwA1, AwA2, CUB, SUN and ImageNet have a [standardization version](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/zero-shot-learning/zero-shot-learning-the-good-the-bad-and-the-ugly), which is widely used now with more standardized data splits, image features and attribute vectors.
- evaluation metrics (accuracy)







## [Natural Language Processing](#content)

### [Text Classification](#content)