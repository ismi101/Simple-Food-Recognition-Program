# Simple-Food-Recognition-Program
This project involves training a VGG-19 model to classify images of food commonly available in my university's cafe/shops, such as chicken-rice, spaghetti, chocolate cakes, and sandwiches. The goal is to create a system that predicts the class of foods available in cafe/shops, facilitating the estimation of food pricing based on the recognized class.

Using 100 images for each food class found on Google Images. (train-test-split = 80% : 20%) (val = 20% of train data)

# Structure of Dataset

input ("/input")

    -test
    
        ChickenRice (64 images)

        ChocolateCake (64 images)
        
        Sandwich    (64 images)
        
        Spaghetti   (64 images)
        
    -train
    
        ChickenRice (20 images)

        ChocolateCake (20 images)
        
        Sandwich    (20 images)
        
        Spaghetti   (20 images)
        
    -val
    
        ChickenRice (16 images)

        ChocolateCake (20 images)
        
        Sandwich    (16 images)
        
        Spaghetti   (16 images)

("/new_test") #subdirectory containing untrained images taken from my university's cafe/shops to be used to test the model.
