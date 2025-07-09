# Infrared Thermography Temperature Prediction

Infrared Thermography Temperature Prediction is a regression task aimed at predicting a person's core body temperature using non-contact facial measurements. The dataset used for this prediction consists of features computed from an Infrared Thermography (IRT) system, which captures facial skin temperature, along with environmental data. These features describe various thermal characteristics of the face and the conditions under which they were measured. The dataset is the "Infrared Thermography Temperature Dataset", which is publicly available from the UCI Machine Learning Repository and PhysioNet.


The dataset contains the following information for each instance:

1. Subject ID: A unique identifier for each sample.
2. Oral Temperature: The target variable, representing the clinically measured oral temperature that serves as the reference core body temperature.
3. Demographic Features: Categorical information including the subject's gender and age range.
4. Ambient Temperature (Tatm): The temperature of the surrounding environment.
5. Humidity: The relative humidity in the environment.
6. Distance: The distance between the subject and the IRT device.
7. Canthus Temperature (e.g., TRC1): The average temperature of the highest four pixels in a square around the right canthus, a region near the inner corner of the eye.
8. Forehead Temperature (e.g., TFHCC1): The average temperature value in the center point of the forehead.
9. Maxilla Temperature (Max1): The maximum temperature measured within the whole face region.


These features provide quantitative measurements that can be used to assess a person's thermal state from a distance. By training a machine learning model on this dataset, it is possible to develop a predictive model that can assist in rapid, non-contact fever screening for public health applications.
