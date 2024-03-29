# Autolabel

# Open Dictionary Autolabel
![UIaa](https://github.com/Ziad-Algrafi/Autolabel/assets/117011801/39be3604-89cb-46a6-9ea4-643b36d7397e)



Autolabel is a project designed to simplify the auto-labeling of classes in images using the YOLO model. The provided GUI allows users to choose between a custom YOLO model or Open Dictionary model.


## Autolabel.py and OpenAutolabel.py

`Autolabel.py` is the main script of this project, featuring a graphical user interface (GUI) for easy interaction. The script leverages the Ultralytics library for object detection.
`OpenAutolabel.py` is an open dictionary script, featuring a graphical user interface (GUI) for easy interaction. The script leverages the Ultralytics library for classifing objects to detect using YOLO WORLD.

### Usage

1. Download the repository:

 https://github.com/ZiadAlgrafi/Autolabel-yolov8.git
 
 
### Run from Command Line

To run the Autolabel script from the command line:

2. . Navigate to the project directory and install your preferred requirements MANUALLY from the command prompt CMD. Note choose your desired file and minimum or recommened requirements:

   
    cd path\to\Autolabel\Requirements
    

3. Activate the Python virtual environment if already done:

   
    . venv/bin/activate      # On Linux
    .\myenv\Scripts\activate # On Windows
  


4. Navigate to the Autolabel script and choose the script you want to Run using cmd:

### Open Dictionary Autolabel

1. cd /home/user/Documents/Autolabel/OpenAutolabel.py
2. python OpenAutolabel.py


### Choose open dictionary model to download

- [Small (52.2 accuracy)](https://github.com/ultralytics/assets/releases/download/v8.1.0/yolov8s-worldv2.pt)
- [Medium (58.4 accuracy)](https://github.com/ultralytics/assets/releases/download/v8.1.0/yolov8m-worldv2.pt)
- [LARGE (62.8 accuracy)](https://github.com/ultralytics/assets/releases/download/v8.1.0/yolov8x-worldv2.pt)

     

### GUI Features

Select YOLO-WORLD MODEL>> if you have custom model and you prefer your images to be labelled as how you have configured your model enter the path to your custom model. If you dont have custom model you can choose the open Dictionary model from ultralytics library i have included it in requirements folder

Select Images Folder>> select the folder that contains your desired images to be labelled. Note choose the root path for the folder, and Ensure that your images are in one of the following formats: jpg, jpeg, png, or jfif. Also based on the names of your images your labels will correspond to that.

Select Output Directory>> select where the images and labels results will be outputed. 

Enter Classes to detect>> enter the names of the classes you want to detect. Separate each class name with a comma. Do not use a comma after the last class.

Select Device>> based on the your device is it GPU or CPU. If GPU choose 0. If CPU choose CPU

Output Format>> choose between YOLO or COCO dataset format

Start>> after adding paths and selecting device you can run the program using Run Code button. Wait few seconds based on your device and check the Log Run.

Log Run: will updates the logs of the detction of the model after it finish it will output Results saved in txt files (your directory)




