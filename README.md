# Squat Perfect: A Computer Vision Application

Welcome to **Squat Perfect**, a computer vision application designed to count squats and provide real-time feedback to users. My ultimate goal was to help users perfect their squat form and technique.

## Note

Please note that some of the values used in this process, such as the approximated NECK and MID_HIP landmarks or LEFT & RIGHT SHOULDERS, are based on estimations and might not be perfectly accurate. They are derived from other landmarks provided by the MediaPipe Pose model and are used for the purpose of calculating the spine angle. The accuracy of these values, and consequently the spine/pose angle, can be influenced by various factors such as the precision of the pose estimation model and the quality of the input image (and I didn't had much videos for estimating these). Therefore, while this method can provide a general guidance for posture correction, the results should be interpreted with consideration of these potential inaccuracies.

## Overview

**Squat Perfect** is not just a squat counter. It's a personal fitness assistant that encourages users to improve their squats by going deeper. While it's possible to perform squats until your thighs are parallel to the floor, **Squat Perfect** motivates users to go even deeper for a more effective workout.

## Getting Started

Here are the steps to set up **Squat Perfect** on your local machine:

### Prerequisites

Ensure you have Python 3.x installed on your machine. You can download it from the official Python website.

### Installation

1. **Clone the repository**
    ```
    git clone https://github.com/yourusername/squat-perfect.git
    cd squat-perfect
    ```

2. **Create a virtual environment**
    ```
    python3 -m venv env
    ```

3. **Activate the virtual environment**
    - On Windows, run: `env\Scripts\activate`
    - On Unix or MacOS, run: `source env/bin/activate`

4. **Install the required packages**
    ```
    pip install -r requirements.txt
    ```

### Running the Application

After you've set up your environment and installed the required packages, you can run the application.


Enjoy your workout with **Squat Perfect**!


