# Indian-Snack-Classification

# In this tutorial, we are going to classify the Indian Snack. Basically, we have 10 different snack types i.e. 'samosa','kachori','aloo_paratha','idli','jalebi','tea','paneer_tikka','dosa',
# 'omlet', and 'poha' so we are going to build the multi-class classification model using Keras. I would like to give first dataset credit to Navin Manaswi and the dataset is available at
# https://github.com/NavinManaswi/IndianSnacks. We can also find the code at the mentioned URL. But we will code it from scratch. Original dataset has only two directories 1) training set 
# (~50K images, each class with ~5K images), and 2) test set (~10K images, each class with ~1K images). As we don't have validation set so we will form validation set (~10K images, each class 
# with ~1K images) from the training set. We are going to use Colab (for more info visit: https://colab.research.google.com) and thanks to Colab for providing GPU access.

# The idea/motivation behind the small tutorial is to explore and understand the data-collection, pre-processing, developing Conv Neural Network model and interpreting the result for the 
# learning purpose.
