# Senior-Project-RKM

Senior Project: Smart School Bus Attendance System

This senior project presents a comprehensive system integrating machine learning algorithms and facial recognition technology to monitor and ensure the safety of students in real-time. The project aims to automate attendance taking and provide parents with timely notifications and status reports via a dedicated mobile application.

Project Overview
Interface Development: The user interface is developed using React Native, providing a seamless and interactive experience for both parents and school administrators.
System Architecture: Created UML diagrams to illustrate the system's design and workflow.
Machine Learning Integration: Utilized machine learning algorithms to accurately detect and recognize student faces.
Facial Recognition Technology: Implemented facial recognition cameras strategically placed inside school buses to capture students' faces from various angles.
Real-Time Monitoring: Enables real-time monitoring and notifications, ensuring parents are informed about their child's attendance status.

![6](https://github.com/Reemaharbi/Senior-Project-RKM/assets/97175030/bd9d638b-2ded-497f-8803-6335f5d6ea1a)

How It Works
- Face Capture: Cameras inside the buses capture images of students from multiple angles.
- Face Recognition: The system detects and recognizes faces from the captured images, comparing them with pre-stored images in the database.


Attendance Marking:
- Match Found: If a face matches the stored image, the student is marked as present, and no notification is sent to the parents.
- No Match/Undetected: If no match is found or the face is undetected, the student is marked as absent. A notification is sent to the parents, and the captured image is stored in the database as a new, unknown image for further analysis.
- 
![7](https://github.com/Reemaharbi/Senior-Project-RKM/assets/97175030/bbe05aa2-d5cf-4232-bcd6-7824a73eefeb)

Technical Stack
Backend: Python is used to program the backend, ensuring seamless communication between the application and the database.
Database: MySQL is utilized to manage and store student data.
Frontend: React Native and JavaScript are used to develop the frontend interface for school administrators and parents.
Hardware: High-quality cameras and mobile devices are used for testing and capturing student images.
Screenshots



![ezgif-5-313a593e3e](https://github.com/Reemaharbi/Senior-Project-RKM/assets/97175030/2bf85fde-71bd-41a8-b53e-4c06be4836a2)



