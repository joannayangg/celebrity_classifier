# Asian Celebrity Classifier!
**Upload a photo, see which east asian celebrity you look most similar to!**

As a kid, I was obsessed with those data science driven "which celebrity are you?" quizzes. However, as an Asian American kid, I was simply always matched with the one or two Asian actresses included in the dataset, or a white actress with dark hair, out of hundreds of other actresses and actors. This is a passion project to rectify that experience to the kid in me :)

Welcome to the "What celebrity are you?", East Asian edition! I pulled 10 of the A100 Honorees (100 Asian Pacific Leaders who made the greatest impact on culture and society over the past year, read more here.). This will take an image of yourself, and return which of the 10 figures you look most similar to (in a ML Model's eyes)!

First, I used Bing Image Downloader to create the dataset and labels. Then, I preprocessed the images using Cascade Classifiers (face and eye), which identify faces in images and crop accordingly. Next, I performed feature extraction, primarily relying on grayscale and wavelet transformations. Finally, I trained machine learning models to predict the celebrity based on the facial image, using Support Vector Machines, Random Forests, and Logistic Regressions. The accuracy of the model is 81.4% when testing on pictures of the celebrities as test data. Finally, I built a user interface, testing the data on my friends' and families pictures, showing them which Asian celebrity they look most similar to! 
