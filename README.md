# real-time-hand-gesture-recognition
This project addresses a significant communication barrier faced by the deaf and mute community by developing a real-time hand gesture recognition system using computer vision and machine learning techniques. The World Health Organization estimates that 360 million people worldwide have some form of hearing disability, highlighting the urgent need for effective communication tools. 

Objective: To create a system that accurately detects and translates sign language gestures into text, thereby facilitating seamless communication for the deaf and mute population. 

 

#### Phases of the Project: 

- Raw Data Collection: Utilizing the OpenCV library, we capture real-time video frames to gather data on hand gestures. This phase ensures the accumulation of diverse and extensive datasets necessary for model training. 
- Data Extraction: Implementing a two-step process involving a palm detector and a hand landmark model. The palm detector identifies the hand's position, while the hand landmark model pinpoints specific 2D coordinates of the hand. This phase is crucial for extracting high-fidelity hand landmarks required for precise gesture recognition. 
- Model Training: The extracted 2D landmarks are labeled and used to train various machine learning classification models. The performance of these models is evaluated to identify the most accurate and efficient one. This comparative analysis ensures that the best model is selected for real-time application. 
- Real-Time Detection: The chosen model from the training phase is deployed for real-time detection. The system processes live video frames, transforming them through the same data extraction methods before feeding them into the trained model for immediate gesture translation. 

 

#### Significance: 

- Innovation: This project employs advanced computer vision and machine learning techniques to develop a robust and real-time gesture recognition system. 
- Social Impact: By bridging the communication gap for the deaf and mute community, this system promotes inclusivity and accessibility. 
- Technological Advancement: The project leverages OpenCV and state-of-the-art machine learning models, contributing to the growing field of assistive technologies. 
