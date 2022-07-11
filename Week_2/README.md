<h1 align="center"> 
    
    Welcome To Week 2
</h1>
Hello folks, so how is your date going on? We hope that you told your partner how much you like it. 
<br><br>
<p align="center"><img src="media/meme.jpg" alt=""/></p>
<br><br>
<b>We know you are too shy to speak, so why don't you propose in sign language?</b>

## Prerequisites
- **Python:** We hope that all of you are familiar with python, if not do checkout this <a href="https://www.youtube.com/watch?v=rfscVS0vtbw">video</a>.
- **Camera Integration:** Next step is to do camera integration with raspi, here is the &nbsp; <a href="https://www.youtube.com/watch?v=VzYGDq0D1mw">tutorial</a> &nbsp; and &nbsp; <a href="https://pyimagesearch.com/2015/03/30/accessing-the-raspberry-pi-camera-with-opencv-and-python/">videocapture</a>

## Your Tasks
<details>
  <summary><b>Task1</b></summary>
  <p>
    <br>
    First part of a proposal is to make a good eye contact with your date. So, this task is to create a face detector for your raspi which counts the number of faces. This code will run entirely on the <b>raspi.</b>  <b>(Hint: use Dlib)</b> 
    <br>
    <p align="center"><img src="media/counter.jpg" alt="" ></p>
    <br>
    <b>NOTE: You don't have to recognise the face, just detect all, count them and display the count on the video.</b>
  </p>
 </details>
<details>
  <summary><b>Task2</b></summary>
    <p>
    <br>
Now, for the main part of proposal, all you need to do is to take input from the camera module by showing it hand signs and broadcast on your pi's ip server using Python Flask.
The code for the same is given <a href="host.zip">here</a>. But it is for general OpenCV, you may need to modify its <b>video capture</b> part.
<br><br>
        Write a python code on your <b>laptop</b> to access this image from the url and decode your message. 
<br><br>
Show three different hand signs and map them to words <b>I</b>, <b>LIKE</b> and <b>YOU</b> , ofcourse in this given order. <br>
Your message will begin with completely stretched hand position (:raised_hand_with_fingers_splayed: sign) and end with it only. <b>(Hint: use mediapipe)</b> 

<p>
  <img src="media/1.png" alt="" width="45%"/>
  <img src="media/2.png" alt="" width="45%"/>
</p>

All signs between them will be your message and again its obvious that you cannot use this sign for other purposes.
<br><br>
  </p>
 </details>

## Your submissions
- **For Task 1**, you need to record a short video inside your **raspi** using opencv videowriter, detecting all the visible faces as shown in the Task 1 problem statement and also display the current total count on the video.
- **For Task 2**, you need to record a short video inside your **laptop** that starts and end with :raised_hand_with_fingers_splayed: sign. Your current meaning of sign should be visible on video as you can see in images of the Task 2 problem statement.
<br> <br>
Try to avoid recording high resolution and long videos in raspi to prevent memory card from getting full. <br>
You will receive submission link at the end of this week. Till then...
<br> <br>
<img src="media/enjoy.jpg" alt=""/>
