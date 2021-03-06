## Quickly start
  - Run the below command to install the PyQt5 module
  ```Bash
  sudo apt-get install python-pyqt5
  ```
  - Run the below command to install the cv2 module
  ```Bash
  sudo apt-get install python-opencv
  ```

## Configuration
- Enable the camera 

- Configure the i2c1 

![Alt text](https://github.com/ArduCAM/RaspberryPi/blob/master/data/cfg_i2c1_1.png)

![Alt text](https://github.com/ArduCAM/RaspberryPi/blob/master/data/cfg_i2c1_2.png)

- Run the below command to init and check the camera
```Bash
sudo ./init_camera.sh
```
-If anything is normal, you will see below message
![Alt text](https://github.com/ArduCAM/RaspberryPi/blob/master/data/check_msg.png)

- Run the below command to start the demo
```Bash
sudo python 4cam_cv2.py
```
- Operation video demo link
 https://www.youtube.com/watch?v=HxHKQS1weGc&feature=youtu.be
  
