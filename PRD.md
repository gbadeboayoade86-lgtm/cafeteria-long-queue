# PRODUCT REQUIREMENTS DOCUMENT (PRD)

# Babcock University Cafeteria Lane Service Management System

  -----------------------------------------------------------------------
  Document Information                Details
  ----------------------------------- -----------------------------------
  Course                              BU-209 -- Backend Engineering

  Assignment                          Week 4

  Project Name                        Babcock University Cafeteria Lane
                                      Service Management System

  Document Type                       Product Requirements Document

  Version                             1.0

  Status                              Proposed

  Platform                            Web-Based Application

  Target Institution                  Babcock University, Ilishan-Remo,
                                      Ogun State, Nigeria
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# TABLE OF CONTENTS

1.  Introduction
2.  Executive Summary
3.  Background and Project Context
4.  Problem Statement
5.  Research and Problem Validation
6.  Research Methodology
7.  Target Users and Stakeholders
8.  Existing Process and Identified Limitations
9.  Proposed Solution
10. Product Goals and Objectives
11. Product Scope
12. Minimum Viable Product (MVP)
13. Functional Requirements
14. Non-Functional Requirements
15. User Stories
16. System Workflow
17. Database Requirements
18. Backend API Requirements
19. Security and Access Control
20. Acceptance Criteria
21. Constraints and Dependencies
22. Risks and Mitigation Strategies
23. Success Metrics
24. Future Improvements
25. Conclusion
26. References

------------------------------------------------------------------------

# 1. INTRODUCTION

The Babcock University Cafeteria Lane Service Management System is a
proposed web-based platform designed to improve communication,
information accessibility and service management within the university
cafeteria environment.

The cafeteria plays an important role in students' daily lives because
it provides access to meals during academic activities.

However, food service environments can experience challenges involving
food availability, customer feedback, service quality, communication and
the management of customer requests.

Research published in the Babcock University Medical Journal in 2026
identified several areas of dissatisfaction among students regarding
on-campus food services.

This project proposes a centralized digital platform that allows
students to access cafeteria information, view available meals, submit
feedback and communicate service-related complaints.

It will also provide authorized cafeteria personnel with tools to manage
food information, monitor feedback and respond to student concerns.

The project will focus on identifying genuine problems within the
cafeteria lane and developing a practical solution that improves the
overall service experience.

# 2. EXECUTIVE SUMMARY

The Babcock University Cafeteria Lane Service Management System aims to
improve how students interact with cafeteria services.

The proposed platform will provide a centralized environment where
students can:

-   View available meals and their prices.
-   Check food availability.
-   Access cafeteria information.
-   Submit complaints and feedback.
-   Monitor the status of submitted complaints.

Cafeteria personnel will be able to:

-   Manage food menus.
-   Update meal availability.
-   Receive student feedback.
-   Review complaints.
-   Respond to service-related issues.
-   Monitor feedback and complaint records.

The system will be developed with a focus on simplicity, security,
reliability and maintainability.

The first version will concentrate on essential information management
and communication features rather than introducing complicated features
that may not be necessary initially.

The proposed solution is intended to complement existing cafeteria
operations, not replace the university's food service department or
physical serving processes.

# 3. BACKGROUND AND PROJECT CONTEXT

Babcock University is located in Ilishan-Remo, Ogun State, Nigeria.

The university provides catering and food services to students and other
customers through its Food Services Department.

According to the university's official Food Services information, the
department is responsible for meeting the nutritional needs of students
and other customers through professional food services.

The department also has different operational units, including:

-   Directorate.
-   Finance Unit.
-   Warehouse.
-   Kitchen Section.
-   Quality Control.
-   Maintenance.

The university also publishes cafeteria meal information and serving
schedules through its official website.

These existing services demonstrate the importance of food information,
service coordination and communication within the university's food
service environment.

The proposed project will investigate how digital technology can improve
access to information and the handling of student feedback within the
cafeteria lane.

# 4. PROBLEM STATEMENT

Students depend on cafeteria services for their daily meals. However,
the quality of the overall cafeteria experience depends on several
factors, including food quality, pricing, availability, service
delivery, hygiene and communication.

A published study conducted among undergraduate students at Babcock
University identified concerns relating to food satisfaction, value for
money, dining conditions, staff availability and the handling of student
complaints.

These findings indicate that the cafeteria experience involves more than
simply purchasing food.

Students also need accessible information and effective ways to
communicate their experiences and concerns.

Without an organized digital feedback and information management
platform, it may be difficult to centralize service-related information
and monitor complaints consistently.

The proposed system will address this digital information and
communication gap by providing a platform for students and authorized
cafeteria personnel to interact more efficiently.

The system will not independently solve operational problems such as
insufficient staffing, poor ventilation or food preparation issues.
Instead, it will provide tools that help communicate, document and
manage these concerns.

# 5. RESEARCH AND PROBLEM VALIDATION

## 5.1 Existing Research

A 2026 research publication in the Babcock University Medical Journal
examined the perception and behaviour of undergraduate students towards
on-campus food operations.

The study involved 450 undergraduate respondents.

Some of its reported findings include:

  -----------------------------------------------------------------------
  Research Finding                                             Percentage
  ------------------------------ ----------------------------------------
  Students who had a poor                                           48.9%
  perception of cafeteria food   
  services                       

  Students who disagreed that                                       74.7%
  the food provided was          
  palatable                      

  Students who felt the food did                                    65.6%
  not offer good value for money 

  Students uncomfortable with                                       65.3%
  cafeteria ventilation          

  Students who disagreed that                                       49.1%
  staff maintained standard      
  hygiene protocols              

  Students who disagreed that                                       53.3%
  staff were friendly and        
  approachable                   

  Students who felt complaints                                      62.0%
  were not handled promptly      

  Students who disagreed that                                       66.0%
  the number of cafeteria staff  
  was sufficient                 
  -----------------------------------------------------------------------

These findings indicate that cafeteria service quality and the overall
dining experience are important areas requiring attention.

The research also identified improvements such as expanding cafeteria
space and providing staff training.

## 5.2 Research Interpretation

The findings suggest that cafeteria challenges are not limited to the
ordering process.

They involve several areas:

1.  Food satisfaction.
2.  Value for money.
3.  Dining environment.
4.  Hygiene practices.
5.  Staff availability.
6.  Customer service.
7.  Complaint management.

For this project, the most relevant opportunity is improving
communication, information accessibility and feedback management.

## 5.3 Initial Understanding Based on Personal Knowledge

At this stage, my understanding of the cafeteria lane problem is based on my general knowledge and experience as a student in the university environment. This is an initial assessment, not the result of a formal survey or completed interviews.

From this understanding, students may sometimes find it difficult to plan where or what to buy because information about meals, prices and availability may not always be easy to access before reaching a cafeteria stand. Students may also have different experiences with food quality, waiting time and customer service.

When a student has a complaint or suggestion, the available way of communicating it may depend on speaking directly to a cafeteria worker or using an informal channel. This can make it difficult for the student to know whether the concern has been recorded or followed up.

These points are the problems I want to investigate further. They should not be treated as confirmed facts about every cafeteria vendor or every student's experience.

## 5.4 Assumptions to Validate

The project will begin with the following assumptions:

1. Students would find it useful to view meal options and prices in one place.
2. Students would benefit from clearer information about whether a meal is available.
3. Students need a simple way to submit cafeteria-related feedback or complaints.
4. Cafeteria personnel may benefit from having complaints organized in one place.
5. Students may value being able to check whether a complaint has been reviewed.

These assumptions will be checked through further observation and conversations with students and cafeteria personnel before the system is fully designed.


# 6. RESEARCH METHODOLOGY

The project will begin with secondary research and an initial assessment based on my general knowledge of the cafeteria environment. Further primary research can be carried out to confirm or correct the assumptions.

## 6.1 Secondary Research

Secondary research involves examining information that has already been published.

Sources include:

- Babcock University's official Food Services website.
- Published research on Babcock University cafeteria services.
- Relevant academic research on university food service management.

## 6.2 Initial Personal Assessment

I will use my general understanding of how students access cafeteria services to identify possible problems worth investigating. I will distinguish what I personally know from assumptions that still need confirmation.

The areas I intend to examine include:

- How students find out what meals are available.
- Whether prices and availability are easy to know before joining a queue.
- How students decide which cafeteria stand to visit.
- How students currently raise complaints or suggestions.
- Whether students can tell if a complaint has been followed up.

## 6.3 Further Validation

If possible, I will speak informally with students and cafeteria personnel and observe the cafeteria lane. The purpose will be to check whether the assumptions in Section 5.4 reflect their actual experiences.

Possible questions include:

1. What is the most inconvenient part of buying food at the cafeteria lane?
2. How do you find out what food is available and how much it costs?
3. Have you ever gone to a food stand and found that the meal you wanted was unavailable?
4. If you have a complaint, how do you usually communicate it?
5. What one improvement would make the cafeteria experience easier?

Any responses collected will be recorded accurately. No interview, survey or observation will be described as completed unless it has actually taken place.


# 7. TARGET USERS AND STAKEHOLDERS

The proposed system will have three primary user categories.

## 7.1 Students

Students are the main users of the platform.

Their needs include:

-   Accessing cafeteria information.
-   Viewing food menus and prices.
-   Checking food availability.
-   Submitting complaints.
-   Providing feedback.
-   Tracking complaint responses.

## 7.2 Cafeteria Personnel

Authorized cafeteria personnel will manage food information and respond
to student feedback.

Their responsibilities include:

-   Updating menus.
-   Updating food availability.
-   Reviewing complaints.
-   Responding to feedback.
-   Updating complaint statuses.

## 7.3 System Administrator

The administrator will oversee the platform.

Responsibilities include:

-   Managing user accounts.
-   Managing staff accounts.
-   Assigning permissions.
-   Monitoring system activities.
-   Managing platform information.
-   Ensuring proper system operation.

# 8. EXISTING PROCESS AND IDENTIFIED LIMITATIONS

The existing cafeteria environment involves students obtaining meals and
interacting with cafeteria personnel.

The university also publishes food service information through its
website.

However, the proposed project will investigate whether the following
areas can be improved:

1.  Access to current food availability information.
2.  Access to cafeteria menus and prices.
3.  Communication between students and cafeteria personnel.
4.  Recording and tracking student complaints.
5.  Monitoring responses to reported issues.
6.  Centralizing cafeteria service information.

These areas are proposed investigation points rather than claims that
the existing university system has no such capabilities.

# 9. PROPOSED SOLUTION

The proposed solution is the Babcock University Cafeteria Lane Service
Management System.

It will be a centralized web-based application that provides students
with cafeteria information and a structured method of communicating
service-related concerns.

The platform will contain two main functional areas.

## 9.1 Student Interface

Students will be able to:

-   Register and log in.
-   View available cafeteria meals.
-   Check food prices.
-   Check meal availability.
-   Submit complaints.
-   Provide feedback.
-   View complaint status.

## 9.2 Management Interface

Authorized personnel will be able to:

-   Log in to the management dashboard.
-   Add and update food items.
-   Update food availability.
-   View submitted complaints.
-   Respond to complaints.
-   Update complaint statuses.
-   Monitor feedback and complaint records.

The system will provide a more organized method of managing information
and communication between students and cafeteria personnel.

# 10. PRODUCT GOALS AND OBJECTIVES

The main goals are:

1.  Improve access to cafeteria information.
2.  Provide accurate food availability information.
3.  Improve communication between students and cafeteria personnel.
4.  Provide an organized complaint submission process.
5.  Make complaint tracking easier.
6.  Help cafeteria personnel monitor recurring concerns.
7.  Improve the accessibility of cafeteria services.

# 11. PRODUCT SCOPE

## 11.1 In Scope

The initial system will include:

-   User registration.
-   User authentication.
-   Role-based access control.
-   Food menu management.
-   Food price management.
-   Food availability updates.
-   Complaint submission.
-   Feedback management.
-   Complaint status tracking.
-   Administrative dashboard.

## 11.2 Out of Scope

The following features will not be included in the initial version:

-   Physical food delivery.
-   Automated food preparation.
-   Artificial intelligence recommendations.
-   Loyalty and reward programmes.
-   Advanced sales analytics.
-   Integrated online payment processing.
-   Automatic cafeteria queue management.
-   Automated resolution of physical service problems.

These features may be considered in future versions.

# 12. MINIMUM VIABLE PRODUCT (MVP)

The MVP represents the smallest functional version of the proposed
system.

The first version will focus on six major features.

  -----------------------------------------------------------------------
  Feature                 Description             Priority
  ----------------------- ----------------------- -----------------------
  User Authentication     Allows users to         High
                          register and log in     

  Food Menu               Displays available      High
                          meals and prices        

  Availability Management Allows staff to update  High
                          food availability       

  Complaint Submission    Allows students to      High
                          report problems         

  Complaint Management    Allows staff to review  High
                          and respond to          
                          complaints              

  Status Tracking         Allows students to      High
                          monitor complaint       
                          progress                
  -----------------------------------------------------------------------

The MVP will prioritize these features before introducing advanced
functionality.

# 13. FUNCTIONAL REQUIREMENTS

Functional requirements describe the actions the system must perform.

## FR-01: User Registration

The system must allow students to create accounts using the required
registration information.

## FR-02: User Authentication

The system must allow registered users to log in securely.

## FR-03: User Roles

The system must distinguish between student, cafeteria staff and
administrator accounts.

## FR-04: Food Menu Management

The system must allow authorized cafeteria personnel to create, edit and
remove food menu entries.

## FR-05: Food Price Management

The system must allow authorized personnel to update food prices.

## FR-06: Food Availability

The system must allow authorized personnel to update the availability
status of food items.

## FR-07: View Food Information

Students must be able to view available food items, descriptions and
prices.

## FR-08: Complaint Submission

Students must be able to submit complaints relating to cafeteria
services.

## FR-09: Feedback Submission

Students must be able to provide feedback about their cafeteria
experience.

## FR-10: Complaint Management

Authorized personnel must be able to view submitted complaints.

## FR-11: Complaint Responses

Authorized personnel must be able to respond to complaints.

## FR-12: Complaint Status

The system must allow authorized personnel to update complaint statuses.

Possible statuses include:

-   Submitted
-   Under Review
-   In Progress
-   Resolved
-   Closed

## FR-13: Complaint History

Students must be able to view their previously submitted complaints and
their statuses.

## FR-14: Administrative Management

Administrators must be able to manage accounts, permissions and platform
information.

# 14. NON-FUNCTIONAL REQUIREMENTS

Non-functional requirements define how the system should operate.

## 14.1 Security

-   Passwords must be securely hashed.
-   User authentication must be implemented.
-   Users must only access authorized features.
-   Sensitive information must be protected.
-   Input validation must be performed.
-   Unauthorized access must be prevented.

## 14.2 Performance

-   The system should respond to normal requests within an acceptable
    period.
-   Database queries should be optimized.
-   The application should support multiple users accessing the
    platform.

## 14.3 Reliability

The system should handle normal operations consistently and provide
appropriate error messages when requests fail.

## 14.4 Usability

The interface should be simple and easy to understand.

The application should work on smartphones, tablets and desktop
computers.

## 14.5 Maintainability

The backend should be organized into manageable components to make
future improvements easier.

## 14.6 Scalability

The system should support additional users, food items and participating
cafeteria vendors as the platform grows.

## 14.7 Data Integrity

The system must maintain accurate user, food menu, availability and
complaint records.

# 15. USER STORIES

User stories describe what different users want to accomplish.

## 15.1 Student User Stories

-   As a student, I want to create an account so that I can access the
    platform.
-   As a student, I want to view available meals so that I can decide
    what to purchase.
-   As a student, I want to check food prices so that I can make
    informed decisions.
-   As a student, I want to check food availability so that I do not
    rely on outdated information.
-   As a student, I want to submit complaints so that I can report
    service-related problems.
-   As a student, I want to track complaints so that I know whether my
    concerns are being addressed.

## 15.2 Cafeteria Staff User Stories

-   As a staff member, I want to update food availability so that
    students receive current information.
-   As a staff member, I want to update menu prices so that displayed
    information remains accurate.
-   As a staff member, I want to view student complaints so that I can
    understand their concerns.
-   As a staff member, I want to respond to complaints so that students
    receive feedback.
-   As a staff member, I want to update complaint statuses so that
    complaint progress is recorded.

## 15.3 Administrator User Stories

-   As an administrator, I want to manage user accounts so that platform
    access is controlled.
-   As an administrator, I want to manage staff permissions so that
    users only access authorized functions.
-   As an administrator, I want to monitor complaints so that recurring
    problems can be identified.

# 16. SYSTEM WORKFLOW

The proposed system will follow these workflows.

## 16.1 Student Workflow

1.  The student opens the application.
2.  The student registers or logs in.
3.  The student accesses the dashboard.
4.  The student views cafeteria information.
5.  The student checks available meals and prices.
6.  The student can submit feedback or a complaint.
7.  The system stores the submitted information.
8.  The student can view the status of the complaint.

## 16.2 Staff Workflow

1.  The staff member logs in.
2.  The staff member accesses the management dashboard.
3.  The staff member updates food information.
4.  The staff member views student complaints.
5.  The staff member reviews submitted complaints.
6.  The staff member provides a response.
7.  The staff member updates the complaint status.

## 16.3 Administrator Workflow

1.  The administrator logs in.
2.  The administrator accesses the administration dashboard.
3.  The administrator manages user accounts.
4.  The administrator assigns permissions.
5.  The administrator monitors platform activities.

# 17. DATABASE REQUIREMENTS

The backend will require a relational database to store and manage
application information.

The proposed database will contain the following major entities.

## 17.1 Users Table

Stores user account information.

  Field           Description
  --------------- ---------------------------------
  user_id         Unique user identifier
  full_name       User's full name
  email           User's email address
  password_hash   Securely hashed password
  role            Student, staff or administrator
  created_at      Account creation date

## 17.2 Vendors Table

Stores information about participating cafeteria vendors or food service
units.

  Field                 Description
  --------------------- --------------------------
  vendor_id             Unique vendor identifier
  vendor_name           Vendor or unit name
  description           Vendor description
  contact_information   Approved contact details
  status                Active or inactive

## 17.3 Food Items Table

Stores food menu information.

  Field          Description
  -------------- --------------------------
  food_id        Unique food identifier
  vendor_id      Associated vendor
  food_name      Name of the meal
  description    Meal description
  price          Food price
  availability   Available or unavailable
  created_at     Record creation date

## 17.4 Complaints Table

Stores student complaints.

  Field          Description
  -------------- -------------------------------------
  complaint_id   Unique complaint identifier
  user_id        Student who submitted the complaint
  category       Complaint category
  subject        Complaint title
  description    Complaint details
  status         Current complaint status
  created_at     Submission date
  updated_at     Last update date

## 17.5 Feedback Table

Stores student feedback.

  Field         Description
  ------------- --------------------------------
  feedback_id   Unique feedback identifier
  user_id       Student who submitted feedback
  rating        Feedback rating
  comment       Written feedback
  created_at    Submission date

## 17.6 Complaint Responses Table

Stores responses from authorized cafeteria personnel.

  Field           Description
  --------------- ----------------------------
  response_id     Unique response identifier
  complaint_id    Associated complaint
  staff_id        Staff member who responded
  response_text   Response details
  created_at      Response date

## 17.7 Database Relationships

The proposed database relationships are:

-   One user can submit multiple complaints.
-   One user can submit multiple feedback records.
-   One vendor can manage multiple food items.
-   One complaint can have multiple responses.
-   One staff member can respond to multiple complaints.

The database will use primary keys and foreign keys to maintain
relationships and data integrity.

# 18. BACKEND API REQUIREMENTS

The backend will expose RESTful API endpoints to allow the frontend
application to communicate with the database.

The proposed endpoints include:

## 18.1 Authentication Endpoints

  Method   Endpoint             Purpose
  -------- -------------------- -----------------------------------
  POST     /api/auth/register   Register a user
  POST     /api/auth/login      Authenticate a user
  POST     /api/auth/logout     End an authenticated session
  GET      /api/auth/me         Retrieve current user information

## 18.2 Food Menu Endpoints

  Method   Endpoint         Purpose
  -------- ---------------- -------------------------------
  GET      /api/foods       Retrieve food items
  GET      /api/foods/:id   Retrieve a specific food item
  POST     /api/foods       Create a food item
  PUT      /api/foods/:id   Update food information
  DELETE   /api/foods/:id   Remove a food item

## 18.3 Availability Endpoints

  Method   Endpoint                      Purpose
  -------- ----------------------------- --------------------------
  PATCH    /api/foods/:id/availability   Update food availability

## 18.4 Complaint Endpoints

  Method   Endpoint                     Purpose
  -------- ---------------------------- ---------------------------------------
  POST     /api/complaints              Submit a complaint
  GET      /api/complaints              Retrieve authorized complaint records
  GET      /api/complaints/:id          Retrieve a complaint
  PATCH    /api/complaints/:id/status   Update complaint status

## 18.5 Feedback Endpoints

  Method   Endpoint        Purpose
  -------- --------------- --------------------------------------
  POST     /api/feedback   Submit feedback
  GET      /api/feedback   Retrieve authorized feedback records

## 18.6 Response Endpoints

  Method   Endpoint                        Purpose
  -------- ------------------------------- ------------------------------
  POST     /api/complaints/:id/responses   Respond to a complaint
  GET      /api/complaints/:id/responses   Retrieve complaint responses

All endpoints must implement appropriate authentication, authorization
and input validation.

# 19. SECURITY AND ACCESS CONTROL

Security is important because the system will store user information and
service-related records.

The following security measures will be implemented:

1.  Password hashing to protect user credentials.
2.  Authentication to verify user identities.
3.  Role-based access control to restrict system functions.
4.  Input validation to prevent invalid data.
5.  Authorization checks before sensitive operations.
6.  Secure handling of user information.
7.  Protection against common web application vulnerabilities.

### User Permissions

  Function                Student   Staff   Admin
  ----------------------- --------- ------- -------
  View food menu          Yes       Yes     Yes
  Submit feedback         Yes       Yes     Yes
  Submit complaints       Yes       Yes     Yes
  Manage food menu        No        Yes     Yes
  Update availability     No        Yes     Yes
  View all complaints     No        Yes     Yes
  Respond to complaints   No        Yes     Yes
  Manage users            No        No      Yes
  Manage permissions      No        No      Yes

Students should only be able to access their own private complaint
records and related responses.

# 20. ACCEPTANCE CRITERIA

The MVP will be considered acceptable when the following conditions are
satisfied.

### Authentication

-   Users can successfully register.
-   Registered users can log in.
-   Unauthorized users cannot access protected functions.

### Food Management

-   Authorized staff can create food records.
-   Authorized staff can update food information.
-   Students can view available meals and prices.
-   Food availability updates are reflected in the application.

### Complaint Management

-   Students can submit complaints.
-   Complaint records are stored successfully.
-   Authorized staff can view complaints.
-   Staff can respond to complaints.
-   Students can view their complaint statuses.

### Feedback Management

-   Students can submit feedback.
-   Feedback records are stored correctly.
-   Authorized personnel can access feedback records.

### Security

-   Users cannot access functions outside their permissions.
-   Passwords are not stored in plain text.
-   Invalid requests are handled appropriately.

# 21. CONSTRAINTS AND DEPENDENCIES

The successful implementation of the system may depend on:

-   Reliable internet connectivity.
-   Student access to internet-enabled devices.
-   Participation from cafeteria personnel.
-   Accurate food information.
-   Cooperation from relevant university authorities.
-   Access to necessary operational information.
-   Availability of suitable development resources.

The platform will also depend on authorized staff updating food
availability and responding to complaints consistently.

# 22. RISKS AND MITIGATION STRATEGIES

## 22.1 Low User Adoption

Some students may prefer existing methods of accessing cafeteria
information.

**Mitigation:** Keep the platform simple and ensure that it provides
useful information.

## 22.2 Inaccurate Food Information

Food availability or prices may become outdated.

**Mitigation:** Allow authorized staff to update information easily and
regularly.

## 22.3 Delayed Complaint Responses

Complaints may not receive timely responses.

**Mitigation:** Provide a centralized complaint dashboard and clear
status tracking.

## 22.4 Internet Connectivity Problems

Users may experience difficulties accessing the platform.

**Mitigation:** Build a lightweight application and handle network
failures appropriately.

## 22.5 Security Risks

Unauthorized users may attempt to access restricted information.

**Mitigation:** Implement secure authentication, authorization and input
validation.

## 22.6 Limited Staff Participation

Cafeteria personnel may not consistently use the system.

**Mitigation:** Provide simple management tools and basic user training.

# 23. SUCCESS METRICS

The success of the platform will be measured using the following
indicators:

1.  Number of registered students.
2.  Number of participating cafeteria vendors or units.
3.  Number of food items successfully managed.
4.  Number of complaints submitted.
5.  Percentage of complaints receiving responses.
6.  Average complaint response time.
7.  Number of active users.
8.  Student satisfaction with the platform.

These metrics will help determine whether the system improves
information accessibility and complaint management.

# 24. FUTURE IMPROVEMENTS

Future versions may introduce:

-   Online food ordering.
-   Digital payment integration.
-   Order status notifications.
-   Automated complaint notifications.
-   Food availability alerts.
-   Advanced service analytics.
-   Student satisfaction reports.
-   Mobile application support.
-   Queue monitoring.
-   Integration with other university services.

These features will only be considered after evaluating the MVP and
collecting user feedback.

# 25. CONCLUSION

The Babcock University Cafeteria Lane Service Management System is a
proposed technology-based solution designed to improve information
accessibility, communication and service feedback management within the
university cafeteria environment.

Existing research involving Babcock University students has identified
areas of dissatisfaction relating to food services, customer experience
and complaint handling.

The proposed platform will provide a centralized environment where
students can access food information, submit feedback and monitor
complaints, while authorized personnel can manage food information and
respond to student concerns.

The project will begin with research and problem validation before
proceeding to system design and development.

The initial version will focus on essential features that address the
identified information and communication needs.

The long-term objective is to provide a reliable, accessible and
maintainable system that supports continuous improvement of the Babcock
University cafeteria experience.

# 26. REFERENCES

1.  Okwudishu, O., Okebalama, V. C., Bamidele, E. I., Osinaike, A.,
    Obinna, C., Adefala, N., Omokore, O., Abaenowa, C., Odeyinka, A.,
    Uchechukwu, N., Omotoso, E., and Enyinnaya, V. (2026). *Perception
    and behaviour of undergraduate students to on-campus food operations
    in a tertiary Nigerian institution in southwest Nigeria: A
    cross-sectional study.* Babcock University Medical Journal, 9(1),
    185--195. https://doi.org/10.38029/babcockuniv.med.j.v9i1.665

2.  Babcock University. *Catering and Food Services.*
    https://www.babcock.edu.ng/food-services

3.  Babcock University. *Cafeteria / Dining Hours.*
    https://www.babcock.edu.ng/food-services/cafe-hours
