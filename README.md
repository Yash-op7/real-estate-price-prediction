# real-estate-price-prediction

First cleaned and preprocessed a housing prices dataset then built a linear regression model then export it to a pickl file which is consumed and served by a http django server which is deployed to an AWS EC2 instance and is accessed by a Next.js frontend.


## Part-1: Load the Data and perform cleaning and preprocessing

This is the dataset: https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data?resource=download

This is the training d‸ataset, I will use supervised learning to predict the price variable which is the target variabel based on the input features which are area_type, availibility, location, size, society, area, bath and balcony.

