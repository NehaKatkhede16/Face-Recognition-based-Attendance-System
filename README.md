# Face-Recognition-based-Attendance-System using Python and Opencv.
#Diploma- Final Year Project#

Steps to Follow:
Download or Clone Repository: Get the project files to your device by either downloading or cloning the repository.
Install Required Packages:
Open the command prompt and navigate to the project folder.
Run the command:
Copy code
pip install -r requirements.txt
This will install all the necessary packages.
Create TrainingImage Folder: In the project folder, make a new folder named TrainingImage where the system will save the images for training.
Update Paths: Open the files attendance.py and automaticAttendance.py. Change all file paths to match your system's file structure.
Run the Attendance System: Execute the attendance.py file to run the attendance system.

Project Flow & Explanation 🚀
1.Register Your Face 👤
- When you run the project, click on "Register New Student".
- A small window will pop up 🪟 where you’ll enter your ID and Name.
- Click "Take Image" 📸 to open the camera window. It will detect your face and capture up to 50 images (you can adjust this number).
- These images will be stored in a folder named TrainingImage. The more images you provide, the better the system will perform while recognizing faces.
  
2.Train the Model 🤖
- After capturing your images, click "Train Image". This will train the system by converting all the images into numeric data so the computer can understand them.
- The training process might take some time ⏳ depending on your system. Once trained, the system can easily recognize your face.
  
3.Automatic Attendance 📝
- Click "Automatic Attendance" and enter the subject name.
- The system will mark attendance using the trained model and create a .csv file for each subject, keeping all records organized.
- 
View Attendance 📊
-After recording attendance, click "View Attendance" to see the records in a neat, tabular format.
