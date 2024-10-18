**Automated Detection of Personal Protective Equipment**
**Introduction**

Ensuring the safety of workers in various environments, such as construction sites, factories, and laboratories, is essential. Personal Protective Equipment (PPE) such as helmets, gloves, vests, and boots are critical in minimizing the risk of injury. However, manual monitoring for compliance with PPE requirements is labor-intensive and prone to human error. This project aims to develop a deep learning-based system to automatically detect the presence of PPE in images from different environments where PPE is necessary.

**Motivation**
The motivation for this project stems from the need to improve safety compliance and reduce the manual effort required to monitor PPE usage. By leveraging deep learning, we aim to create a reliable and efficient solution that can be implemented in various settings to ensure the safety of workers.

**Objectives**
* **Develop a PPE Detection Model:** Train a Faster R-CNN  model to
accurately detect Personal Protective Equipment (PPE) such as helmets, gloves, vests, and boots in images from various environments.

* **Address the Regression Problem:** Implement regression techniques to evaluate the degree of compliance with PPE requirements in the detected images.

**The Dataset**
The dataset used for this project is sourced from the Roboflow site, an open-source collection of images designed to facilitate deep learning projects focused on the detection of Personal Protective Equipment (PPE). This dataset contains a total of 1064 image-label pairs, specifically curated to aid in the accurate identification of various PPE items and related objects in different environments.

**Dataset Details**
The images in this dataset are labeled and categorized into the following classes:

* Boots
* Gloves
* Helmet
* Helmet on
* No boots
* No glove
* No helmet
* No vest
* Person
* Vest

**Data Split**
The dataset is divided into three primary subsets:

* Training Set: 743 images
* Testing Set: 106 images
* Validation Set: 215 images

This segmentation promotes a structured and methodical organization of the data.

In each folder there are two subfolders:
* **images:** Provided in JPG format with a resolution of 640 × 640 pixels.
* **labels:** Ppe are annotated in Pascal VOC format.



