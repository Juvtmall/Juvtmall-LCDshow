LCD driver for the Raspberry PI Installation<br>
====================================================
   This is Juvtmall, if you have any troble in our product, please contact<br> 
   our support: support@juvtmall.com<br> 
   our website is: www.juvtmall.com<br> 
   Thank you<br> 

1.)Step1, Install Raspbian official mirror <br>
====================================================
  a)Download Raspbian official mirror:<br>
  https://www.raspberrypi.org/downloads/<br>
  b)Use“SDFormatter.exe”to Format your TF Card<br>
  c)Use“Win32DiskImager.exe” Burning mirror to TF Card<br>
     
2.) Step2, Clone my repo onto your pi<br>
====================================================
Use SSH to connect the raspberry pi, <br>
And Ensure that the raspberry pi is connected to the Internet before executing the following commands:
-----------------------------------------------------------------------------------------------------

```sudo rm -rf LCD-show```<br>
```git clone https://github.com/goodtft/LCD-show.git```<br>
```chmod -R 755 LCD-show```<br>
```cd LCD-show/```<br>
  
3.)Step3, According to your LCD's type, excute:
====================================================
In case of 2.8" LCD<br>
  ```sudo ./LCD28-show```<br><br>
In case of 3.2" LCD<br>
  ```sudo ./LCD32-show```<br><br>
In case of 3.5" GPIO Display<br>
  ```sudo ./LCD35-show```<br><br>
In case of 3.5" HDMI Display-MPI3508<br>
  ```sudo ./MPI3508_480_320-show```<br>
  or<br>
  ```sudo ./MPI3508_600_400-show```<br>
  or<br>
  ```sudo ./MPI3508_720_480-show```<br>
  or<br>
  ```sudo ./MPI3508_810_540-show```<br>
  or<br>
  ```sudo ./MPI3508_960_640-show```<br><br>
In case of 3.5" DPI Display-MPI3510<br>
  ```sudo ./MPI3510-show```<br><br>
  
In case of 3.97" LCD<br>
  ```sudo ./LCD397-show```<br><br>
In case of 4.3" LCD<br>
  ```sudo ./LCD43-show```<br><br>
In case of 5" LCD<br>
  ```sudo ./LCD5-show```<br><br>
In case of 7inch(B)-800X480 RPI LCD<br>
  ```sudo ./LCD7B-show```<br><br>
In case of 7inch(C)-1024X600 RPI LCD<br>
  ```sudo ./LCD7C-show```<br><br>
If you need to switch back to the traditional HDMI display<br>
  ```sudo ./LCD-hdmi```<br><br>

Wait a few minutes,the system will restart automaticall , enjoy with your LCD.
-------------------------------------------------------------------------------
<br><br>


