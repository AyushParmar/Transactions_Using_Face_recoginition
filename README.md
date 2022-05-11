# Transactions_Using_Face_recoginition

The Project is a Community Project for VIT Bhopal course. The project is a Face Recoginition System developed using Spring Boot, Java, hibernate, MySQL, and Python. The Project requires following implimentation before running everything on the System.

The Folder ajBanking contains the Banking website which enables the user to perform Deposit and Withdrawal of funds. The Folder OpenCV-Face-Recognition-master contains the Python Script which is used to make transactions using face Recoginition.

Basic Start: Run the SpringBoot Application ajBanking and direct towards localhost:8081 on your browser. Click on the Registration and get Register for the banking. SignIn using the Username and Password you created at the time of registration.

Now, Go to the mySQL workbench and locate the user table and find the serial number your name data is stored at and train your face in 01_face_dataset file, and use this serial number to enter the ID of the specified face to be trained. open the OpenCV-Face-Recognition-master folder and run the file named 01_face_dataset inside the Face Recoginition Folder and run the script. open 03_face_recognition_02 file and start Transacting.

now once you made the transaction, go to the localhost:8081 ajBanking site and sign in using your data. Check the transactions and amount after doing some transactions using python Script.

Necessary Extensions should be installed before running any script.

Also Import the SQL file in you workbench.

*Note: Do not forget to update the relevant information about MySQL connectivity in src/main/resources/application *Note: Do not forget to update the relevant informations in your 01_face_dataset, 02_face_training, 03_face_recognition_02 about SQL Connectivity and Data Storage locations

The Project is a prototype of how transactions using face recoginition take place. This can be improved on various levels with abundance of possibilities.
