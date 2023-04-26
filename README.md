# Using-Computer-Vision-For-Physical-Security

Utilizing Computer Vision for Physical Security. 
Machine Learning and How it can be used in cybersecurity. 
Using python to create a software to detect objects in a physical security setting with PyTorch, YOLOv5, OpenCV and more. 


The first model will detect Backpacks, Laptops, and a USB'
  - This model will append all detection to a log file with time stamps. 
  - As well as it will send alerts when objects are detected


The second model will detect whether computer ports are open or if a USB is detected.
  - If a USB is connected and the objects switch from Ports_Open to USB_Detected a log will be created with a timestamp
  - If a USB is disconnected and the objects switch from USB_Detected to Ports_Open a log will be created with a timestamp. 

Both of these models were aimed at creating software for physical security that was both cost effective and efficient. 
Using Computer Vision we no longer have to manually view security cameras, rather we we will be notified when a threat is detected. 



