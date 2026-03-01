# CS255-Portfolio

System analysis and design portfolio featuring the DriverPass project.

## DriverPass Project Artifacts
- [Business Requirements Document (Project One)]([DriverPass_Business_Requirements_Document_FINAL.docx](https://github.com/user-attachments/files/25666547/DriverPass_Business_Requirements_Document_FINAL.docx))
- [System Design Document (Project Two)]([DriverPass_System_Design_Document.docx](https://github.com/user-attachments/files/25666546/DriverPass_System_Design_Document.docx))
- [Client Presentation]([DriverPass_Client_Presentation.pptx](https://github.com/user-attachments/files/25666545/DriverPass_Client_Presentation.pptx))

## Project Summary
DriverPass was the client for this project. They wanted a secure, web-based system that helps students prepare for driving exams through online practice tests and by scheduling behind-the-wheel training. The system needed to support multiple user roles (customers/students, instructors, admins/staff, and IT) with role-based access and tools for scheduling, account management, and reporting.

## Reflection

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
The client was DriverPass. They needed a web-based platform where customers could register, purchase lesson packages, take practice exams, track results, and schedule/reschedule driving lessons. On the business side, staff needed the ability to manage users, scheduling, packages, and reporting.

### What did you do particularly well?
I did well at translating the client’s goals into clear requirements and then carrying those requirements into a system design that makes sense for implementation. I focused on keeping workflows and system expectations clear so the documents could be used as a blueprint for building the system.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one part, I would add more detail for exceptions and edge cases, especially around scheduling conflicts, invalid inputs, failed updates, and service outages (like payments or notifications). I would also tighten parts of the UML/design details so fewer assumptions are left to the development team.

### How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
I interpreted user needs by focusing on what customers and staff must be able to accomplish quickly and reliably—booking lessons, practicing exams, viewing progress, and managing schedules and accounts. Considering user needs is important because a system can meet requirements on paper but still fail if it doesn’t match real workflows or if it creates friction for the people using it daily.

### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
I start with requirements and user workflows, then I model system behavior with use cases and diagrams to catch gaps early. After that, I define technical constraints and nonfunctional requirements so the design is realistic to build and maintain. In the future, I want to include more acceptance criteria, simple wireframes, and clearer requirement-to-design traceability to make changes easier to manage.
