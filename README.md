# GROUP-PROJECT PROPOSAL A
KULLIYYAH OF INFORMATION & COMMUNICATION TECHNOLOGY
SEMESTER 2, 2020/2021

INFO 3305 WEB APPLICATION DEVELOPMENT
SECTION  03

Supervised by:
Dr. Mohd Khairul Azmi Bin Hassan

## Group Members

- Nurul Najihah Binti Khairul Najmy 1915634

- Nisa Syazana Bt Mohamed Rizal 1914200

- Siti Nor Farihan binti Supia 1911992

- Muhammad Rafiqul Islam 1823295

# STUDENT DASHBOARD

### INTRODUCTION

The student dashboard provides the information for the student regarding their studies. All of the student’s information, including their assignments, attendance records, and more, is stored and tracked. The web application acts as an automated filing cabinet for school-related documents.  It can also be used to capture and visualize traces of learning experiences to encourage comprehension, reflection, and sense-making, as well as to help students set goals and monitor progress toward them. It is a simple web application that instantly and easily shows the users their level of interaction with their studies similarly to our university’s dashboard, iTaleemc. There are several benefits that can be obtained from this application. Firstly, to improve management of prospective and enrolled student data. This is because all of the students’ information will be stored at one place. Next, it will help to increase communication between the student and lecturer. Both of the parties will be able to communicate with each other through this platform. Lastly, it will help to reduce the time spent on maintaining and organizing student records as the records are kept at a central location and can be obtained easily. Our hope is that by creating this web application, students will be able to use the dashboard to help them take control of their studies and improve their skills. According to our plan, our team will be focusing on the student’s side of the platform therefore, the primary users are students. 

### OBJECTIVE

The student dashboard provides students with the information to track their own performance and acts as a channel of communication between their instructors. Our objective in creating this Web-Application is to-

- Dashboards that visualize student competency success both inside and across courses.
- Students would have access to their assignments and attendance records.
- Students will have the option to personalize their profiles.
- Only the subjects taken during the current semester will appear in our dashboard.

### FEATURES AND FUCTIONALITIES

This web application will have five pages. Below are the features and functionalities for each page.
1. Login Page: The students can login into their account by inserting their matric no and password.
2. Homepage: The homepage of the student dashboard showcases the overview of the website. There are several elements that will be included in this page:

- subjects that the students are enrolling
- calendar
-  week
-  time
-  lecturer details
-  important announcements

3. Student Profile Page: This page will display personal information of the students. For example, their full name, student id, email address and home address.
4. Attendance Page: The students are able to record and check their attendance according to each subject that they have registered for the semester. 
5. Assignment Page: The students are able to check the due dates of assignments and tasks that have been given to them by their lecturer and also submit their work. 

### DEFINATIONS OF VIEWS, CONTROLLERS< ROUTERS AND MODELS

Firstly, the route is a handler that will map the URL to a particular action when the user start to use the application. Next, the view is defined as a script that will display all the data in the user’s browser. Then, the model will interact with the database and it will carry the data to the view. After that, controllers will handle and fill the model with data that has been modified or updated. 
Before the user can start using the website, the user needs to log in using student id and password. The user will send a request to the route to log into the website. Then, it will redirect to the Homepage(view) and the users can request for the Student Profile page(controller) to update or modify their details. After the user successfully updates or modifies the details, the same page will display the stored data. Here is model will be used to interact with the database when the user change their data. The students are also able to submit their attendance and assignment using the Attendance page(view) and Assignment Page(view).

![ER DIAGRAM](https://user-images.githubusercontent.com/61734948/117008877-bf4bba00-ad1d-11eb-9c5e-7971c60727a1.png)

### SEQUENCE DIAGRAM

Sequence diagrams show how objects in the system interact with one another and it shows the sequence of the system. In our system there are seven objects that are represented in the rectangle boxes. The process begins when the user that is represented by the actor key in their login details that they have and it will pass to the database part to check whether the details is in the database or not. Moreover, it will then pass to the verification part to check whether the details are correct or not. The alternative happens when the details are correct, it will send the message to the user in the login page while if it is incorrect and it will pass the warning message in the login page to the users. 

Furthermore, after successfully login the object will go through to the homepage and an alternative happens when they would like to logout rather than proceed to the next page and the object will pass through until the login page back. Next, if users would like to proceed from homepage to profile page, the object will continue to pass until profile page and will encounter alternatives when they would like to logout from the profile page, the object will be passed to the login page. Furthermore,objects will pass from profile page to attendance page if the user proceeds from profile page to attendance page and the object will be passed to login page if they log out from the page. Finally, the object will continue to be passed from attendance page to assignment page if they proceed to the page and will make the object being passed to login page if they logout.
In addition, the object from the homepage can be passed directly to the profile page, attendance page and assignment page because the user can directly access it from the homepage. Next, activation boxes at each of the life lines shows that the longer the activation box, the more the object interacts in the system. 

![SEQUENCE DIAGRAM](https://user-images.githubusercontent.com/61734948/117007430-3b450280-ad1c-11eb-8f74-2ec50c1fa0df.png)


# MOCKUP 
1. LOGIN PAGE
![LOGIN PAGE](https://user-images.githubusercontent.com/61734948/117010118-0edeb580-ad1f-11eb-893a-273ed28da38a.png)

2. HOMEPAGE 
![HOMEPAGE](https://user-images.githubusercontent.com/61734948/117010141-143c0000-ad1f-11eb-91d9-d359f631a479.png)

3. PROFILE PAGE
 ![STUDENT PROFILE](https://user-images.githubusercontent.com/61734948/117010163-19994a80-ad1f-11eb-8089-5984c372179d.png)

4. ATTENDANCE PAGE
![ATTANDANCE](https://user-images.githubusercontent.com/61734948/117010186-2027c200-ad1f-11eb-9164-03ec83f44d5e.png)

5. ASSIGNMENT PAGE
![ASSIGNMENT](https://user-images.githubusercontent.com/61734948/117010225-2cac1a80-ad1f-11eb-9e49-d151ac0e9585.png)

# PROJECT SYSTEM & EXPLANATION
1.This page is for student to log in using their username and password
![WhatsApp Image 2021-06-16 at 23 24 15](https://user-images.githubusercontent.com/61734948/122248046-61081e80-cefa-11eb-8c1f-042e0ecbb7ea.jpeg)

2.This page is for student to take note on any notice and there are courses that they take for the semester being display for them.
![WhatsApp Image 2021-06-16 at 23 29 17](https://user-images.githubusercontent.com/61734948/122248647-cb20c380-cefa-11eb-904d-c4f2bfaf9ed1.jpeg)


3.This page is for student to view and edit their profile. 
![WhatsApp Image 2021-06-16 at 23 24 15 (1)](https://user-images.githubusercontent.com/61734948/122248709-d7a51c00-cefa-11eb-95c3-67aa9a602d88.jpeg)
![WhatsApp Image 2021-06-16 at 23 24 15 (2)](https://user-images.githubusercontent.com/61734948/122250826-93b31680-cefc-11eb-8ece-de7fb1b41c44.jpeg)



4.This page is for student to submit their attandance to the classes.
![WhatsApp Image 2021-06-16 at 23 24 14](https://user-images.githubusercontent.com/61734948/122248788-ea1f5580-cefa-11eb-8c36-8ff279e7f641.jpeg)
![WhatsApp Image 2021-06-16 at 23 24 14 (2)](https://user-images.githubusercontent.com/61734948/122250695-74b48480-cefc-11eb-8c3e-eff1349e5035.jpeg)



5.This page is for student to submit their assignment that had been assigned to them.
![WhatsApp Image 2021-06-16 at 23 24 13](https://user-images.githubusercontent.com/61734948/122248864-f7d4db00-cefa-11eb-9be5-fc14b2cc57ae.jpeg)
![WhatsApp Image 2021-06-16 at 23 24 13 (1)](https://user-images.githubusercontent.com/61734948/122250777-885feb00-cefc-11eb-9566-7e6ff80384a4.jpeg)



### CHALLENGE & DIFFICULITIES
1. It is quite hard to find a template that satisfy all of us and can be integrated. We found several of it and the template that we used is the only one that we sucessfully integrated it.
2. We encountered few problem on XAMPP and it is a rare case where it takes few hours for us to solve the issue.
3. Need to do a lot of research and watch Youtube videos to help in solving errors
4. In compilation, it is hard for the leader to compile all of it

# PRESENTATION GROUP PROJECT PROPOSAL
https://youtu.be/IOxlrE15G9s
