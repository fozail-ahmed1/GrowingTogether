# GrowingTogether

## Introduction

This repository contains the information about my final year project titled "Wearable Device using AI and IoT for Assessment of Fetal &amp; Maternal Well-being During Pregnancy". Our project aims to provide a non-invasive and continuous monitoring solution to track the health parameters of both the mother and the fetus throughout the pregnancy period.

Unfortunately, the repository does not include the source code for the web application, machine learning models, or IoT device. This limitation arises from privacy concerns and copyright considerations.

The research paper associated with our project can be found at the following link: https://www.researchgate.net/publication/371159293_Wearable_Device_using_AI_and_IoT_for_Assessment_of_Fetal_Maternal_Well-being_During_Pregnancy

## Key Features

* Continuous monitoring of fetal and maternal health parameters.
* Real-time data collection and analysis.
* AI-powered algorithms for intelligent data processing.
* Integration with IoT infrastructure for seamless connectivity.
* User-friendly mobile application for data visualization and risk predictions.

## Architecture 

The architecture of the project highlights the three key modules: IoT Device, Machine Learning Models, and Web Application.

1. **IoT Device Module**
   - Wearable Device: The wearable device, in the form of a belt, is equipped with high-end sensors such as MAX 30100 integrated pulse oximetry sensor, Blood Glucose sensor, Temperature sensor, and an accelerometer.
   - ESP32 MCU: An ESP32 microcontroller unit is used, offering integrated Wi-Fi and dual-mode Bluetooth functions. It connects the sensors and enables efficient data transmission.
   - Safety Certification: Ensured that the necessary components and sensors used in the wearable device are certified for safe use by expectant mothers.
   - ThingSpeak Integration: Use the ThingSpeak IoT analytics platform to send health vitals collected from the wearable device to the cloud. Utilize the ThingSpeak API service for data transmission.
   - Write API Key: Use the Write API key provided by ThingSpeak to write the readings from the wearable device to the cloud.

2. **Machine Learning Models Module**
   - Overall Pregnancy Risk Prediction: Developed a machine learning model that predicts the overall pregnancy risk based on the health vitals collected from the IoT device.
   - Pre-eclampsia Risk Prediction: Created a machine learning model that predicts the risk of pre-eclampsia using the health vitals obtained from the wearable device.
   - Gestational Diabetes Risk Prediction: Built a machine learning model that predicts the risk of gestational diabetes based on the health vitals gathered from the IoT device.
   - Fetal Heart Rate Classification: Developed a machine learning model that classifies fetal heart rates into categories such as suspicious, pathological, or normal. The model takes ultrasound values provided by the doctor as input.

3. **Web Application Module**
   - Growing Together: Developed a user-friendly web application called "Growing Together" that provides a responsive interface accessible on all devices.
   - Home Page: Created the home page from where users can access two dashboards: one for the mother and another for her doctor.
   - Authentication: Implemented a login feature to authenticate the mother and doctor before accessing their respective dashboards.
   - Mother's Dashboard: Designed the dashboard for the mother, displaying health vitals from the IoT device in a user-friendly interface. Provide lifestyle and well-being recommendations such as exercise and diet during pregnancy. Allow the mother to enter emergency contact information to receive alerts if her health vitals deviate from normal levels.
   - Doctor's Dashboard: Create a dashboard for the doctor, providing access to four machine learning models: overall pregnancy risk prediction, pre-eclampsia risk prediction, gestational diabetes risk prediction, and fetal heart rate classification. Load health vitals directly from the patient's IoT device and display the results of the machine learning models on the doctor's screen.

## Preview

### 1. IoT device
![iot](https://github.com/fozail-ahmed1/GrowingTogether/assets/96954007/919be982-942d-48f6-a405-aeefea8d4444)

### 2. Mother's Dashboard
![Screenshot (55)](https://github.com/fozail-ahmed1/GrowingTogether/assets/96954007/2c17a960-7872-4b09-8c78-cd5a81522467)

### 3. Machine learning models for risk prediction on doctor's dashboard
![Screenshot (56)](https://github.com/fozail-ahmed1/GrowingTogether/assets/96954007/238fff6d-26e9-41d7-bb1f-f7729bc8ab93)

### 4.  Machine learning model for fetal heart classification on doctor's dashboard
![Screenshot (54)](https://github.com/fozail-ahmed1/GrowingTogether/assets/96954007/cd896b03-1cec-4e30-8721-62beaf1f199a)

<!-- ### Want to see all the pages? [Click Here](PreviewImages.md) -->

## Tech Stack:

 - Arduino 
 - ThingSpeak
 - Python
 - Django
 - JavaScript
 - Bootstrap
 - CSS
 - HTML

## Project achievements 

1. Winner of a paper presentation competition held in B.M.S. Institute of Technology and Management for a research paper titled “Wearable Device using AI and IoT for Assessment of Fetal and Maternal Well-Being During Pregnancy” in Nov. 2022.
2. Achieved 2nd runner-up at TECHNOVA-2K23, a state-level project exhibition with 60+ teams at RRIT for the project "Wearable Device using AI and IoT for Assessment of Fetal and Maternal Well-Being During Pregnancy".
3. The research paper titled “Wearable Device using AI and IoT for Assessment of Fetal and Maternal Well-Being During Pregnancy” was awarded best paper at
International Conference of Computer Science Technology Allies in Research (ICCSTAR) held at RRIT on May 26th and May 27th 2023.
4. The paper has been accepted for publication in the esteemed journal IJERT.
5. This project received special mentions at ProTatva-2k23 held at RV Institute of Technology and Management in Apr. 2023.

## Contributors

Team Localhost consisting of <br>
1. <a href="https://www.linkedin.com/in/fozail-ahmed1/">Fozail Ahmed </a>
2. <a href="https://www.linkedin.com/in/ananya-bhombore-674870245/">Ananya Bhombore </a>
3. <a href="https://www.linkedin.com/in/mrudula-s-prassad-24712a16b/">Mrudala S Prasad </a>
4. <a href="https://www.linkedin.com/in/charan-simha-d-325664239/">Charan Simha </a>





