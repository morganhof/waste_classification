## Problem Statement  
According to the EPA, of the household waste that ended up in landfills in 2018, 24% of that material was food waste, 18% was plastic materials, and 12% was paper/paperboard. Using a variety of images, I'll build convolutional neural network models that will accurately classify whether an item should be composted, recycled, or trashed to help everyday consumers determine which bin their waste should go in. I'll build an app that people can upload a photo to and it will determine which class their waste belongs in.

* CITATION: https://www.epa.gov/facts-and-figures-about-materials-waste-and-recycling/national-overview-facts-and-figures-materials

* Looking at accuracy?  

## Assumptions  
* Everyone has access to compost, recycling, and trash services.  
* The composting, recycling, and trash rules of my neighborhood are the rules in other locations.  
* When in doubt, throw it out... If the image contains two different classifications - for example a banana (compost) with a sticker (trash) on it - the image will be classified to the category that is not obvious. So, the example above would be categorized as trash.  
  
## Risks
* Model may misclassify items, so this model may not be the holy grail for sorting.  
  
## Data  
* Sources:  
* Data Dictionary: (data-types)  
  
## EDA, Cleaning & Munging  
* Organize data
* Write functions to clean, where applicable
* Highlight assumptions
* Comment on approach
* Examine distributions of each class
* Identify outliers
* Identify missing data and look for patterns of missing data
* Describe how your EDA will inform your modeling decisions and process