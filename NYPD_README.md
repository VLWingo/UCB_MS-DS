When I started this project before the current semester, I downloaded the data instead of accessing it from URL because I did not trust that it would always be there and I detested pinging the site so much when debugging code. 
While I'm aware this bad practice, it seems I was right, because while peer reviewing others' work, the data looked different and I would have to start over again.
So I have included the file and kept the code as-is.
I received a comment on my assignment that it was difficult to use because of the packages. Following is a list of packages and how the code is setup.

packages involved: tidyverse, dplyr, lubridate, ggplot2, chron, vegawidget, reticulate

In order to use the Python chunks in R, you will need to create a virtual environment (I did this via anaconda) that contains the packages 'altair' and 'pandas'. I named it "r-reticulate" to be easy to remember what it is for.
You will then go to the global options of R Studio, navigate to the Python tab, and select this virtual environment as the Python interpreter. 
Next, in the console, you'll enter install.packages("altair") and then altair::install_altair().
The code SHOULD work after that. 

I liked altair's visuals when working with it for the Intro to Data Visualization course and I immediately knew how to code it up for what I wanted. 
Despite what looks like quite a few people pushing for native support in R, they haven't resolved some underlying issues that make this a bit more annoying than I thought it would be. 

I advise you to knit to HTML, the altair plots will not knit into PDF for reasons I didn't figure out.

I have added a knitted HTML file just in case.
