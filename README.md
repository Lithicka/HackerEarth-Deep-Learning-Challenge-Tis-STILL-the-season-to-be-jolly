# HackerEarth-Deep-Learning-Challenge-Tis-STILL-the-season-to-be-jolly

##Problem statement

An e-commerce platform is getting all geared up for a season clearance sale and plans to leverage social media as the primary channel to reach their audiences. The campaign’s target group are individuals/families that have recently posted a picture of their indoor Christmas decor or are traveling during the holidays. 

You work at a leading social media platform and your team has been tasked to build a product recommendation engine for consumers. As part of the development team, your role is to use Deep Learning to develop a model that classifies images based on elements within the picture. These elements should be related to decor or holiday season vacations, such as a snowman, a Christmas tree, flights, and the like. 

##Dataset

The dataset consists of over 6000 images.

The benefits of practicing this problem by using Machine Learning/Deep Learning techniques are as follows:

This challenge encourages you to apply your Deep Learning skills to build a model that classifies an image based on holiday-related elements.
This challenge will help you to enhance your knowledge of multi-label classification, which is one of the basic building blocks of Machine Learning.
We challenge you to develop a model that successfully identifies holiday-related elements in images and classifies them accordingly.

##Model
TL (Transfer learning) is a popular training technique used in deep learning; where models that have been trained for a task are reused as base/starting point for another model. Xception has been used as a base model for this particular problem. 

Stratified K-fold cross validation technique has been used which is an extension of regular kfold cross validation but specifically for classification problems where rather than the splits being completely random, the ratio between the target classes is the same in each fold as it is in the full dataset.
