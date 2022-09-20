## Multi-Frequency RF Sensor Based Human Activity Recognition : MultiModal Deep Learning Approach 
<img width="1046" alt="Screenshot 2022-09-20 at 2 25 07 PM" src="https://user-images.githubusercontent.com/54806252/191214369-b084620c-293c-49df-9a7a-2fb684372e29.png">

### ✯ Introduction
* Human Activity Recognition (HAR) is of great value in a wide range of real-world applications, such as health, fall detection and smart home.
* There are generally two types of solutions for HAR: device-based and device-free.
* Device-based solutions rely mostly on wearable devices such as smartphones and smart watches. However, these solutions often cause discomfort and extra burden.
* To overcome the weaknesses, device-free solutions utilizing cameras and Radio-Frequency (RF) signals have later come into view.
* Unlike camera based solutions, RF-based approaches do not raise privacy concerns, and are not affected by temperature or lighting conditions.
* Therefore, RF-based solution has become a promising candidate for indoor HAR, leading to a large amount of research contributions recently

### ✯ Methodology
<img width="1086" alt="Screenshot 2022-09-20 at 4 21 05 PM" src="https://user-images.githubusercontent.com/54806252/191240778-b851092e-5874-469a-9769-3f27cb10bd8e.png">

### ✯ Dataset Preparation
* Original dataset was acquired from [1].
* Three different sensors and a total of 11 diﬀerent activities and ambulatory gaits were considered, as listed in the Figure 1.
* The images from the respective sensors were resized to 128x128.
* Then the data from the respective sensors was splitted into train,validation and test sets.

### ✯ Single Modal Model Architecture
<img width="1485" alt="Screenshot 2022-09-20 at 4 44 45 PM" src="https://user-images.githubusercontent.com/54806252/191243852-39bafd6f-eed6-40fe-b54e-0cbbce2484c3.png">

### ✯ Multiple Modal Architecture
<img width="1218" alt="Screenshot 2022-09-20 at 4 54 52 PM" src="https://user-images.githubusercontent.com/54806252/191247290-db808501-e8b6-416f-8c14-a726ecbd0692.png">
