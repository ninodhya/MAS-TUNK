# MAS TUNK Dataset README

## Introduction

This GitHub repository hosts the MAS TUNK dataset, an innovative collection of eye-tracking data meticulously gathered for the research paper titled "Meticulous Acquisition System for Tracking User’s Natural Kinetics (MAS TUNK): An Approach in Eye Tracking Dataset Collection for Neural Network Training." Our work has been recognized and accepted for presentation at ETRA 2024 in Glasgow, Scotland, marking a significant contribution to the field of eye tracking.

## Dataset Description

The MAS TUNK dataset pioneers the use of standard laptop webcams for eye-tracking data collection, focusing on capturing natural user interactions. By leveraging everyday technology, we aim to democratize eye-tracking research, making it more accessible and versatile. The dataset is designed to support and enhance neural network training for detailed eye movement analysis and accurate gaze estimation across various applications.

## Data Collection Methodology

Participants engaged with a specially designed interactive game, ensuring user focus and engagement while simultaneously collecting eye-tracking data. This method allows us to gather authentic and natural eye movement data, crucial for developing robust eye-tracking models, particularly for applications in automatic proctoring and security.

## Dataset Attributes

The dataset includes the following key attributes, each serving a specific purpose in eye movement analysis and gaze estimation:

- **Full Frame Face Capture**: High-resolution images capturing the entire face of participants, providing context for eye movement (Frame-Asli).
- **Cropped Eyes**: For general analysis, images of eye regions are provided at dimensions of 150x50 pixels. These images require flipping for correct orientation.
- **Cropped Eyes (Left & Right)**: Detailed crops of each eye, with dimensions of 90x40 pixels, allowing for individual eye movement analysis.
- **Iris Euclidean Distance**: Includes measurements for the left eye, right eye, and both eyes combined, offering insights into gaze direction and eye orientation.
- **Mouse Coordinates**: Serves as labels indicating the user’s gaze point on the screen, essential for validating gaze estimation models.

Data synchronization is achieved through the use of timestamp epochs in file naming, ensuring integrity and sequence accuracy across the dataset.

## Ethical Considerations

All participants in this study have provided their consent for the data collection and subsequent publication of the dataset, adhering to ethical guidelines and ensuring the responsible use of personal data.

## Usage and Applications

The MAS TUNK dataset is an invaluable resource for researchers and practitioners in the fields of machine learning, eye tracking, and human-computer interaction. It offers a diverse set of data points for training and testing gaze estimation models, with potential applications in enhancing automatic proctoring systems, improving user experience design, and beyond.

## Accessing the Dataset

We invite the academic and research community to explore and utilize the MAS TUNK dataset. For access and detailed guidelines on using the dataset, please refer to the subsequent sections of this repository.
