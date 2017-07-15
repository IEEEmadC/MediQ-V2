Team Details
Team Name - TryCatch

Member Name 1 (Team Leader): Wasura Wattearachchi    E-mail: wasuradananjith@gmail.com

Member Name 2: Hisan Hunais    E-mail: hisan.live@gmail.com

Member Name 3: Kasun Dissanayake    E-mail: kasunprageethdissanayake@gmail.com


Aims and Objectives
Scenario: Most of the time patients make appointments to channel doctors, but the doctors will not be able to come at the right time. If we consider the time we waste in hospitals while waiting till our number is displayed on the screen of the doctor’s room, the scope narrows quickly.
For example, let’s assume doctor has to be there in the hospital at 4.00pm, but due to some reason he will come late, like around 5.00pm. So, the patients are waiting and it will waste their time, right??
We came up with a solution to end the hassle of waiting in the queue for hours. Instead, with our system, people can arrive at the hospital at the right time for his/her turn. MediQ - “End the Hassle of Waiting. Manage Time”
This will be ideal for countries like Sri Lanka, India etc.

Project Functions
•	Ability to get notification by mentioning a particular appointment number. In order to be on time, patient can enter any number before his/her appointment number and he/she will be informed when that particular number is being checked by the doctor.
        Example: Assume that patient’s appointment number is 10 for a particular appointment. He/she can enter 8, so a notification will be received when that particular appointment number is being checked by the doctor.
•	Ability to check the appointment number of the current patient.
•	Receiving notifications when the doctor is IN or OUT.
•	Generating an estimated time for client’s appointment number based on doctor’s arrival time, current number and average time taken to inspect a patient. 
•	We are planning to provide an app for the doctor to ease his task. 

How to operate
•	“Android Studio Project” directory has to be imported using Android Studio, and run it. (This is the Android App for patients)
•	“Net Beans Project” has to be imported using NetBeans, and run it. (This is a java application for the Doctor/Hospital)
•	Additionally, we are using an online server to host our database (assuming that it is the hospital database) which is remotely connected to the java application and android application separately.
•	I am sending you the .sql file and php scripts in " MediQDB Server - hostbuddy.net" directory so you can check our database details if you need. (I have mentioned/commented the local server connection details also in the source code. It is better if you can test this using the local server)

Example Scenario to execute the Android App, based on database information. (To check the app, please provide given example data which are stored in our database)
•	First, run the Android App "MediQ". Register by providing a username, a password and a phone number. Then, Log In.
•	Second, open the java application (for doctor to increase numbers). And log in providing doctor details. (You can check by providing "637411111V","abc" as NIC and Password and select the session "S0001")
•	To check which number is now being check by the doctor, select "Current Number" button. And enter the reference number for the particular appointment. (Check by providing reference numbers A0001,A0002,A0003....)
•	To request a notification, click on "Request" button. Then, the patient can request, mentioning at which appointment number that he/she should receive the notification. (Assume, reference number A0014, has appointment number 8, and he want to be notified when number 2 is IN. So enter "2" in the "Enter an appointment number to notify :" field , and then increment the counter to "2" by java application for the Session "S0001". You will recieve a notification via android app within few seconds)
•	P.S :- Enter the above data which I have mentioned between brackets (because those details are in the database), so you can successfully test our applications. 

Video links
https://youtu.be/yJlxWn_1kzc
https://youtu.be/e59w_ZMlgT4
