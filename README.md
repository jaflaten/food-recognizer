# food-recognizer

## Background about this project 

The idea behind this project is that using computer vision based on deep learning it is potentially possible to revolutionize how we track food intake. By creating a system that can automatically recognize food in pictures that would allow for much simpler logging of food intake. Combined with the possibility to recognize which food is in the picture, this could be linked to a database containing nutritional data such as calorie content and macronutrient composition. This could allow people to get a better understanding of how the food they consume impact their overall health, and helping them to make more informed decisions on what they eat and drink. Such a system could also be integrated in other applications and have many positive benefits, such as helping people live a healthier lifestyle, lose weight, or to reach specific fitness goals. 

## Blog
I wrote a blog post about this project on my [blog](https://ja.flaten.dev/blog/food-recognizer-ai/).

## Application 
I have created a simple Gradio application using the model I trained. The application runs in huggingface.co/spaces and all the required files are available in the repository [https://huggingface.co/spaces/jaflaten/food-recognizer-app/tree/main](https://huggingface.co/spaces/jaflaten/food-recognizer-app/tree/main).

The model itself is hosted on Huggingface hub in another repository [https://huggingface.co/jaflaten/foodmodel/tree/main](https://huggingface.co/jaflaten/foodmodel/tree/main)

## Training the model

The model was trained on Kaggle and the notebook and repositories are the following:

- [Kaggle notebook food-recog-loader](https://www.kaggle.com/code/jaflaten/food-recog-loader/notebook?scriptVersionId=124909439) 
- Kaggle datasets:
    - [Validation dataset](https://www.kaggle.com/datasets/jaflaten/food-validation)
    - [Training dataset](https://www.kaggle.com/datasets/jaflaten/food-training)
    - [Test dataset](https://www.kaggle.com/datasets/jaflaten/food-testing)
    - [The trained model](https://www.kaggle.com/datasets/jaflaten/foodmodel)

