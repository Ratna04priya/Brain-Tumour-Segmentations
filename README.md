# Brain-Tumour-Segmentations
*Detection of Brain Tumour using the given MRI Image*

## Indroduction 

 The Brain Tumor is affecting many people worldwide. It is not only limited with the old age people but also detected in the early age. Brain Tumor is the abnormal growth of cell inside the brain cranium which limits the functioning of the brain. Early detection of the brain tumor is possible with the advancement of machine learning (ML) and image processing (IP) .In this paper stages of image processing are discussed and overview of the analogous papers are quoted by analyzing several research papers. This paper provides gist of technologies which can be used to predict brain tumor.
 This project is using Image processing techniques like 
 >1.Converting Image into gray scale
 
 >2.Median Filtering
 
 >3.Edge Detection
 
 >4.Thresholding
 
 >5.Watershed Algorithm
 
 ## Step Wise Processing

### Reading Real Image
 ![GitHub Logo](/img/1.png)
 
 ### Converting to Greyscale
  ![GitHub Logo](/img/2.png)
  
### Median Filtering

 ![GitHub Logo](/img/3.png)

### Edge Detection

 ![GitHub Logo](/img/4.png)
 
 ### Thresholding
  Setting the threshold value to maximum value
 
  ![GitHub Logo](/img/5.png)
  
  Threshold the pixel values
  
   ![GitHub Logo](/img/6.png)

### Determining foreground and background

 To remove any small white noises in the image using morphological opening. 
 ![GitHub Logo](/img/7.png)
 
### Dilation increases object boundary to background
  ![GitHub Logo](/img/8.png)

###  White region shows sure foreground area
 ![GitHub Logo](/img/9.png)
 
### Watershed Algorithm
 ![GitHub Logo](/img/10.png)
 
### Marker Labelling
 ![GitHub Logo](/img/11.png)
 ![GitHub Logo](/img/12.png)
 
 ## Morphological Operations
 Opening is achived by errosion followed by dilation
 The basic purpose of the operation is to show only that part of the image having 
 more intensity which has the tumor that is the part of the image forming our desired extraction.
 
  ![GitHub Logo](/img/13.png)
  ![GitHub Logo](/img/14.png)




 

## Output

<p align="center"> <img src="output_brain.gif"/> </p>

