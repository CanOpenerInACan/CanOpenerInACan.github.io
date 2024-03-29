# Food Classification Project
---
  This project took a dataset of 12,000 images of food that belonged to one of eleven different categories. I used image classification to build a model that would learn the characteristics of these images and place the image into one of the eleven categories based on the patterns it was noticing. The model that was used for breaking the images down and recognizing the patterns was a neural network called InceptionResNetV2, which could take the images as inputs and place the images into the categories that were set and provided for us.  
  
  
  The idea for this project was to be included in a much larger program which would do a number of things. The goal was to be able to take a picture of a user’s pantry and refrigerator, make an inventory of that user’s available ingredients, and then be able to pull recipes from a website that could be completed with just the ingredients from the user’s pantry. In order for this to work, we would need a neural network that was able to break down each individual item in an image, and then break down exactly what ingredient they had. This would be a key aspect of the app, and any uncertainty from the neural network would need to be dealt with by asking the user what it is seeing before making an assumption on the most likely ingredient and then being wrong about it. The bright side of something like this is that as the user submissions come in, the neural network will keep getting better at what it is seeing and have even more training data to strengthen the model for future users.   
  
  
  In the end, the neural network built for just categorizing the images into the eleven categories was able to return an accuracy of 0.74. There were some areas the model struggled with for various reasons, like a small sample of certain categories and foods that may have fit into multiple categories but for the sake of the dataset were thrown into just one. I was pleased with how the model performed and how it was able to categorize the images relatively accurately. The more this model could learn from user submissions, the better it would perform in the future.   
  
  
  For the full write-up and code for this project, click <a href="https://github.com/CanOpenerInACan/DSC_Projects/tree/main/Food%20Classification">here</a>.
