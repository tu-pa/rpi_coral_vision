# rpi_coral_vision
Raspberry Pi 3+ with Coral TPU for Embedded System Inferencing 

Pose Example:
![](pose_example.gif)


Pre-configuration:
- HW: 
  - Raspberry Pi 3+: https://www.raspberrypi.org/products/raspberry-pi-3-model-b/
  - Coral Edge TPU USB: https://coral.ai/docs/accelerator/datasheet/
  - Raspberry Pi Camera: https://www.newegg.com/p/023-019V-00004?item=9SIA4W27NA6922&nm_mc=knc-googleadwords&cm_mmc=knc-googleadwords-_-toys%20-%20electronics%20for%20kids-_-alion%20fortune%20hk%20limited-_-9SIA4W27NA6922&source=region
    - Cheap version that works with RPi 3. 
  
- SW: 
  - Setup Raspberry Pi with Wi-Fi access to the internet
    - Used desktop UI Wi-Fi Icon
  - (If using RPi Camera) Enable Raspberry Pi Camera
    - <code>sudo raspi-config</code>
    - Interfacing Options > Camera > Enable
  - Fresh image of RPi Debian with Raspberry Pi Imager: https://www.raspberrypi.org/downloads/
    - Desktop Image 
  - Follow getting started guide: https://coral.ai/docs/accelerator/get-started/
    - Linux steps on the Raspberry Pi
      - Verify setup with results from this test: https://coral.ai/docs/accelerator/get-started/#3-run-a-model-using-the-tensorflow-lite-api
  - Clone Pose Net GIT: https://github.com/google-coral/project-posenet
     - Run project-posenet example for Raspberry Pi Camera
   

