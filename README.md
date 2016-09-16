# biogas-literature-visualization

Click on the images below to see different parts of the visualization:

<table><tr>
<td>
<a href="https://cbdavis.github.io/biogas-literature-visualization/index.html"><img src=./ScreenShots/Biogas20Topics.png height=200></a>
</td>
<td>
<a href="https://cbdavis.github.io/biogas-literature-visualization/index.html#/bib"><img src=./ScreenShots/BiogasLiterature.png height=200></a>
</td>
<td>
<a href="https://cbdavis.github.io/biogas-literature-visualization/index.html#/model/yearly"><img src=./ScreenShots/BiogasLiteratureTimeLine.png height=200></a>
</td>
</tr></table>

The topic modelling is a machine learning algorithm which is able to create word clouds of the feeding text based on the frequency and significance of the word itself. This algorithm is implemented in a program called [MALLET](http://mallet.cs.umass.edu/). The results are then visualized using the [dfrtopics package for R](https://github.com/agoldst/dfrtopics). The feeding text is a list of references which includes titles, abstract, year and name of authors and journals. With the graphic design, this technique can also present the development of each topic in time- scale. For more information of this technique please check the article of [Blei et al. (2003)](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)

Please note that this topic modeling programme is only able to process the information on the feeding text, thus the more refined the text, the more correct the result. Since the main concern is the development of biogas in Netherlands, only research about biogas which is carried out by Dutch institutions and research about Dutch biogas carried out by foreign institutions are considered. In other words, the list that is fed to the coding program was checked manually to be certain that all the references on it contribute to the knowledge of biogas development in the Netherlands.

In the first experiment, the search website of "Web of Science" was used; the reseach word is "biogas" and the refined criteria is "research from the Netherlands". Momentarily, this website allows the extraction of the searched result lists in the form of a text file to the computer which created good match for the topic modelling engine. Despite the refining functions, 35/270 suggested publications from Web of Science were not directly related to the Dutch biogas system, hence they were excluded from the feeding text. The shown result was derived from the best matched 235 articles. 

Click on this link to see the result! https://is.gd/cbtWXr
