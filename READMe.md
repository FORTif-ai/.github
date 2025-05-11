# FORTif.ai: An AI assistant for Independent Safe Senior Living 
In partnership with [WAT.ai](https://watai.ca/#/)

## TPMS and Their Contact Info

### Lino Kee
- **LinkedIn:** https://www.linkedin.com/in/linokee0423/  
- **Email:** guitarkinglino@gmail.com  
- **GitHub:** d-lino-kee  
- **Discord:** dalinoman  

### Edson Takei
- **LinkedIn:** https://www.linkedin.com/in/edsontakei/  
- **Email:** etakei@my.yorku.ca  
- **GitHub:** edsontakei  
- **Discord:** luketonbeleu  

## Ultimate Objective
FORTif.ai is an AI-driven companion that empowers seniors to live independently by merging proactive safety monitoring with tailored daily support. Using a computer-vision–powered Hazard Detection model, it continuously scans the home for potential risks—like spills, cluttered pathways, and tripping hazards—and offers clear, actionable recommendations to address them. At the same time, an intuitive AI chatbot engages users in friendly, proactive conversations, providing timely medication and appointment reminders, personalized wellness check-ins, and empathetic responses to questions or concerns. With built-in voice-to-text capabilities and real-time safety insights, FORTif.ai delivers a seamless, user-centric experience designed to enhance home safety, streamline everyday routines, and foster lasting independence for seniors.

## Project Goals

1. **AI Chatbot (LLM)**: Design and deploy a robust conversational assistant
   - Develop reliable voice-to-text transcription with built-in quality control
   - Implement an action-oriented interface for booking appointments and sending medication reminders
   - Ensure LLM responses are accurate, relevant, and aligned with senior-friendly language
   - Integrate the chatbot with the back-end Hazard Detection system for contextual alerts
   - ***AI Topics:*** *Speech Recognition, Prompt Engineering, LLM Evaluation, System Integration*

2. **Hazard Detection (OpenCV)**: Build and validate a vision-based model for home-hazard identification
   - **Subgoal 1:** Model development to detect obstacles along predefined walkways
   - **Subgoal 2:** Define performance metrics and risk thresholds (e.g., model accuracy and obstacle risk scoring)
   - **Subgoal 3:** Curate and preprocess high-quality training datasets (data cleansing, augmentation, transformation)
   - Quantify obstacle count and relative size for risk prioritization
   - Establish a 70:30 training-testing data split to evaluate generalization
   - ***AI Topics:*** *Computer Vision, Object Detection, Data Preprocessing, Model Evaluation*

3. **Integration**: Deliver a seamless, end-to-end user experience
   - Push real-time hazard alerts and recommendations through the AI chatbot
   - Conduct end-to-end testing of voice, vision, and notification pipelines
   - Validate system performance in simulated home environments and user trials
   - ***AI Topics:*** *Multimodal integration, API Development, UX Design, Automated Testing*

## Background
As the global population ages, many seniors face significant challenges in maintaining their independence while ensuring their safety. Common risks include falls, accidents at home due to environmental hazards, and difficulties in managing daily tasks, such as taking medications or attending appointments. These issues often lead to a decline in quality of life and can result in a need for constant caregiver assistance, which is not always feasible or sustainable.

The goal of this project is to address these challenges by providing seniors with an AI-driven assistant that promotes both safety and independence. By using computer vision for hazard detection, gait analysis for fall vulnerability assessment, and a user-friendly chatbot for daily reminders and check-ins, we hope to ensure that seniors can confidently navigate their living spaces while staying on top of their personal care routines. This project aims to reduce the risk of accidents, improve daily living, and empower seniors to maintain their autonomy in a safe, supportive environment.

## Interesting Background Papers and Links

#### 1. Elderly Falls
##### Key Articles and Research Papers
- *Nonfatal and Fatal Falls Among Adults Aged ≥65 Years*  
- Kakara, R., Bergen, G., Burns, E., & Stevens, M. (2023). *CDC MMWR Report*  

#### 2. Tools and Tutorials for OpenCV and YOLO
##### OpenCV Resources
- [OpenCV Tutorials (C++ & Python)](https://docs.opencv.org/4.x/tutorials.html)  
- [OpenCV Python Tutorials](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)  
##### YOLO Resources
- [YOLO for Object Detection (Darknet)](https://pjreddie.com/darknet/yolo/)  
- Aggarwal, A. (2024). *YOLO Explained* on Medium  
- Kalra, K. (2023). *YOLO Object Detection Overview*  

#### 3. Design Principles to Accommodate Older Adults
- Farage, M. A., Miller, K. W., Elsner, P., & Maibach, H. I. (2012). *Global Journal of Health Science: Design Principles for Older Adults*  

#### 4. Convolutional Neural Networks (CNNs)
- Essential for image classification tasks. FORTif.ai will use CNNs to analyze home-interior images and extract hazard features.  
- **Resource:** [IBM: Convolutional Neural Networks](https://www.ibm.com/think/topics/convolutional-neural-networks)  

#### 5. Image Classification
- Fundamental to classifying and scoring images of safe vs. hazardous environments. Ergonomic benchmarks derived from senior-friendly home images inform the model.  
- **Resources:**  
  - [Custom Vision Service: Getting Started](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier)  
  - [Image Classification on Papers With Code](https://paperswithcode.com/task/image-classification)  
  - [Viso.ai: Image Classification](https://viso.ai/computer-vision/image-classification/)  

#### 6. Reinforcement Learning
- Used to develop a safety-scoring system: preprocessed images guide an RL agent to detect obstructions and assign risk scores.  
- **Resources:**  
  - [Getting Started with Reinforcement Learning (Medium)](https://gordicaleksa.medium.com/how-to-get-started-with-reinforcement-learning-rl-4922fafeaf8c)  
  - [UBC CPSC533: Reinforcement Learning](https://www.cs.ubc.ca/~van/cpsc533/rl.html)  

#### 7. Data Manipulation with Python Tools
- Libraries like Matplotlib, Pandas, NumPy, and Scikit-learn support preprocessing, visualization, and feature engineering.  
- **Resources:**  
  - [Kaggle Discussion: Top Matplotlib Visualizations](https://www.kaggle.com/discussions/general/414271)  
  - [Machine Learning Plus: Master Plots in Python](https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/)  
  - [Awesome Scikit-Learn GitHub](https://github.com/fkromer/awesome-scikit-learn)  

#### 8. Human Biomechanics
- Gait analysis and common gait abnormalities in seniors inform hazard-scoring algorithms.  
- **Resources:**  
  - [Gait Patterns in Older Adults (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5318488/)  
  - [Gait Variability & Fall Risk (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC2872829/)  
  - [Rehabilitation Biomechanics (Nature)](https://www.nature.com/articles/s44172-024-00193-5)  

#### 9. Computer Vision Techniques
- Core methods: object detection, image classification, and augmented reality overlays for hazard highlighting.  
- **Resources:**  
  - [OpenCV Documentation](https://docs.opencv.org/4.x/index.html)  
  - [OpenCV GitHub Repository](https://github.com/opencv/opencv)  

#### 10. AI/ML Frameworks
- TensorFlow and PyTorch provide the backbone for model development, training, and deployment.  
- **Resources:**  
  - [TensorFlow](https://www.tensorflow.org/)  
  - [5 Best Resources to Learn TensorFlow (Medium)](https://robterceros.medium.com/the-5-best-resources-to-learn-tensorflow-in-2020-65b764a5fb8c)  
  - [PyTorch](https://pytorch.org/)  


## Project Timeline

# The Team

## Technical Project Managers

### Lino Kee

**Role:** Hazard Detection Model Development Lead

[Lino Kee](https://www.linkedin.com/in/linokee0423/) is an undergraduate student at the University of Waterloo studying Honours Management Engineering. He brings academic and practical co-op experience in project management, data analysis, automation development, quality assurance, business platform management, and software development. Lino leads the development of the computer-vision–driven Hazard Detection model and oversees the overall architecture and delivery of the FORTif.ai tool. He’s happy to answer questions about project scope, timeline, and the long-term vision for FORTif.ai.

### Edson Takei

**Role:** AI Chatbot Lead

[Edson Takei](https://www.linkedin.com/in/edsontakei/) 

## Core Members

### 🖥️ Hazard Detection Subteam (Lead: Lino Kee)

- **Dhruv Sharma** ([`@dhruvsharma11`](https://github.com/dhruvsharma11))
Hello, my name is Dhruv Sharma and I'm a 4th year Management Engineering student! My main interests include playing and watching sports such as basketball and cricket. I also really enjoy playing video games. My main role on the team is to help with the fall detection model!

- **Naomi Eshetu** ([`@naomieshetu`](https://github.com/naomieshetu)) 
Hi my name is Naomi and I'm a 3rd year Biomedical Engineering student! I enjoy reading, roller skating, and watching true crime. My role on the team is to do hazard detection and biomechanics research.

- **Marco Kee** ([`@Keezyyy`](https://github.com/Keezyyy)) 
Hello! My name is Marco and I’m a 2nd year Health Sciences student. I love watching sports (especially football), going to the gym, and watching a new movie with friends. I’m involved with the hazard detection and biomechanics research for this project!

- **Adnan Habib** ([`@adnxnhabib`](https://github.com/adnxnhabib))
Hey! I'm Adnan and I'm a 4th year CS/BBA student. I love video games, movies, going to the gym and chilling. I'm part of the hazard detection team helping to build our model!

- **Owen Kim** ([`@Owenkim2006`](https://github.com/Owenkim2006))  
Hi, I'm Owen and I'm a first year BME student. I am interested in learning about new developments in ML/AI, and I love playing many sports such as basketball, volleyball and ultimate frisbee. I will be working on the hazard detection and biomechanics sub team for this project.

- **Sania Banga** ([`@Saniabanga`](https://github.com/Saniabanga))  
Hi! My name is Sania and I’m a 4th year student majoring in CS. I love reading, hiking and watching horror movies. My role on the team is to help with the fall and hazard detection!

- **Meghana Yarlagadda** ([`@yarlas99`](https://github.com/yarlas99))  
Hello I am Meghana, 3rd year Statistics and Computational Mathematics student. I will be working on the Fall and hazard detection team.

---

### 🤖 AI Chatbot Subteam (Lead: Edson Takei)

- **Anahad Dhaliwal** ([`@Anahadd`](https://github.com/Anahadd))  
I'm Anahad, first year CE student. I love coding and watching sports. I'm very interested in LLMs.

- **Larris Xie** ([`@Profilist`](https://github.com/Profilist))  
Hi, I'm Larris, a 1st year CS student at the University of Waterloo. I enjoy playing the piano and basketball in my free time. I'm currently working on LLM agents for FORTif.ai! 

- **Akil Giri** ([`@akilgiri`](https://github.com/akilgiri))
Hi, I’m Akil, a 3rd year Computer Engineering student at the University of Waterloo. I enjoy playing video games and going on walks in my free time. I’m currently working on AI Chatbot team on FORTif.ai
 
- **Lucas Khan**
  Bio coming soon
