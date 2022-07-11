## Installation

We recommend you to get familiar with python code to access raspberry pie camera before moving ahead. 

### STEP 1: Download host.zip file manually or run this command:
```bash
git fetch git://github.com/Robotics-Club-IIT-BHU/Hardware-Track-Specialization-22/Week_2/flask/host.zip
```


### STEP 2: Use SCP Command to Transfer Files to Raspberry Pie
```bash
scp host.zip [user@]DEST_HOST:]/[path to directory]
```


### STEP 3: Unzip the zip file.
```bash
unzip host.zip
```

### STEP 3: Move inside the directory.
```bash
cd host
```

### STEP 5: Install the requirements.
```bash
pip install flask
pip install numpy==1.19.5
pip install opencv-python  
```

### STEP 6: Change the host name to the pi's ip address and cv2.VideoCapture() with raspi camera api.  

### STEP 7: Run host.py inside your virtual environment
```bash
python host.py
```

