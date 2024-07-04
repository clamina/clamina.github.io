Stylometry is a field of study within computational linguistics and literary theory that focuses on analyzing linguistic style and its variations across different texts or authors. It involves the statistical analysis of writing styles to identify distinctive patterns, characteristics, and authorship based on textual features. 

During our second day of the Introduction to Computation for Literary Studies course, we discussed how to run our own statistical analysis on texts using *Stylo*—a software tool developed for stylometric analysis. It is used within an *R package*, a programming language and software environment for statistical computing and visualizations. *Stylo* was created by the [Computational Stylistics Group](https://computationalstylistics.github.io/) (using the same web-based interface [Github](https://github.com/) that we used to create these blogs and posts!)

*Stylo* is widely used in computational linguistics, digital humanities, forensic linguistics, literary studies, and other fields where the analysis of writing styles and authorship attribution are of interest. It serves as a valuable tool for researchers and analysts who wish to gain insights into textual data through systematic and quantitative stylometric analysis. 

### Author Attribution with *Stylo*

One of the primary applications of *Stylo* is authorship attribution, which involves determining the likely author of a text or identifying the number of authors who contributed to a text based on stylometric similarities and differences. This includes analyzing word frequencies, vocabulary richness, sentence structures, and other linguistic attributes. ​​
To conduct our own analysis of authorship, our instructor directed us to [Posit Cloud](https://posit.cloud—which) is a website that allows anyone “to do, share, teach and learn data science online.”

In Posit Cloud, we used the *R package* to examine a work of co-authorship and see how the program would assess the text's authorship. Alongside this co-authored text, we uploaded a corpus of individual text samples from each author of the original text. From there, the *R package* conducts its own statistical analysis of each author’s texts (examining syntax, word frequencies, etc.) to create a style package for each author. The co-authored text is assessed against the information derived from these style packages—essentially comparing each author’s linguistic style to the style the program detects within the co-authored text. From there, the program can produce different visualizations of its statistical analysis of the texts, like the graph below. 

![](/assets/image/co-authorship.png)

This graph represents the text from left to right, with the word count displayed along the x-axis. From there, we can see how the program attributes certain ranges of words in either red or green—a color for each author. With this visualization, one can return to experts of the text highlighted in either color to assess how the program differentiates each author’s linguistic style. 

### Examining *Stylo* 

Another exercise our instructor led us through required each participant of the course to upload 3-5 texts of their choosing to a corpus. The corpus was extremely diverse, ranging from participants’ own scholarly writing to ancient texts to my own contribution of Sherlock Holmes stories. We asked the *R package* to complete a cluster analysis of the corpus, which instructs the package to examine the texts of the corpus, identify any patterns of similarities between the texts, and create a visualization that groups or clusters the texts by these similarities. Our visualization can be seen below. 

![](/assets/image/clusteranaylsis.png)

Clustered, huh? After the program created this visualization, our class began to examine which texts were clustered together. From there, we began to brainstorm about the possible similarities the program had identified for each cluster. Our forensic analysis did not stop at the end of the *R package*. We continued to question why the program may be sorting certain texts together, how the different languages affected its sorting, and the extent of this tool’s use in scholarship.

 
This was just a taste of the experiments that computational linguists and other digital humanists are conducting using *Stylo*. It’s a fascinating application of both data science and linguistic analysis which contributes to advancements in fields where understanding language and authorship are pivotal. This lesson in stylometry truly cemented the interdisciplinary nature of the digital humanities in my mind, and has opened my eyes to the research collaborations possible across disciplines. 