 **AI Face HeartRate BPM Detector Using (Machine Learning OpenCV)**

Monitoring heart rate in real-time using a webcam. This is based on an algorithm called Eulerian Video Magnification, which enables the visualization of color changes as blood flows in and out of the head. It is capable of detecting pulses and calculating the heart rate in beats per minute (BPM) . This method performs well in real-time.



                                       ┌───────────────────┐
                                       │       Input       │
                                       │   Webcam Video    │
                                       └───────────────────┘
                                                │
                                                v
                                       ┌───────────────────┐
                                       │   Preprocessing   │
                                       │   Face Region     │
                                       │    Detection      │
                                       └───────────────────┘
                                                │
                                                v
                                       ┌───────────────────┐
                                       │    Spatial        │
                                       │  Decomposition    │
                                       └───────────────────┘
                                                │
                                                v
                                       ┌───────────────────┐
                                       │    Temporal       │
                                       │   Filtering       │
                                       └───────────────────┘
                                                │
                                                v
                                       ┌───────────────────┐
                                       │   Magnification   │
                                       └───────────────────┘
                                                │
                                                v
                                       ┌───────────────────┐
                                       │    Measurement    │
                                       │   Heart Rate      │
                                       │   Estimation      │
                                       └───────────────────┘
                                                │
                                                v
                                       ┌───────────────────┐
                                       │    Visualize      │
                                       │    Results        │
                                       │   CVZone LivePlot │
                                       └───────────────────┘

**🧠 Installation & Setup Guide**

**Step 1:** Download the source code from this repository and open the folder in PyCharm.

**Step 2:** Open the terminal, **copy all pip,** and install the required dependencies by running the following commands:

            pip install opencv-python
            pip install numpy
            pip install cvzone
            pip install mediapipe



            
**Step 3:** Wait until all installations are completed successfully. Then, run the program and see your result!

**Output**

<img width="1272" height="477" alt="image" src="https://github.com/user-attachments/assets/a57deee2-73e4-4ae5-be15-6843059391e8" />


<img width="1277" height="474" alt="image" src="https://github.com/user-attachments/assets/77b83305-682d-422a-96fb-07bdedd838e9" />




**📬 Contact**

If you face any problems, feel free to reach out:


Email: arafat.bd.hosen@gmail.com

**WhatsApp: +8801744805068**

**WeChat: arafat_cn**

**QQ: 3522584423**








