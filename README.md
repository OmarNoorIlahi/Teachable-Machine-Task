# Teachable-Machine-Task

# Table of Contents

- [Overview](#overview)
- [Methods](#methods)
  - [Teachable Machine](#teachable-machine)
  - [Python](#python)
- [Output](#output)

---

## Overview

This is task one under the AI & Robotics Operating Systems track, submitted to Smart Methods Company for 2025 Summer Internship. This task presents a trained AI model developed with Python programming. The model classifies data into its appropriate category. For instance, the model accepts images of different football players and predicts their classes according to their nationalities with a confidence level.

---

## Methods

Two tools are used in order to perform the task: Teachable Machine and Python. Each of these tools performs separate functions, but also, they are complementary to each other.

### Teachable Machine

Teachable Machine was used to build an image recognition model. The model consists of four classes: France, England, Germany, Spain, representing the nationalities of the players. Each category includes 10 pictures of different football players to improve the model’s accuracy. Then, the model was generated into TensorFlow Keras Format.

>> ![Teachable Machine Model](Teachable%20Machine%20Model.png)
<p align="center"><em>Figure 1: Teachable Machine Model</em></p>

> **Note:** The Keras code is attached as a separate file in the repository.

### Python

In Python, the model code is loaded and tested. The script accepts an input image to predict its category based on nationality. The code was further modified so that the output will also display the input image of the player alongside its class. To run the program, the input image must be uploaded to the working directory first. Then, copy its path in the code.

> **Note:** The original & modified codes are attached as separate files in the repository.

---

## Output

Four testing images, each depicting a different football player from four different countries, are used as inputs. The program displays each player’s image along with the confidence score of the prediction.

> ![Test Results](Test%20Results.png)
<p align="center"><em>Figure 2: Test Results</em></p>

As shown in Figure 2, the model figured out the nationality of each player from different countries. In fact, the predictions are true despite the variations in the confidence scores. However, the input images contain the logos of the national teams, which may have aided the model in classification. Therefore, it is recommended to use face images without any nationality hints for future work.

> **Note:** All the pictures & files used in the task are attached in the repository.
