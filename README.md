# Senior-Project-RKM


Senior Project: Smart School Bus Attendance System
This senior project presents a comprehensive system integrating machine learning algorithms and facial recognition technology to monitor and ensure the safety of students in real-time. The project aims to automate attendance taking and provide parents with timely notifications and status reports via a dedicated mobile application.
Project Overview
	• Interface Development: The user interface is developed using React Native, providing a seamless and interactive experience for both parents and school administrators.
	• System Architecture: Created UML diagrams to illustrate the system's design and workflow.
	• Machine Learning Integration: Utilized machine learning algorithms to accurately detect and recognize student faces.
	• Facial Recognition Technology: Implemented facial recognition cameras strategically placed inside school buses to capture students' faces from various angles.
	• Real-Time Monitoring: Enables real-time monitoring and notifications, ensuring parents are informed about their child's attendance status.
How It Works
	1. Face Capture: Cameras inside the buses capture images of students from multiple angles.
	2. Face Recognition: The system detects and recognizes faces from the captured images, comparing them with pre-stored images in the database.
	3. Attendance Marking:
		○ Match Found: If a face matches the stored image, the student is marked as present, and no notification is sent to the parents.
		○ No Match/Undetected: If no match is found or the face is undetected, the student is marked as absent. A notification is sent to the parents, and the captured image is stored in the database as a new, unknown image for further analysis.
Refer to the architectural diagram in Figure 1.
Technical Stack
	• Backend: Python is used to program the backend, ensuring seamless communication between the application and the database.
	• Database: MySQL is utilized to manage and store student data.
	• Frontend: HTML, CSS, and JavaScript are used to develop the frontend interface for school administrators and parents.
	• Hardware: High-quality cameras and mobile devices are used for testing and capturing student images.

![image](https://github.com/Reemaharbi/Senior-Project-RKM/assets/97175030/2c81b361-6bca-43dd-957a-a1897ab28b32)



Screenshots

Below is a screenshot of the interface of the project, showcasing the homepage of the mobile application:


