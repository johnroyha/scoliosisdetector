# Scoliosis Detector
## Inspiration
Our experience with scoliosis inspired us to build a website that shows you how to do the therapy/exercise by yourself during covid without having physical contact with the orthopedic doctors when it is not necessary. There are people who have scoliosis but can’t get the care that they need from orthopedic doctors due to COVID or other reasons. Our project helps users manage their scoliosis without having the need to leave their house.

## What it does
Our project helps users in identifying, understanding, and managing scoliosis. First, we ask the user to upload an image of their back. Then, with machine learning, our app can understand the type of scoliosis that the user has. After identifying the type of scoliosis, our app gives the user information about the scoliosis and exercises and doctor recommendations to manage it.

## How we built it
Our project works by using Azure’s CustomVision API to identify the type of scoliosis someone may have. We trained a model with the different types of scoliosis and then used the user’s uploaded images to categorize their scoliosis type. By using node.js and express, we were able to render the appropriate page (depending on the type of scoliosis) and display information that is useful in the user’s case

## Challenges we ran into
Training the CustomVision API was harder than expected. We had to process the images in different ways to find the one that gave the most accuracy with the API.

## Accomplishments that I'm proud of
We are proud of getting the machine learning to work by training and classifying data because this was a new thing learned among the members.

## What I learned
I learned how to use Azure Custom Vision API for a simple way to incorporate ML/AI technologies into our project. We learned about website development in backend/frontend with MERN stack

## What's next for ScoliNosis
We would love to implement additional classification that gives the user more detail about the scoliosis that they have. We would also like to implement a feature where users can track their progress.

## Links
[Scoliosis Detector](obscure-badlands-65461.herokuapp.com) </br>
[Devpost](https://devpost.com/software/scolinosis?ref_content=user-portfolio&ref_feature=in_progress)
