Text analysis, also known as text mining or natural language processing, involves extracting meaningful insights and patterns from written text. Computational tools can be extremely helpful in extracting patterns in text, especially when there is a large amount of text to cover in analysis. 

Textual visualization refers to the graphical representation of textual data to visually depict patterns, relationships, and trends within the text. By highlighting keywords, phrases, and themes, these visualizations facilitate quicker identification of important information from a text. Visualizations can also bridge the gap between textual complexity and human understanding, making textual data more accessible, interpretable, and actionable. During our first session of the Introduction to Computation for Literary Studies course, we explored three programs used for text analysis and visualization.

### AntConc and Sublime Text

[AntConc](https://www.laurenceanthony.net/software/antconc/) is a powerful and user-friendly corpus analysis tool used primarily for exploring and analyzing textual data. The tool provides functions for clustering words based on their co-occurrence patterns, enabling researchers to explore semantic relationships and thematic clusters within the corpus. Additionally, AntConc offers various statistical measures such as frequency lists, dispersion plots, and lexical density analysis, which provide quantitative insights into the characteristics of the text. While AntConc offers many amazing avenues for textual analysis, it does not offer many visualization options. 

With AntConc, our instructor showed us how we can use the program to create plain txt files (plain text files), which allows operating systems and software applications we would be using throughout the course to recognize the text for computation. 

We sourced our texts from Project Gutenberg, which has txt files available to download. We also discussed different ways for creating our own textual data—from typing up a txt file yourself to scanning text to extract the data. 

![](/assets/image/antconc.png)

[Sublime Text](https://www.sublimetext.com/) is another text editor primarily used for coding and text editing tasks. You can also create txt files from Sublime Text to be exported into different computational programs. 

### Voyant Tools 
[Voyant Tools](https://voyant-tools.org/) is a web-based text analysis and visualization tool designed to facilitate the exploration of textual data. It allows users to analyze and visualize patterns, trends, and relationships within texts through various computational methods.

Voyant Tools offers functionalities such as frequency analysis (word frequency counts), concordance (word contexts), and collocation (word co-occurrence). Users can visualize textual data through interactive visualizations like word clouds, scatterplots, and trends over time, which makes complex textual analysis more accessible and comprehensible.

Here are examples of some visualizations available in Voyant Tools. I uploaded a corpus of five different Sherlock Holmes stories to the program, and Voyant Tools created multiple visualizations based on all five texts! The image below displays a word cloud (top left), textual arc (top middle), and trend graph (top right) of the corpus.

![](/assets/image/voyanttools.png)

From a glance at the word cloud (in the top left) I can see that the words “room,” “night,” “light,” and “bed” are some of the most common words across the five texts I submitted to the program. I begin to wonder why these settings and descriptions are so common within the stories. Could it have anything to do with the Victorian sensation novel and the fascination with the “hidden drama of the home”? Does the recurrence of the words “room” and “bed” speak to a specific trope within detective fiction? 

Additionally, Voyant Tools easily allows one to view words within the context of the text (as displayed in the bottom left widget. If I wanted to visit every instance where the word “light” appeared across the five texts to determine if there were any comparisons of interest, I could easily select my desired word, and Voyant Tools lists every occurrence of the word and its line within the text. A paper analyzing the different domestic settings of Holmes stories, coupled with an appendix of some visualizations cooked up in Voyant Tools, sounds like a good time to me!

### Limitations of These Programs 

These programs are incredibly useful for quantitative data, but not for the “subjective data” that most humanists are interested in. These programs cannot conduct semantic evaluations of texts to interpret the deeper context, implications, and intended message behind pieces of literature. However, the visualizations displayed above can point researchers in the direction of interesting analyses. Brainstorming research questions can flow easily from there.

Additionally, these programs are designed for English and European languages, which makes them not useful for texts in most other languages. This is because of how the program “tokenizes” (or sorts) each word apart from one another—these programs default to separate words by ‘spaces.’ In class, we discussed the possibility of adjusting how the program tokenizes words so that the program can be useful to those studying non-European and non-English texts.  

