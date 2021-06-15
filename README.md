# Social-distance-detection

#### Github usually doesn't support files larger than 25 Mb.You have download yolov3.weights & move it to yolo-coco folder.

# For CPU:

## To run this code in your terminal:
* ***Open your terminal**
* ***Change directory to where you have downloaded this code***
* ***Install python3 if you have not, if installed already then it's ok!***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***to activate your environment!***
* **Write**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like opencv,numpy,scipy etc.***
* **Run the command** `time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1
` ***to run your social distance detection project***

#### After you run the last line of command,a window eill pop up and after execution of the file a `output.avi` file will be showing up in your directory like this:
![Output avi gif](https://github.com/abd-shoumik/Social-distance-detection/blob/master/social%20distance%20detection.gif)

