The last topic we discussed in the Introduction to Computation for Literary Studies course was image mining and analytics. Image mining is the process of extracting meaningful patterns, relationships, and knowledge from large collections of digital images. It combines many different techniques, including pattern recognition, image classification, object detection and recognition, artificial intelligence machine learning, and many more. 

Image mining technologies are used in the fields of medicine, security and surveillance, agriculture and food security, infrastructure development, etc. Image analytics are also used within the field of digital humanities, and we discussed how this computation technique can be applied to literary studies.
 
While visual analysis might appear as a separate entity from literary studies, many scholars utilize both visual and textual media as sources for their research. The study of visual rhetoric of newspaper advertisements or an examination of cultural symbolism are all of interest to humanist scholars. Image mining and analytics can aid in scholarly research by identifying patterns, connections, and influences across a visual corpus. 

With the rise of digital archives, image analytics can be useful for sorting through and categorizing digitized literary manuscripts, photographs, and artwork. Our class discussed how image analytics could be employed on manuscripts to examine penmanship to determine the authorship of certain texts. The possibilities for image mining and analytics in the field of humanities are remarkable.

### Running An Image Analytics Workflow

To further explore and discuss image mining and analytics, our instructor directed us to an open-source data visualization and analysis tool called [Orange Data Mining](https://orangedatamining.com/). Orange has a graphical interface that allows users to drag and drop widgets to create data analysis workflows—sequences of tasks performed by the machine for the desired data analysis. Our instructor gave us an *OWS* file that contained a Clustering and Classification workflow to upload in Orange. The workflow can be seen below. 

![](/assets/image/orange.png)

This workflow allows the user to upload a corpus of images to be sorted in a hierarchical clustering visualization and an image grid. Each participant was asked to compile a corpus of related images for the workflow to sort and categorize. The purpose of this exercise was to see how the workflow would sort the images compared to how we would expect it to sort them.

I decided to upload a corpus of environmental land art and see how the computer would organize the images. I uploaded 70 images from 7 different environmental artists. Would the workflow sort the images by artist? Would it compile similar shapes together, like spirals and nests? Would it sort the art by the materials used, such as recycled materials versus stones and branches? Would the workflow be able to detect the theme of the most abstract pieces? Would it sort by theme? Could the program even detect a piece of artwork’s “theme”? 

#### Here is the hierarchical clustering visualization. From this visualization, I selected sections to send to an image viewer, where I could see which images were clustered together by the program. 

![](/assets/image/environcluster.png)
![](/assets/image/environ2.png)

From this cluster, it appears that the workflow combined some of the images with warmer red and orange tones. A few of the images in this cluster feature human beings, so it is possible that the program recognized the people and compiled them into a cluster together. Additionally, in the bottom left corner of the cluster, there are images containing non-natural materials, which may have been the object detection processing of the workflow. 

What I find so interesting about this cluster in particular is how many of the pieces of art center around light. The two images in the middle are pieces that represent the sun. The two images directly to their left are the same piece of sculpture but with one photo taken during the day and the other at night. Other images in this cluster feature landscapes of stormy skies, whose shadows play a focal point of the images. Is the program recognizing a theme of light or manipulated light in these images? Or is this cluster sorting the images by a factor I am overlooking? 

#### The second visualization this workflow produced was an image grid of the entire corpus. 

![](/assets/image/environ1.png)

From this image grid, I can start to hypothesize how the program sorted the corpus. It seems that many of the spiraling sculptures and monuments are close together, as well as some of the images with similar materials. It also appears that the images are sorted by color. Many of the blues and greens are clustered together, while lighter whites and grays cluster together in other sections. The program may be sorting the images by many factors at once, which explains why some appear as outliers when I see obvious similarities. 

As a class, we shared interesting insights we pulled from this exercise. One participant shared that she uploaded a corpus of paintings of animals, and the program had a difficult time matching abstract animals to their discernable counterparts. Others noticed that the program produced different grids when they adjusted the workflow to analyze the images against a “Painters'' profile. The categorization depends on what images the specific program was trained on. Our isntructor suggested that the program may be able to recognize the landscapes and colors of images because those features are apparent within he impressionist painting it is familiar with. 

This exercise was a great way for participants of the course to explore an image analytic program, as well as examine how the machine categorizes a visual corpus. I can see how these tools can be used to help spot visual patterns that may have been overlooked by the human eye. These programs kight be able to give scholars a new perspective on their corpus 
