# Using Smartphones to Encourage Movement


## Sitting: One of the Most Dangerous Daily Activities

Physical inactivity and sedentary behavior has become a major public health risk around the world. Experts tell us that a minimum amount of daily physical activity is necessary to maintain health and reduce the risk of chronic diseases such as diabetes, heart disease, and cancer. Some researchers have suggested that sitting for long periods of time may in itself contribute to the problem, in addition to the total amount of inactivity. A [study published in 2017](https://mfprac.com/web2018/07literature/literature/Misc/SedentaryMortality_Diaz.pdf) found that sitting in periods of longer than 30 minutes at a time increased mortality risk after control for other factors. The total amount of sedentary time was separately a risk factor. A [follow-up study](https://academic.oup.com/aje/article-abstract/188/3/537/5245876) by the same team, published in January 2019, found that there was no benefit of reducing the duration of episodes of sitting unless those episodes were replaced with physical activity (of any intensity). 

## A Multi-Sensor in Everyone's Pocket

WIth the proliferation of screens of all sizes for both work and entertainment, many people find themselves sitting for much of the day. However, the same devices can also be useful for reminding people to be active. Smartphones contain numerous sensors that can be used to classify movement, particularly the following: accelerometer, gyroscope, and magnetometer. (GPS is also used for detecting movement, but is ineffective indoors.)

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
