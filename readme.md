# Raspberry Pi Smart Doorbell
## By Dominique Denert & Gabriel Maravilla

### Motivation:
Though there are many smart doorbells on the market, when the doorbell is rung, often there isn't a clear notification of who or what is at the door. We want to create a smart doorbell that's able to distinguish people using face detection, whether that be a family member, friend, or neighbor.

### Design Goals:
Using a Raspberry Pi & its camera module, we will design a smart doorbell that can detect people and classify whether they are recognized or unknown.

### Deliverables:
* Deployed ML model on Raspberry Pi
* Lightweight face detection utilizing TensorFlow Lite
* Capture image & classify upon arrival at door
* Send notification upon arrival

### System Blocks:
* Hardware:
<img width="342" height="364" alt="image" src="https://github.com/user-attachments/assets/2f35e3e7-5eec-4939-8e9e-9eead03df148" />
* Software:
Data obtained from camera -> Program running on Raspberry Pi <-> TensorFlow Lite model

### Hardware Requirements:
* Capture image and store data through Raspberry Pi
* Low latency and power consumption

### Software Requirements:
* Capture image with Raspberry Pi and camera module
* Classify image based on TensorFlow Lite model

### Team Member Responsibilities:
Gabriel Maravilla:
* Software:

Dominique Denert:
* Hardware: Responsible for configuring hardware physically as well as handle camera module interaction and and writing simple system code.

### Project Timeline:
Weeks 1-3 - Idea finalized, research and outline system details
Weeks 3-6 - Obtain and configure hardware components, implement TensorFlow Lite model
Weeks 6-9 - Bring system together with system interaction and ML model
Week 10 - Final touches / Presentation

### References:
* [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861)
