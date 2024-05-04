# Eat with AI
The purpose of this project is to address the challenges associated with manual event attendance tracking by developing a comprehensive solution that leverages computer vision and AI technologies. The manual methods currently in use are time-consuming, error-prone, and lack real-time insights, making it difficult for event organizers to manage attendance effectively. We envision an application that allows event organizers to seamlessly set up events, implement real-time attendance tracking using cameras, and organize historical attendance data for analysis. Our project's design involves capturing event video using a companion app, managing administrative functions through our main web app, and implementing an object detection algorithm for attendance tracking. The key features include accurate attendance counting, real-time reporting, flexible recording options, compliance and security features, user-friendly interface, and data security. In this report, our objective is to outline a thorough plan for the implementation of the Event Attendance Tracking integrated with Artificial Intelligence project, also known as: EAT with AI.

## The structure of the project, and its repositories
The project is contained within 5 different repositories.

1. Backend (backendApp Repo)  
This repository contains our backend code which include basic CRUD routes, and other API calls. Also, this server interacts with our MongoDB database.

2. Machine Learning (crowdCounting Repo)   
This repository contains code to our image processing server. The sole job of this server is to count number of people in an image.

3. Companion App (mobileApp Repo)   
This repository contains our mobile application code which captures the video/frames to be used for the purpose of crowd counting.

4. Frontend (webApp Repo)   
This repository contains our web application code which include different web pages a user can interact.

5. Testing the application (streaming_simulator)   
This repository contains code to test our project.

For the best setup experience, follow steps 1-5 in that order. Setup instructions for each component can be found in that repository.


