# Drowsiness Detection System

## Project Overview
This project is designed to detect drowsiness in drivers, specifically those driving trucks or cars. The system uses computer vision to monitor the driver's eyes. If the system detects that the driver's eyes are closed for an extended period, it triggers an alarm to alert the driver and prevent accidents caused by drowsiness.

The primary goal of this project is to demonstrate a real-time application of drowsiness detection for academic purposes.

## System Requirements

- **Anaconda Environment** with Python 3.9 version
- **Required Libraries**: All required Python libraries can be installed via the `requirements.txt` file.

## Installation Instructions

1. **Create an Anaconda environment** (if not already created):
    ```bash
    conda create --name drowsiness-detection python=3.9
    ```

2. **Activate the environment**:
    ```bash
    conda activate drowsiness-detection
    ```

3. **Install the required dependencies** using pip:
    ```bash
    pip install -r requirements.txt
    ```

4. After installation, you can run the system in your preferred IDE or directly from the command line.

## Dataset Information

The dataset used in this project is the **MRL Drowsiness Detection Dataset**, which is available on Kaggle. It contains images of faces with labeled eye states (open or closed), allowing the system to learn how to detect drowsiness based on eye activity.

- **Dataset source**: [MRL Drowsiness Detection Dataset on Kaggle](https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset)

## Credits

- **Dataset**: The dataset used for training the model is the [MRL Drowsiness Detection Dataset](https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset) by Prasad V Patil.
- This project was built for academic purposes to demonstrate the use of machine learning in real-time drowsiness detection.

## License

This project is for academic purposes only. Feel free to use the code and modify it for non-commercial purposes.
