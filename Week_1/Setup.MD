## <img src="https://user-images.githubusercontent.com/78701055/173236524-c7c6df39-3da3-4348-af9c-7c87dbbd774a.png" alt="" width="40"> Setup your Raspi (Headless)  

- Connect your SD card to your laptop  
- Head over to this [site](https://www.raspberrypi.com/software/) and download and install the Raspi Imager
- Run the app and choose OS as Raspberry Pi OS 32 bit and storage as your SD card  
<br>  
<p align="center" style="background-color: rgb(250,250,250)">
  <img src="https://github.com/san2130/Hardware-Track-Specialization-22/blob/main/Week_1/media/pic1.png" alt="" width="50%">
</p>  
<br>  
<br>  

- Now click on the settings option and do as shown
<br>  
<p align="center" style="background-color: rgb(250,250,250)">
  <img src="https://github.com/san2130/Hardware-Track-Specialization-22/blob/main/Week_1/media/pic2.png" alt="" width="50%">
</p>  
<br>  
<br>  
<p align="center" style="background-color: rgb(250,250,250)">
  <img src="https://github.com/san2130/Hardware-Track-Specialization-22/blob/main/Week_1/media/Screenshot%20from%202022-06-28%2023-14-06.png" alt="" width="50%">
</p>  
<br>  
<br>  

- That's it all done, now simply click on write to format your card and install everything (**All your previous data on the SD card will get erased**)  
<br>  
<hr>  

Now just plug in the SD Card into the Raspi SD Card slot, and connect the USB cable to the **USB** Port and not the port marked PWR. If you have a mini HDMI cable connect it as well if you want.  
<br>   
<p align="center" style="background-color: rgb(250,250,250)">
  <img src="https://github.com/san2130/Hardware-Track-Specialization-22/blob/main/Week_1/media/Raspberry-Pi-Zero-Overview.jpg" alt="" width="50%">
</p>  
<br>  
<br>  

If everything is correct as soon as you connect the USB cable you will see a yellow LED blinking, which means the Raspi is booting up.   
Wait for a few minutes for all the background processes to get over and then open up a new terminal in your laptop.  

```
ssh pi@raspberrypi.local  
```  
**Here pi is the username you entered and raspberrypi.local is the hostname.**   
  
Now type in the password and you are in !!!  
<br>  
<p align="center" style="background-color: rgb(250,250,250)">
  <img src="https://github.com/san2130/Hardware-Track-Specialization-22/blob/main/Week_1/media/Screenshot%20from%202022-06-29%2000-32-43.png" alt="" width="50%">
</p>
<p align="center">Congrats you and your date can communicate freely now, go ahead and explore :) </p>  

## <img src="https://user-images.githubusercontent.com/78701055/173236524-c7c6df39-3da3-4348-af9c-7c87dbbd774a.png" alt="" width="40">Fun Tasks  
- Find out her address (IP address plz) (Using ifconfig and nmap)
- Try connecting to her using her IP address (ssh pi@ip_addr) (This is how u should be doing it from now on since remembering hostnames for multiple devices is cumbersome)
- Share some of your property (files) using SCP  
- Give her a permanent address (Static IP Address through your Router) (You won't like to query her new address every time your router is rebooted)
- Create an alias in your bashrc to connect to her with a shorter command
