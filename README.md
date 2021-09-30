### Smart Attendance System using Face recognition and RFID

(For storing the output in database install SQL-Lite Studio)

```
1.Execute main file train.py in python idle.

2.A GUI(interface) will open up
```
![Main Screen](Main.png)
```
(i) Enter the id

(ii) Enter the name

-click on Take images button (images captured will be stored in the folder called "Training image").

Note:It will capture upto 30 images

3.Now click on Train button -this will train all the images captured and store the data in Trainner.yml .

Note:Now,you don’t need the images stored in "TrainingImage" folder anymore after you have trained 

("The images in TrainingImage folder will be automatically deleted).

4.Click on Track button,

Place the rfid tag near rfid reader,Now a window called Recognizer will pop up and start capturing your 
image

Note:
(i).The recognizer will pop/open only if you scan the RFID tag. 
(ii).As soon as it identifies your face,the window will close automatically and attendance will be updated.
(iiI).If it dosent recognise then the window/program will end automatically within 10 seconds.
(iv).To change the window closing time change the value of z in track function,presuming with stopwatch.

5.Now the output will be stored in the Database (to view the output in database click refresh)

Note:The second time you want to take attendance you dont have to give the input in input field of gui

just click on track button,it will track and update the database.

6.Output will be displayed in GUI and also in LCD.
```
![Output on database](output1.png)

![Output on LCD](output2.png)
```

7.The future development of the project is to make the PI run automatically.
```

### Smart-Attendance-System-using-Face-Recognition-and-RFID
