# Using Smartphones to Encourage Movement


## Sitting: One of the Most Dangerous Daily Activities

https://academic.oup.com/aje/article-abstract/188/3/537/5245876?redirectedFrom=fulltext


## A Multi-Sensor in Everyone's Pocket

Smartphones contain numerous sensors useful for classifying movement, particularly the following: accelerometer, gyroscope, and magnetometer. (GPS is also useful for detecting movement, but is ineffective indoors.)

Continuously polling the sensors uses a lot of power and would drain phone batteries quickly. Therefore, a useful algorithm should be able to classify activities based on relatively infrequent polling of sensors.


## Human Activity Recognition


## The Real World Dataset

https://sensor.informatik.uni-mannheim.de/#dataset_realworld
The data set covers acceleration, GPS, gyroscope, light, magnetic field, and sound level data of the activities climbing stairs down and up, jumping, lying, standing, sitting, running/jogging, and walking of fifteen subjects. For each activity, we recorded simultaneously the acceleration of the body positions chest, forearm, head, shin, thigh, upper arm, and waist. Each subject performed each activity roughly 10 minutes except for jumping.

## Exploratory Data Analysis

See Notebook for details.

## Correcting the Labels


## Separating Data into Train and Test Sets


## CNN-GRU Model

## Model Validation

## Use Cases

## Further Extensions

