# Project Orion-X: Seismic Detection Across the Solar System

## Team Members:
- **Sasanka S Kundu**
- **Bhavesh**
- **Suparna**
- **Purvesh**
- **Jonshen**
- **Aryan**

## Event: 2024 NASA Space Apps Challenge
**Challenge Title**: Seismic Detection Across the Solar System  
**Difficulty**: Advanced  
**Group Name**: Orion-X  
**Challenge URL**: [NASA Space Apps Challenge](https://youtu.be/pQfwtutsjFw) ![Seismic Detection Challenge](URL_to_hosted_image) <!-- Replace with actual image URL -->


### Overview
This project is our submission for the 2024 NASA Space Apps Challenge. Our goal is to develop an algorithm that distinguishes seismic signals from noise using real data from the Apollo missions and the Mars InSight Lander. By analyzing planetary seismic data, we aim to filter out unnecessary noise and focus on detecting quakes, which are rare but critical events in planetary research.

Planetary seismology is constrained by the challenge of transmitting large amounts of seismic data across the vast distances between celestial bodies and Earth. The power required to send this data increases significantly with distance, and with most seismic recordings containing noise rather than useful information, it's crucial to develop methods that can identify and transmit only valuable signals.

### Challenge Objectives
Our primary objective is to write a computer program capable of analyzing seismic data and identifying quakes within the noise. We will be working with:
- **Apollo mission data**
- **Mars InSight Lander data**

These seismic records are divided into training and test subsets, allowing us to train the algorithm to distinguish known seismic events and apply the model to uncatalogued data.

### Features
- **Custom Algorithm Development**: Our algorithm will sift through planetary seismic data, identifying useful signals.
- **Machine Learning Integration**: Incorporating machine learning techniques to improve seismic signal detection in noisy environments.
- **Signal Processing**: Applying signal processing techniques like STA/LTA (Short-term average and long-term average ratio) to detect anomalies and identify quakes.
- **Python-Based**: Development using Python and Jupyter Notebooks.

### Tech Stack
- **Programming Language**: Python
- **Machine Learning Libraries**: TensorFlow, Scikit-learn
- **Data Analysis Tools**: Pandas, NumPy, Matplotlib
- **Seismic Data**: Official datasets from Apollo and Mars InSight Lander missions
- **Notebooks**: Jupyter Notebooks for easy data visualization and algorithm development

### Project Scope
The main task is to develop an algorithm that can:
- Analyze continuous seismic data from Apollo missions and Mars InSight.
- Distinguish seismic quakes from noise.
- Handle missing data and glitches, common in planetary datasets.
- Experiment with manual and automated approaches for identifying seismic events.
