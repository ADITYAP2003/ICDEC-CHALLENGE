# ICDEC-CHALLENGE
ICDEC CHALLENGE - TEAM DETECTORS
# Approach :
1. Video processing and Emergency Vehicles Detection using AI Utilises AI algorithms to identify vehicles. Trained with diverse datasets comprising images of various types of  vehicle for accurate identification. Upon detection, the system proceeds to the next phase.
   
1.1 Data Collection Before an AI system can accurately identify vehicles, a significant amount of data must be collected. This data may include images, videos, or audio recordings of vehicles captured from various sources, such as traffic cameras, emergency dispatch centres, or publicly available datasets.

1.2 Data Processing Once the data is collected, it must be pre-processed to remove noise, normalize the features, and enhance the quality of the input. This step is crucial for improving the accuracy and reliability of the AI model.

1.3 AI Model Training In this phase, the collected and pre-processed data is used to train an AI model. The AI model, typically based on deep learning techniques such as Convolutional Neural Networks (CNNs), is trained to recognize and classify vehicles based on their unique visual and auditory features.

1.4 Real Time Detection After the AI model is trained, it can be used to perform real-time detection of vehicles in live video streams. The detection process involves feeding the video frames into the AI model, which then analyses the frames and identifies whether an emergency vehicle is present or not.

1.5 Integration with Traffic Control Signals To effectively control traffic and facilitate the smooth passage of vehicles, the AI-based vehicle detection system can be integrated with existing traffic control systems. This integration allows traffic signals to automatically adjust to prioritize the passage of emergency vehicles, ensuring swift and uninterrupted movement.

# Tech Stack :
1. CCTV Camera: In this system the CCTV camera is installed at the intersection where traffic occurs and our system is going to be deployed. Using these CCTV cameras we are going to collect the data, capture videos and this data will be used by Artificial Intelligence for the further process. CCTV cameras must be there at the intersection to collect the real time traffic data and videos for the processing and take the decisions accordingly.
   
2. Artificial Intelligence (AI): Artificial Intelligence (AI), specifically utilizing the YOLOv8 model, is employed for the efficient detection of vehicles amidst traffic scenarios. This choice is made due to the superior efficiency of Open-CV over alternative technologies such as Deep Learning, Machine Learning, and IoT devices.
   
3. RasperryPi: Raspberry Pi is a credit card-sized, low-cost, single-board computer developed by the Raspberry Pi Foundation in the UK. Despite its small size and low cost, Raspberry Pi is capable of performing various tasks such as word processing, gaming, and internet browsing. In our project it is used for signal optimization after detecting vehicles. With its versatility and affordability, Raspberry Pi has gained a large community of enthusiasts and developers worldwide.
   
4. Server: The server serves as the central repository for storing and managing the data and information transmitted by the AI. Its pivotal role lies in collecting this data, as it forms the basis for implementing future system improvements. This data is indispensable for tracking the progress and assessing the impact of our system, particularly in facilitating the timely arrival of vehicles at their destinations.

# Basic Workflow :
1. Capturing Video through CCTV
2. Real time analysis / processing of video
3. Check weather condition
4. Find out the vehicles detection
5. cross verify the number of vehicles detected
6. Save the data in servers
7. Repeat it again
