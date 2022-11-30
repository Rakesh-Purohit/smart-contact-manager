Exploring the vastness of JAVA! 

I like to present my new complete FULL STACK Project "Smart Contact Manager" which I developed using Spring Boot. Here I have followed the MVC design Pattern for designing this mega project.

This application help the user to store your contact in much better smarter way by adding images & detailed description of your contact and if required can modify it any time in future. It also provides feature to enable/disable the USER using ADMIN role which has access to this feature. I have also used Spring Boot Security feature to secure this app. Anyone without Login cannot directly add the new contact. This also has two separate dashboard for USER as well as for ADMIN.

The Project consist of Modules such as USER module, ADMIN module, CONTACT module, PASSWORD Module and SEARCH module.

@ User Module: Here any particular USER can first register with his details on app and then can LogIn into the system with username as Email and password.
@ ADMIN Module: ADMIN has the access to enable or disable any particular user from his ID. By default the USER will be enable.
@ CONTACT Module: USER can add contact in it, can delete it or update the details, see Profile pic and can do many more.
@ PASSWORD Module: If USER which to change the password then after LogIn, can do this by entering the old password and new password in it.
@ SEARCH Module: If their are many contacts in the contact List then user has this SEARCH feature to search contact using contact name.

In FRONTEND: I have used HTML,CSS,BOOTSTRAP and THYMELEAF template for dynamic content and some JAVASCRIPT for actions in our Page to toggle the sidebar.
In BACKEND: I have used Spring Boot Servies like Spring Boot Rest and Spring Boot Data JPA and also used Spring Security for Authentication
DATABASE: I have used MySQL database here with SQL language query.

Functionalities:
-> User Registration
-> User Login
-> User Dashboard
-> Create Contacts
-> View Contact
-> Maintain/Edit Contact
-> Role Based authentication and Authorization
-> Change Password feature
