# driver_Drowsy_detection
Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving. To validate the proposed approach tests were conducted by using a variety of different images, such as the driver's face covered with a mask or glasses. 

The proposed approach uses 
Eye aspect ratio (EAR)   to detect driver drowsiness in real-time. This is useful in situations when the drivers are used to the strenuous workload and drive continuously for long distances.

 Methodology:
 The face is detected from a video stream using facial
landmark detection and extract the eye regions. These facial landmarks are then used to compute the EAR and are returned back to the driver. In our context, the EAR value received at the application’s end would be compared with the threshold value taken as 0.25 If the EAR value is less than the threshold value, then this would indicate a state of fatigue. In case of Drowsiness, the driver and the passengers would be alerted by an alarm.

 landmark-68 detection model:
 works  by extracting the key of facial features  and deals with eye closure detection, yawn detection. 
This model uses computer vision to observe the face, either using a built-in camera. 
![68_facial landmarks](https://github.com/fatma-elshall/driver_Drowsy_detection/assets/90958050/1febe16e-47dc-42a6-915f-375a7dfc93d7)

