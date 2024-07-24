# Football Analytics with Deep Learning and Computer Vision

**Project Objective:** Develop a web application that automates football analysis and provides valuable insights to aid decision-making.

**Current Progress:** Building a Streamlit web application focused on football object detection and tactical map visualization.

## Installation & Usage Instructions

Follow these steps to set up and run the application:

1. Clone the repository using the command:  `git clone https://github.com/AMx14/Football-Analytics `
2. Install the necessary libraries specified in the `requirement.txt` file. You can create the conda environment I use by executing: `conda env create -f environment.yml`
3. Ensure that the PyTorch installation is compatible with your system.
3. Launch the application with the following command: `streamlit run main.py`
    

## Features

- Detects players, referees, and the ball.
- Identifies players' teams based on predetermined team colors.
- Generates a tactical map representation.
- Monitors ball movements.

## Application Workflow

The process of handling the input video and the various functionalities is depicted in the workflow diagram below.

![workflow diagram](https://github.com/Hmzbo/Football-Analytics-with-Deep-Learning-and-Computer-Vision/assets/62519374/8a934460-5f7f-4170-a2b2-d89c77fce2fe)