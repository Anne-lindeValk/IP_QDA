# IP_QDA: Lab Journal
1. What was my goal of today?
2. What did I achieve? Optional: refer to code snippets
3. Any challenges? Did I solve them or still work in progress?
4. Short description of genAI use
5. If applicable, what to work on next time?

## 12-06-2026
### Anne-Lin
1. Writing a script to open the images from the different data sets and to split the multichannels such that from every image the nuclear channel and reporter channels are splitted, package used was opencv
2. No
3. Problems were about reading in the image file
4. I used AI to help with finding the right directory path
5. To continue with working on the import_image script
### Lema
1. 
2. 
3. 
4. 
### Sophie
1. 
2. 
3. 
4. 

## 13-06-2026
### Anne-Lin
1. Continuing with writing the script to read and split the images, found out that opencv is not the right package
2. Reading the image file was successfull, but splitting the multi channels not
3. Need to dive into the imagefile structure and understand how the image data is used for further analysis, also, 
    since we are working with z-stack multi channel images --> 
    - need to confirm whether every image has the same nuclear-reporter channel organisation
    - which package to use to open and split channels
    - think about which z-stack number are we going to use for segmentation
4. Used AI to find out how to use openCV and found out that this is not the right package. 
5. Further work on this script 