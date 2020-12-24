# Detect temple tomb using custom vision

## Use Case

Create a custom vision ai model to find which temple and what tomb. Idea is to get tag some pictures and then train a model to detect which which tomb belongs a temple.

## Prerequstie

- Create a Azure Account
- Create a resource group
- Create Cognitive services account for custom vision
- Choose free version F0
- will give you 2 projects.
- Select Image classification as Project Type

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/workspace.jpg "Logo Title Text 1")

## Image collection

- Collect image from google or bing
- Choose public data set
- download the image
- save them to disk
- Check the CustomVision folder
- Go to Customvision.ai web site

## Image labelling

- Create a project in custom vision
- Create labels

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvisionlabels.jpg "Logo Title Text 1")

- Click one image and select the label
- Keep selecting each image and tag the label

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision1.jpg "Logo Title Text 1")

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision2.jpg "Logo Title Text 1")

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision3.jpg "Logo Title Text 1")

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision4.jpg "Logo Title Text 1")

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision5.jpg "Logo Title Text 1")

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision6.jpg "Logo Title Text 1")

## Training

- On the top of the page there in training button

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision10.jpg "Logo Title Text 1")

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision11.jpg "Logo Title Text 1")

- Click training
- Wait for training to complete
- Once complete check the performance of model
- Quick Training

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision7.jpg "Logo Title Text 1")

- Advance Training
- Set limit to stop so that price is not too high

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision8.jpg "Logo Title Text 1")

- if model performance if low add more images to all labels and retraining

## Quick Test

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision9.jpg "Logo Title Text 1")

## Publish

- if you want to consume the rest API click Publish

![alt text](https://github.com/balakreshnan/templeaimodel/blob/main/Images/customvision12.jpg "Logo Title Text 1")

## Conclusion

- Done