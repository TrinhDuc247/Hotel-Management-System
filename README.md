# Hotel-Management-System

## INTRODUCTION
This is our project about HOTEL MANAGEMENT SYSTEM to manage bookings, employees, 
rooms, service and hotels efficiently in order to provide best service. We have implemented this 
project using the concepts of database designing along with frontend using c# and MS Sql Server 
to make our program more efficient. We have provided few services such CRUD operations for 
all aspects where required. We have also tried to manage project security and integrity using 
various constraints and abstracting data.

## HOW TO RUN
Make sure that you have Microsoft Sql Server installed in your PC. Along with that I have already uploaded the query file which you just have to run to create database. Connect your application from Visual Studio Code with Microsoft Sql Server services of integrating database. You are now good to go! 

## SCREENSHOTS
![Screenshot 2024-12-26 200816](https://github.com/user-attachments/assets/20bedde3-ef39-4a76-b365-bfd6cf9c343a)
![Screenshot 2024-12-26 200835](https://github.com/user-attachments/assets/4199d904-39d9-41ca-a50e-8195de52e539)
![Screenshot 2024-12-26 200856](https://github.com/user-attachments/assets/29df422d-8cf3-41f0-86f6-a69c57a29d83)
![Screenshot 2024-12-26 200925](https://github.com/user-attachments/assets/08faff3a-7bf7-4d90-8de8-f896683e25e4)
![Screenshot 2024-12-26 174308](https://github.com/user-attachments/assets/352430df-a68f-4254-bf7f-a0a90ae95c7b)
![Screenshot 2024-12-26 174357](https://github.com/user-attachments/assets/56bc2698-b10c-497c-86e5-24334cf8a2b5)
![Screenshot 2024-12-26 174926](https://github.com/user-attachments/assets/2fbe001b-d280-4928-be76-12eb70233621)
![Screenshot 2024-12-26 175737](https://github.com/user-attachments/assets/d2630fc8-9492-4a18-8017-63a1a3f77e80)
![Screenshot 2024-12-26 175844](https://github.com/user-attachments/assets/adf763c7-bb19-411c-b714-02eec4e424e5)
![Screenshot 2024-12-26 180004](https://github.com/user-attachments/assets/15af8c3a-5bae-4856-931e-6bc2f5fe0e61)
![Screenshot 2024-12-26 180048](https://github.com/user-attachments/assets/def03a69-6918-483b-bd2e-2ca199421a4a)
![Screenshot 2024-12-26 180215](https://github.com/user-attachments/assets/0c3718b7-b41b-48a7-8857-496a8dbb54c1)
![Screenshot 2024-12-26 180257](https://github.com/user-attachments/assets/8ff3f6f3-80e0-490e-9daa-1cd7aeb4660c)
![Screenshot 2024-12-26 180349](https://github.com/user-attachments/assets/e48dacda-13c0-44c4-aadb-94ca6debceb5)
![Screenshot 2024-12-26 191629](https://github.com/user-attachments/assets/6a61162f-8afe-4608-bbf6-1273b1bf6dcc)
![Screenshot 2024-12-26 191721](https://github.com/user-attachments/assets/3c21f006-368b-4f71-92b1-99bbd9f512a9)
![Screenshot 2024-12-26 202128](https://github.com/user-attachments/assets/16d4ea87-b6f3-4785-a89d-c49e4dfa70b9)
![Screenshot 2024-12-26 191934](https://github.com/user-attachments/assets/fc0570ff-5e9a-44f5-8530-7180b4f24d8f)
![Screenshot 2024-12-26 192057](https://github.com/user-attachments/assets/e715883b-b4cf-44f0-abf7-e8f4bf3d1081)
![Screenshot 2024-12-26 192605](https://github.com/user-attachments/assets/6393935e-c7e5-43df-b64a-a52198e10aa2)
![Screenshot 2024-12-26 192643](https://github.com/user-attachments/assets/776fa6d5-697c-4302-b1fc-cd42730ceba2)
![Screenshot 2024-12-26 193224](https://github.com/user-attachments/assets/b11a1a1d-56db-4291-91ce-bbc9ce381ac5)

![image](https://user-images.githubusercontent.com/74453775/194845204-f1e24881-841b-4827-bc36-d86f15ce80d2.png)
![image](https://user-images.githubusercontent.com/74453775/194845255-a691caea-fdf7-4c2b-a886-ce053146c9ec.png)
![image](https://user-images.githubusercontent.com/74453775/194845282-2b07bfe4-2b35-4363-88f6-84901ef4a0bf.png)


## OBJECTIVES
Here's the logic behind our project. The design of our project is based on SAS applications where 
we provide Software as Service. Firstly, we are the super admins of this application and the hotel 
owners can get our application on subscription based model. We will be registering the hotels in 
database and authenticating them to use this application.
The purpose is to build this in a way that this reduces the manual and paper work for managing 
hotels, guest’s and employee’s data. Moreover, we have also added to functionality to provide 
hotel reports in order to maintain the record of bookings and payments.
We have provided full rights to user where he can add, update, search and delete information when 
required. Best database design is used in order to increase efficiency of managing data from various 
hotels.
Application have following features: 
• Adding, updating, deleting and searching Hotels.
• Generate hotel reports based of bookings.
• Adding services.
• Adding employees. (CRUD)
• Adding guests (CRUD)
• Maintaining payments of guests. 
• Maintaining revenue of hotel.

## MOTIVATION
The motivation behind the idea is that now a days the world is getting digitalized so in order 
to remove all manual and paper work we have created system which would help us to manage 
data more accurately and efficiently. Moreover, this would give an ability to keep records of 
guests and employees which could be further used for analytics.

## FLOW OF APPLICATION
1. When a hotel owners comes to register his hotel in database and avail subscription, we will 
add hotel details in the database and provide a username and password which must be 
change when the user login for the first time.
2. Hotel owner (user) has a right to add employee, add services, add discounts and add rooms. 
He can also view details of bookings, guests and payments. Total revenue would be visible 
only for the owner.
3. He can also add room type and departments in the system.
4. Once a hotel owner adds employee, if he is from HR, Admin or IT department so it’s 
necessary to create account that would be auto generated. 
5. When employee login first time, he will change password and add security question along 
with answer. This would ensure the maximum security of the application.
6. Registered employee can add guests, rooms, discount, services, payments and bookings. All 
have CRUD operations.
7. Guest status can be changed to check-in and checkout. 
8. Employee can filter data according to check-in and checkout.
9. Aggregate cost of stay duration and services used is automatically generated along with 
giving discount if applicable.
10. On checking out of the guest, the amount is added to hotel gross revenue. 
11. The rooms have status of availability which would be marked as YES if it’s not booked and 
NO if it’s reserved.
12. Room type can be set by employee and ceo along with the rates.
13. Login user can reset there password if required

## CHALLENGES AND LIMITATIONS
We faced most of the challenges in creating relationships among tables. We need to make sure that all 
the relationships created among tables are logical and follow the normalization rules. The most 
challenging part was creating the booking and the rooms table and its relationships with other 
respective tables. Another challenge was to learn and research about the designing framework to use 
for frontend and we ended up using GUNA. It was difficult initially but we were able to integrate it. 
We had some issues initially to use foreign keys where required so to overcome that we used tokens in 
Statics file. We also research about basics of C# as it was new for us along with Visual Studio as it was 
new environment for us to work. Another challenge was that to decide where to use foreign keys in 
regards to using it in plain MS Sql server and then accessing it from the frontend. We wanted to use 
few dependencies in order to generate reports which was a challenge for us. When we create accounts 
our initial approach was to email username and password to user but after 30 May 2022 it was 
restricted by Gmail to access any third party software so we ended up using security question and 
answer to overcome it.

## TOOLS AND TECHNIQUES
The language that is used is C# and for IDE Visual Studio is primarily used. Basic concepts of 
OOP along with best database design approach is used with MS Sql Server.

## CONCLUSION
Overall, the project has achieved its objectives. This was an attempt to create a database 
management system for hotel where a DBA can easily manage the hotels, rooms, bookings, 
guests, employees, departments, services, etc. and other things as well, easily and quickly. 
Overall, it is huge area and we tried to cover most of the parts of it. If we see this project in a long 
run, the world is changing and now everything is digitalize so this will be a productive and to 
optimize work load of everyone and reduce human efforts and work load and replace manual 
paper work.

FOR MORE DETAILED EXPLANATION, PLEASE REVIEW OUR PROJECT REPORT WHICH CONTAINS UI IMAGES AND MORE VALUABLE INFORMATION!

## Extended Software Documentation Repository Link:
> https://github.com/aliasar1/Hotel-Management-System-Documentation

HAPPY CODING! :D
