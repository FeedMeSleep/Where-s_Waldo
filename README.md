# Wheres Waldo
Machine Learning Project (Finding Waldo)

David San
Jacky Gnong

A CS 4662 Project utilizing Machine Learning to train Neural Networks to be able to find Waldo given original images


# Where’s Waldo Finder


## Team Responsibilities
We are using the Where’s Waldo competition from kaggle.com/residentmario/wheres-waldo for our project. Our responsibilities include brainstorming different ways to tackle the Where’s Waldo finder through the algorithms we learned in class. We brainstormed a couple of different algorithms that could be applied to the images. After figuring out which algorithms were usable, we both worked on the project at a variety of times to see how far each of us could go until we got stuck. Overall, we were both responsible for working on figuring out how to utilize the Neural Networks with our project and also working on this report and slides.

![Kaggle Dataset Webpage](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image8.png)

## Description 
Waldo (originally Wally, but had a varied name depending on localization) is a popular character in a children’s book series called Where’s Waldo. The book was created by Martin Handford, where it consists of a collection of random scenes in each page that also includes Waldo and the reader's goal is to find where Waldo is located. Waldo is a male character that always wears a red and white striped beanie and shirt, glasses, and jeans. As time went on, additional characters were added into the mix, like Woof, Odlaw, and Wenda, but Waldo remained the character that was typically on the forefront.


![Where's Waldo Information](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image4.png)


## Details
The data that we’re using includes multiple pictures from different Where’s Waldo books. It consists of colored, gray scaled, and bw (black and white) pictures of both Waldo and not Waldo. Additionally it also has a couple original pictures from the Where’s Waldo book.  
![Where's Waldo Book](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image10.png)


## Code
Our code has its first section set up so that we import many of the packages we believed we would be using as well as having our images read either through the CSV’s or referencing the image itself. From there, we used Convolutional Neural Networks (CNN) to develop a learning algorithm for the machine to be able to solve the Where’s Waldo games. Additionally we used techniques learned from the Artificial Neural Networks (ANN) to provide another layer of checking the game. 

#### Waldo:

![Waldo1](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image1.jpg)
![Waldo2](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image9.jpg)
![Waldo3](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image7.jpg)

#### Not Waldo:

![NotWaldo1](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image2.jpg)
![NotWaldo2](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image3.jpg)
![NotWaldo3](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image5.jpg)
![NotWaldo4](https://github.com/FeedMeSleep/Where-s_Waldo/blob/david2/report_images/image6.jpg)


## Results
We had to create a CSV file being able to label the pictures which were waldo and not waldo so that we could easily label them for training. Our project is able to train utilizing CNN and ANN while utilizing the provided images to return results of images containing Waldo. The original images are divided up into 64x64, 128x128, and 256x256 images and are split to contain training data that defines the section to express if it contains Waldo or not. The model is then tested on the rest of the data to produce output images either saying if it contains Waldo or not. So overall, our project doesn’t find Waldo specific points to where Waldo is, but it does identify image slices based on whether it contains Waldo or not with a 99% accuracy.

