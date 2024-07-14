# Vehicle-Movement-Analysis-in-College-Campus

## Introduction
This repository hosts a machine learning model built with YOLOv5 for detecting vehicles and their number plates in images and video streams. The model achieves high accuracy and is adaptable for various domains including traffic management, security systems, and more.

## Features
Vehicle Detection: Accurately identifies cars and other vehicles in images and video.  
Number Plate Recognition: Extracts and reads number plates from detected vehicles.  
High Accuracy: Achieves robust performance in detecting vehicles and recognizing number plates.  
Versatility: Suitable for deployment across different applications and environments.  
Automatic Record Keeping: The identified number plates are stored in a csv file.  

## Installations
Ensure you have the following Python packages installed:

numpy  
pandas  
matplotlib  
opencv-python  
jupyter  
labelImg  
You can install these packages using pip  

## Usage
The model can be deployed in various real-life scenarios:  

Traffic Management: Monitor and analyze vehicle movements in real-time.  
Security Systems: Enhance surveillance capabilities by detecting vehicles and identifying number plates.  
Smart Parking Solutions: Automate entry and exit management in parking facilities.  

## Dataset
- **Stanford Cars Dataset:** [Link to dataset](https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset)
- **Automatic Number Plate Recognition Dataset:** [Link to dataset](https://www.kaggle.com/code/aslanahmedov/automatic-number-plate-recognition)

## Model Training (YOLOv5)
The project makes use of yoloV5 model.   
YOLOv5 is a state-of-the-art object detection model known for its speed and accuracy. It primarily utilizes a convolutional neural network (CNN) as its underlying algorithm. It is trained using stochastic gradient descent (SGD) or adaptive optimization algorithms like Adam, to minimize the combined loss function.

## Step by Step procedure of environment setup  

### Step 1: Set Up the Virtual Environment  
To ensure a clean and isolated development environment, we use virtualenv. Follow these steps to create and activate a virtual environment:  
**1.1. Install virtualenv:** If virtualenv is not already installed, use the following command:  
bash  
pip install virtualenv  
**1.2. Navigate to your project directory:** Open a terminal or command prompt and navigate to your project directory:  
bash  
cd path/to/your/project  
**1.3. Create a virtual environment:** Create a virtual environment named myenv (or any name of your choice):  
bash  
virtualenv myenv  
**1.4. Activate the virtual environment:** Activate the virtual environment using the appropriate command for your operating system:  
•	On Windows:  
bash  
myenv\Scripts\activate  
•	On macOS/Linux:  
bash   
source myenv/bin/activate  
**1.5. Install dependencies:** With the virtual environment activated, install the necessary dependencies using pip:  
bash  
pip install package_name  
To deactivate the virtual environment when done, simply use:  
bash  
deactivate  
### Step 2: Clone the Repository 
Clone the project repository that contains the YOLOv5 model and associated files:  
bash   
git clone ”https://github.com/ultralytics/yolov5.git”  
### Step 3: Install Dependencies  
Start the virtual environment created in Step 1 and install all required dependencies. These dependencies can be installed individually using pip, or you can use a requirements.txt file if provided:  
bash   
pip install -r requirements.txt   
If installing individually, use the following commands:   
bash  
pip install python    
pip install numpy   
pip install pandas    
pip install matplotlib     
pip install opencv-python    
pip install jupyter    
pip install pytesseract    
### Step 4: Open Jupyter Notebook  
Once all dependencies are installed, open Jupyter Notebook in the same terminal:  
bash  
jupyter notebook  
This command will launch Jupyter Notebook in your default web browser.  
### Step 5: Run the Notebook  
Navigate to the relevant Jupyter Notebook file within the repository and execute all the code blocks sequentially. This will initialize the YOLOv5 model, load the datasets, and run the vehicle and number plate detection algorithms.  
## Project-video
-  [project-video](https://github.com/R7A2J8A7N/Vehicle-Movement-Analysis-in-college-campus/tree/main/projet-video)
## Project-documentation
-  [project-Documentation](https://github.com/R7A2J8A7N/Vehicle-Movement-Analysis-in-college-campus/tree/main/project-documentation)
