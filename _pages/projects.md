---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Subreddit Classification and Sentiment Analysis
**Tech Stack:** Python, TensorFlow, LLM <br>
**Dataset:**  Stanford Cars Dataset, sourced from Kaggle
- Built a full NLP pipeline to classify Climate Science vs Climate Skeptics subreddit posts and performed sentiment analysis using deep learning and LLMs.
- Achieved 99.12% accuracy using Random Forest, outperforming traditional ML models (SVM: 85.12%) and LLMs like BERT (90.37%), RoBERTa (89.93%), and XLNet (88.84%)

## Car Make and Model Detection and Classification
**Tech Stack:** Python, Scikit-learn <br>
**Dataset:** Public opinion data on climate change from Reddit, sourced from Kaggle
- Utilized the Stanford Cars Dataset (16,185 images, 196 classes) with CNNs and Transfer Learning models (VGG16, Xception, ResNet50), applying feature extraction, data augmentation, and fine-tuning to support real-world traffic safety applications
- Achieved 94.60% accuracy using Xception with K-Fold Cross-Validation, outperforming VGG16 (84.83%) by reducing overfitting <br>

**GitHub:** [Project Link](https://github.com/ummeasalma/suicide-detection)

## Secure Data Sharing System for Vehicular Network
**Tech Stack:** Contiki, C++, X.509 <br>

This project proposes a design for a secure data-sharing framework in connected and autonomous vehicular networks. It focuses on ensuring authentication, confidentiality, and data integrity during cooperative perception, where vehicles and infrastructure nodes exchange sensory data to improve object detection, localization, and mapping. The work introduces a lightweight certificate system based on elliptic curve cryptography to establish secure communication channels between vehicles and infrastructure nodes, enhancing the overall safety and reliability of vehicular networks.

## Autonomous Control of a Fleet of Vehicles
**Tech Stack:** Python, MQTT Broker, Raspberry Pi <br>

Designed and implemented a distributed architecture where each vehicle in the fleet is equipped with a Raspberry Pi Pico W microcontroller, enabling real-time data exchange and coordination by utilizing the MQTT protocol. <br>

**GitHub:** [Project Link](https://github.com/mrp17010/cse4709-project)
