PRODUCT REQUIREMENTS DOCUMENT (PRD)
Project Title
Campus Food Queue & Pre-order System
Course
BU-209 Backend Engineering
Document Type
Product Requirements Document (PRD)
Version
Version 1.0 — Draft
________________________________________
1. Executive Summary
The Campus Food Queue & Pre-order System is a proposed digital platform designed to investigate and potentially address challenges associated with purchasing food from campus vendors, particularly during busy periods.
Students may experience delays when purchasing food, especially during periods of high demand. Such delays may affect their schedules, convenience and overall food-purchasing experience. Food vendors may also face difficulties managing multiple customer orders during busy periods.
The proposed system will allow students to view available food menus, place orders in advance and monitor the progress of their orders. Vendors will be able to receive orders digitally, manage incoming orders and update order statuses to inform students when meals are ready for collection.
The system will initially focus on essential ordering and order-management functionality. Its proposed effectiveness will need to be evaluated through actual research, testing and feedback from students and food vendors.
The purpose of this Product Requirements Document is to define the problem under investigation, proposed solution, system requirements, user expectations, technical considerations, scope, risks and development approach before implementation begins.
________________________________________
2. Document Purpose
This document provides a structured description of the proposed Campus Food Queue & Pre-order System.
It outlines the problem being investigated, target users, proposed system functionalities, technical requirements, system workflows, research methodology, potential risks and development approach.
The document will serve as a reference during system design, development, testing and evaluation.
________________________________________
3. Problem Statement
Purchasing food from campus vendors may involve waiting in queues, particularly during periods of high demand. Students may have limited time between lectures and other academic activities, making delays in food purchasing inconvenient.
Traditional food-ordering processes may also require students to physically visit vendors, wait to place orders and remain at the food stall while meals are prepared.
However, the extent to which these challenges occur within the target campus environment has not yet been established through actual field research.
This project therefore investigates the potential challenges associated with campus food purchasing and proposes a digital food-ordering and order-management system as a possible solution.
________________________________________
4. Project Objectives
The objectives of the proposed project are:
1.	To investigate potential challenges associated with purchasing food from campus vendors.
2.	To examine existing food-ordering solutions and their capabilities.
3.	To identify the needs of students and campus food vendors.
4.	To propose a digital platform for advance food ordering and order management.
5.	To define the functional and non-functional requirements of the proposed system.
6.	To establish a preliminary technical architecture and database structure.
7.	To develop a minimum viable product that can be tested and evaluated.
8.	To evaluate the system's usability, reliability and potential effectiveness.
Existing Solutions Research
Two existing food-ordering platforms were examined: Chowdeck and Glovo.
Chowdeck provides users with access to restaurant menus, online ordering, scheduled orders, pickup options, order notifications and delivery tracking. Its services demonstrate that customers can order meals online and collect them or receive delivery.
Glovo also provides food ordering and pickup options. Customers can place orders through the platform and collect their purchases directly from participating merchants.
The review of these platforms shows that online ordering and pickup are already established solutions. Therefore, the proposed campus system should not simply replicate existing food delivery applications.
Further investigation is needed to determine whether campus food vendors and students experience specific challenges that are not adequately addressed by existing general-purpose platforms. These may include order handling during peak periods, communication about food readiness, vendor workflow and convenient collection within the university environment.
Note: This review is based on publicly available platform information. The simulated student responses used earlier are not actual field research.
Preliminary Gap Analysis
The review of existing food-ordering platforms shows that online ordering, digital menus, pickup options and order tracking are already available in the food delivery industry.
However, the specific needs of students and food vendors within a university campus environment may differ from those of general food delivery customers.
The potential gaps identified for further investigation include:
1.	The availability of digital ordering systems among campus food vendors.
2.	The convenience of ordering food and collecting it within the university campus.
3.	Communication between vendors and students regarding order readiness.
4.	The management of multiple food orders during busy periods.
5.	Access to updated menus and food availability.
These potential gaps will guide further investigation before the project scope and proposed solution are finalized.
Proposed Solution
The proposed solution is a Campus Food Queue & Pre-order System designed to improve the process of purchasing food from vendors within a university campus.
The system will allow students to view participating food vendors, browse available menus, check meal prices, place orders in advance and receive updates on their order status.
Food vendors will have access to an interface through which they can view incoming orders, manage order requests and update the status of meals as they progress from preparation to collection.
The system is intended to reduce unnecessary physical waiting, improve communication between students and food vendors, and help vendors manage orders more efficiently during busy periods.
The proposed system will be evaluated against the problems identified during the research process before its features and implementation requirements are finalized.
MVP Scope
The proposed Campus Food Queue & Pre-order System will initially focus on providing students with a convenient way to order food from participating campus vendors before arriving at the food stall.
The MVP will focus on the essential functionalities required to support ordering and food collection.
Core MVP Features
1.	Vendor Menu Display: Students can view available meals, prices and food availability.
2.	Order Placement: Students can select meals and submit their orders.
3.	Order Status: Students can see whether their order is pending, being prepared or ready for collection.
4.	Order Identification: Each order will have a unique order number for identification during collection.
5.	Vendor Order Management: Vendors can view incoming orders and update their order statuses.
6.	Pickup: Students collect their meals directly from the participating vendor.
Features Excluded from the Initial MVP
The following features will not be included in the initial version:
•	Delivery services.
•	Complex payment integrations.
•	Loyalty points and rewards.
•	AI-powered recommendations.
•	Multiple campuses.
•	Advanced analytics.
MVP Goal
The goal of the MVP is to determine whether advance ordering and improved order communication can help students conveniently purchase food and improve how campus food vendors handle orders during busy periods.
Functional Requirements
The Campus Food Queue & Pre-order System is expected to provide the following functionalities:
FR-01: Student Registration
The system should allow students to create accounts using their basic information.
FR-02: Vendor Menu Management
Vendors should be able to add meals, edit prices, and update meal availability.
FR-03: Menu Viewing
Students should be able to view food items, prices and availability.
FR-04: Order Placement
Students should be able to select food items, specify quantities and submit orders.
FR-05: Order Management
Vendors should be able to view incoming orders and manage them.
FR-06: Order Status Updates
Vendors should be able to update orders to Pending, Preparing, and Ready for Pickup.
FR-07: Order Identification
The system should generate a unique order reference for each submitted order.
FR-08: Order History
Students should be able to view their previous orders.
FR-09: Order Cancellation
Students should be able to cancel an order before preparation begins, subject to the system's cancellation rules.
FR-10: Order Notifications
Students should receive notifications when their orders are ready for pickup.
Non-Functional Requirements
NFR-01: Performance
The system should load menus and display order information within a reasonable time under normal usage conditions.
NFR-02: Security
The system should protect student and vendor account information against unauthorized access.
NFR-03: Usability
The system should have a simple and understandable interface that students and vendors can use without extensive training.
NFR-04: Availability
The system should remain accessible during normal campus food purchasing hours, subject to maintenance and internet availability.
NFR-05: Reliability
The system should accurately record orders and their status changes without losing essential order information.
NFR-06: Scalability
The system should be designed so that additional vendors and users can be accommodated as usage increases.
NFR-07: Maintainability
The system should be structured so that developers can fix bugs, update features and maintain the system efficiently.
NFR-08: Data Integrity
The system should ensure that order details, quantities, prices and order statuses remain consistent throughout the ordering process.
System Workflow
Student Workflow
The student begins by logging into the system and viewing the available food vendors. After selecting a vendor, the student browses the available menu, selects the desired food items and quantities, and submits the order.
The system records the order and generates a unique order reference. The vendor receives the order and begins processing it. The student can monitor the order status while the food is being prepared. Once the vendor marks the order as ready, the student receives a notification and proceeds to collect the food.
Vendor Workflow
The vendor logs into the system and views incoming student orders. The vendor reviews the order details, confirms the order and begins preparation.
After preparing the meal, the vendor updates the order status to Ready for Pickup. The student is then notified and can collect the order using the generated order reference.
Order Lifecycle
The proposed order lifecycle consists of the following statuses:
1.	Pending
2.	Confirmed
3.	Preparing
4.	Ready for Pickup
5.	Completed
An order may also be Cancelled where cancellation is permitted.
12. System Architecture (Proposed)
The proposed system will use a client-server architecture. Students and food vendors will interact with the system through a user interface, while the backend will process requests, manage orders, validate information and communicate with the database.
The system will consist of three primary components:
12.1 Frontend
The frontend will provide the interface through which students and vendors interact with the system. Students will use it to browse menus, place orders and check order status. Vendors will use it to manage menus and incoming orders.
12.2 Backend
The backend will handle the application's business logic. It will manage user authentication, order creation, order processing, menu management, order status updates and communication between the frontend and database.
12.3 Database
The database will store student accounts, vendor information, food menus, orders, order items and order status records.
________________________________________
13. Database Requirements (Proposed)
The system will require a database to store and organize the information needed to operate.
The following entities are proposed:
13.1 Users
Stores student account information.
•	User ID
•	Full name
•	Email
•	Password
•	Registration date
13.2 Vendors
Stores information about participating food vendors.
•	Vendor ID
•	Vendor name
•	Location
•	Contact information
•	Account details
13.3 Menu Items
Stores information about meals offered by vendors.
•	Item ID
•	Vendor ID
•	Food name
•	Description
•	Price
•	Availability
13.4 Orders
Stores information about orders placed by students.
•	Order ID
•	User ID
•	Vendor ID
•	Order reference
•	Total amount
•	Order status
•	Order date
13.5 Order Items
Stores individual food items associated with an order.
•	Order Item ID
•	Order ID
•	Menu Item ID
•	Quantity
•	Price per item
The proposed database structure will allow the system to organize orders, users, vendors and food items efficiently.
________________________________________
14. Backend Processing Requirements
The backend will be responsible for processing requests received from the frontend and enforcing the system's business rules.
The backend is expected to:
1.	Authenticate students and vendors.
2.	Validate incoming order information.
3.	Confirm that food items are available before an order is accepted.
4.	Calculate the total cost of an order.
5.	Generate unique order references.
6.	Store orders and their associated items.
7.	Allow vendors to update order statuses.
8.	Ensure that only authorized users can access appropriate information.
9.	Retrieve order information when requested.
10.	Manage cancellations according to the system's rules.
________________________________________
15. Business Rules
The system will operate according to the following rules:
1.	Students must have an account to place orders.
2.	Vendors must be registered and authorized to manage their menus.
3.	Students may only order items that are currently available.
4.	Each order must have a unique order reference.
5.	An order must belong to a student and a specific vendor.
6.	Vendors may only manage orders assigned to their accounts.
7.	Vendors must update order statuses as orders progress.
8.	Students may cancel orders only when cancellation is permitted.
9.	An order marked as Completed should not be processed again.
10.	The system must maintain accurate order and pricing information.
________________________________________
16. API Requirements (Proposed)
The backend will expose API endpoints through which the frontend can communicate with the system.
The following endpoints are proposed for the initial version.
User Endpoints
•	POST /api/register — Register a user.
•	POST /api/login — Authenticate a user.
•	GET /api/profile — Retrieve the authenticated user's profile.
Vendor Endpoints
•	GET /api/vendors — Retrieve available vendors.
•	GET /api/vendors/{id} — Retrieve information about a specific vendor.
•	GET /api/vendors/{id}/menu — Retrieve a vendor's menu.
Menu Endpoints
•	POST /api/menu — Add a food item.
•	PUT /api/menu/{id} — Update a food item.
•	DELETE /api/menu/{id} — Remove a food item.
Order Endpoints
•	POST /api/orders — Create a new order.
•	GET /api/orders — Retrieve orders belonging to the authenticated user.
•	GET /api/orders/{id} — Retrieve details of a specific order.
•	PUT /api/orders/{id}/status — Update an order status.
•	PUT /api/orders/{id}/cancel — Cancel an order where permitted.
These endpoints are preliminary proposals. Their exact implementation and authorization rules will be determined during technical design.
________________________________________
17. Security Considerations
Security will be an important part of the proposed system because it will store student accounts and order information.
The system should:
1.	Protect passwords using secure hashing rather than storing plain-text passwords.
2.	Authenticate users before granting access to protected features.
3.	Restrict vendor access to their own orders and menu management.
4.	Prevent students from accessing other students' private order information.
5.	Validate user input to reduce the risk of malicious or invalid requests.
6.	Use secure communication channels when transmitting sensitive information.
7.	Protect the database against unauthorized access.
8.	Limit access to administrative functions.
________________________________________
18. Risks and Challenges
The project may face several challenges during implementation and deployment.
18.1 Vendor Adoption
Some campus food vendors may not be willing or able to use a digital ordering system.
18.2 Internet Connectivity
Poor internet connectivity may prevent students or vendors from accessing the system.
18.3 Incorrect Order Information
Students may submit incorrect quantities or orders, leading to misunderstandings during collection.
18.4 Food Availability
Meals may become unavailable after students have placed their orders.
18.5 Order Overload
Vendors may receive too many orders simultaneously, especially during lunch periods.
18.6 User Trust
Students may hesitate to use a new system if they are uncertain about whether their orders will be processed correctly.
18.7 Notification Failures
Students may not receive notifications promptly if connectivity or notification services fail.
________________________________________
19. Proposed Risk Mitigation
The following measures may help reduce the identified risks:
1.	Provide vendors with a simple interface that requires minimal training.
2.	Make the system accessible through mobile-friendly web pages.
3.	Allow vendors to update meal availability regularly.
4.	Provide clear order references for identification.
5.	Allow vendors to manage order volumes and processing times.
6.	Provide clear order status information.
7.	Ensure the system can display order information when users refresh the page if notifications fail.
8.	Test the system with a small number of vendors and students before wider deployment.
________________________________________
20. Testing Strategy (Proposed)
Testing will be required to determine whether the system behaves as expected.
20.1 Functional Testing
Tests will confirm whether the system's functions, such as registration, menu viewing, order placement and order status updates, work correctly.
20.2 Validation Testing
Tests will confirm that invalid inputs, unavailable food items and incomplete order information are handled correctly.
20.3 Security Testing
Tests will examine authentication, authorization and access restrictions.
20.4 Performance Testing
Tests will examine the system's response time under different levels of usage.
20.5 Usability Testing
Students and vendors will be asked to interact with the system to identify usability problems.
20.6 Integration Testing
Tests will confirm whether the frontend, backend and database work together correctly.
________________________________________
21. Success Metrics
The success of the system will be evaluated using the following measurable indicators:
1.	Reduction in the average time students spend waiting to collect food.
2.	Number of successfully completed orders.
3.	Percentage of orders collected successfully.
4.	Number of participating vendors.
5.	Percentage of orders completed within the estimated preparation time.
6.	User satisfaction based on feedback.
7.	Number of cancelled or failed orders.
These metrics will be used to evaluate the effectiveness of the system after implementation and testing.
________________________________________
22. Implementation Approach
The project will be developed incrementally to allow the system to be tested as features are introduced.
Phase 1: Technical Planning
Define the database structure, API requirements, backend logic and system architecture.
Phase 2: User Authentication
Implement registration, login and authentication.
Phase 3: Vendor and Menu Management
Implement vendor information and food menu management.
Phase 4: Order Processing
Implement order creation, order items, order references and order management.
Phase 5: Order Status Management
Implement order status updates and student order tracking.
Phase 6: Testing
Test the system's functionality, security, performance and usability.
Phase 7: Pilot Deployment
Deploy the system for a small group of participating campus vendors and students to evaluate its effectiveness.
________________________________________
23. Preliminary Conclusion
The Campus Food Queue & Pre-order System is a proposed solution to the potential challenges associated with purchasing food from campus vendors during busy periods.
The project aims to provide a convenient method for students to place food orders in advance and collect their meals when ready, while giving vendors a simple way to receive, organize and manage orders.
The proposed system will consist of a frontend, backend and database. The backend will manage authentication, order processing, menu management, order status updates and data validation.
Before implementation, the proposed system will require further validation through actual student and vendor research. The initial survey findings presented earlier in this project were simulated for exploratory analysis and should not be treated as actual field research.
The system will be developed incrementally, beginning with its essential features and expanding based on testing, feedback and practical requirements.
24. Requirements Prioritization
Requirements prioritization is the process of identifying which system features are most important to users and which should be implemented first.
The proposed Campus Food Queue & Pre-order System will use the MoSCoW prioritization method to classify its requirements.
24.1 Must Have
These features are essential for the system to function.
•	Student registration and login.
•	Vendor login.
•	Viewing available vendors.
•	Viewing menus and prices.
•	Placing food orders.
•	Generating unique order references.
•	Vendors viewing incoming orders.
•	Vendors updating order statuses.
•	Students viewing their order status.
24.2 Should Have
These features are important but may be introduced after the core functionality.
•	Order cancellation where permitted.
•	Order history.
•	Notifications when orders are ready.
•	Vendors updating food availability.
•	Basic vendor order management improvements.
24.3 Could Have
These features may be added if time and resources permit.
•	Student ratings and feedback.
•	Estimated food preparation times.
•	Search and filtering of food menus.
•	Basic vendor sales summaries.
24.4 Won't Have in the Initial Version
These features are excluded from the initial MVP scope.
•	Food delivery.
•	AI-powered meal recommendations.
•	Loyalty and reward programmes.
•	Multi-campus support.
•	Advanced analytics.
•	Complex payment integrations.
These features may be reconsidered in future versions.
24.5 Prioritization Summary
The initial development effort will focus on the features required to enable students to place orders and vendors to process those orders successfully.
Additional features will be introduced based on user feedback, available resources and the results of initial testing.
25. Research Methodology
25.1 Research Approach
The research will use a combination of quantitative and qualitative methods to investigate the challenges students experience when purchasing food from campus vendors.
Quantitative research will help identify patterns in waiting times, purchasing frequency and student preferences. Qualitative research will help explore students' experiences, opinions and suggestions for improving food purchasing on campus.
25.2 Data Collection Methods
The proposed research methods include:
•	Questionnaires: Students will be asked questions about their food purchasing habits, waiting times, queue-related challenges and preferences.
•	Interviews: Short interviews with students and food vendors may help provide a deeper understanding of the problem.
•	Observation: Observing food vendor queues during busy periods may help identify waiting patterns, congestion and order-processing challenges.
•	Secondary Research: Existing food-ordering platforms and relevant articles, reports and research materials will be examined to understand current solutions and identify areas requiring further investigation.
25.3 Target Participants
The primary research participants will be students who regularly purchase food from campus vendors.
Food vendors will also be considered as potential research participants because they are responsible for preparing meals, handling customer orders and managing service during busy periods.
25.4 Data Analysis
Questionnaire responses will be analyzed using basic descriptive statistics, including percentages, frequencies and comparisons between responses.
Interview responses and observations will be examined to identify recurring problems, experiences and suggestions.
The findings will be used to guide the proposed system's requirements and scope.
25.5 Research Limitations
Potential limitations include limited access to students and vendors, insufficient responses, time constraints and the possibility that participants may provide inaccurate or incomplete information.
The initial survey analysis presented in this project is simulated and does not represent actual responses collected from students. Actual data collection and validation will be necessary before drawing definitive conclusions about the campus food purchasing problem.
26. User Stories and Use Cases
User stories describe the system's functionality from the perspective of the people who will use it. They help ensure that the system is designed around actual user needs.
26.1 Student User Stories
US-01: View Food Menus
As a student, I want to view available food menus and prices so that I can decide what to buy before visiting a vendor.
US-02: Place an Order
As a student, I want to select meals and quantities and submit my order so that I can arrange my food purchase in advance.
US-03: Track an Order
As a student, I want to see the status of my order so that I know whether it is being prepared or ready for collection.
US-04: Receive Order Notifications
As a student, I want to receive notifications when my food is ready so that I can collect it without repeatedly checking with the vendor.
US-05: View Order History
As a student, I want to view my previous orders so that I can keep track of my purchases.
26.2 Vendor User Stories
US-06: Manage Menus
As a vendor, I want to add, edit and remove menu items so that students can see the food I offer.
US-07: Manage Food Availability
As a vendor, I want to update food availability so that students do not order meals that are no longer available.
US-08: View Incoming Orders
As a vendor, I want to view incoming orders so that I can prepare meals based on student requests.
US-09: Update Order Status
As a vendor, I want to update order statuses so that students know the progress of their orders.
US-10: Identify Orders
As a vendor, I want each order to have a unique reference so that I can identify and hand over the correct food to the correct student.
26.3 Use Case: Placing an Order
Actor: Student
Description: The student places an order from a selected food vendor.
Preconditions:
•	The student has an account.
•	The student is logged in.
•	The vendor has available food items.
Main Flow:
1.	The student opens the system.
2.	The student selects a vendor.
3.	The student views the vendor's menu.
4.	The student selects food items and quantities.
5.	The student reviews the order.
6.	The student submits the order.
7.	The system validates the order.
8.	The system records the order.
9.	The system generates an order reference.
10.	The vendor receives the order.
Postcondition: The order is recorded and available for the vendor to process.
26.4 Use Case: Processing an Order
Actor: Food Vendor
Description: The vendor receives and processes a student's order.
Preconditions:
•	The vendor is authenticated.
•	A valid order has been submitted.
Main Flow:
1.	The vendor views incoming orders.
2.	The vendor selects an order.
3.	The vendor confirms the order.
4.	The vendor begins preparing the food.
5.	The vendor updates the order status.
6.	The vendor marks the order as Ready for Pickup.
7.	The student receives a notification.
8.	The student collects the order.
Postcondition: The order is ready for collection and can subsequently be marked as completed.
27. Acceptance Criteria
Acceptance criteria are conditions that a system feature must satisfy before it can be considered complete and functioning correctly.
27.1 Student Registration and Login
•	Students should be able to register using valid information.
•	The system should reject invalid or incomplete registration information.
•	Registered students should be able to log in using their credentials.
•	Unauthorized users should not be able to access protected features.
27.2 Vendor Menu Management
•	Vendors should be able to add new food items.
•	Vendors should be able to edit food item information.
•	Vendors should be able to update food availability.
•	Changes made to the menu should be reflected when students view it.
27.3 Order Placement
•	Students should be able to select food items and quantities.
•	The system should calculate the total order amount correctly.
•	The system should reject orders containing unavailable food items.
•	The system should generate a unique order reference after a successful order submission.
•	The system should store the order correctly.
27.4 Order Management
•	Vendors should be able to view orders assigned to them.
•	Vendors should be able to confirm incoming orders.
•	Vendors should be able to update order statuses.
•	The system should prevent unauthorized users from modifying orders.
27.5 Order Tracking
•	Students should be able to view their order statuses.
•	Order status changes should be reflected accurately.
•	Students should be notified when their orders are ready for collection.
27.6 Order Cancellation
•	Students should be able to cancel orders when cancellation is permitted.
•	The system should prevent cancellation when the order has reached a stage where cancellation is no longer permitted.
•	Cancelled orders should be clearly identified in the system.
28. Assumptions and Dependencies
28.1 Assumptions
The project is based on the following assumptions:
1.	Students regularly purchase food from campus vendors.
2.	Some students experience delays when purchasing food during busy periods.
3.	Participating food vendors will be willing to receive and process digital orders.
4.	Students and vendors will have access to internet-enabled devices.
5.	Vendors will be able to update food availability and order statuses.
6.	Students will be willing to use a digital system if it provides a convenient ordering experience.
These assumptions must be validated through actual research before implementation.
28.2 Dependencies
The system may depend on the following:
1.	Internet connectivity.
2.	A reliable database service.
3.	Authentication services.
4.	A notification service.
5.	Participation from campus food vendors.
6.	Access to devices capable of using the system.
7.	Availability of accurate menu information.
________________________________________
29. Scope and Scope Limitations
29.1 Project Scope
The initial system will focus on helping students place food orders before arriving at campus food vendors and allowing vendors to manage those orders.
The proposed system will include:
•	Student registration and authentication.
•	Vendor authentication.
•	Vendor menu management.
•	Food availability management.
•	Food ordering.
•	Order references.
•	Order status management.
•	Order tracking.
•	Order collection.
•	Basic order history.
29.2 Scope Limitations
The initial version will not include:
•	Food delivery.
•	Multi-campus operations.
•	AI-powered recommendations.
•	Loyalty programmes.
•	Advanced business analytics.
•	Complex payment processing.
•	Automated inventory management.
These limitations will help keep the initial development focused on the main problem being investigated.
________________________________________
30. Project Stakeholders
The stakeholders identified for the proposed system include:
30.1 Students
Students are the primary users of the system. They will use the platform to view menus, place orders and monitor order statuses.
30.2 Food Vendors
Food vendors will use the system to manage menus, receive orders, prepare meals and update order statuses.
30.3 System Administrator
The administrator will be responsible for managing user accounts, overseeing vendor registrations, monitoring system activities and resolving operational issues.
30.4 Project Developer
The developer will be responsible for planning, designing, implementing, testing, maintaining and improving the system.
________________________________________
31. Estimated Development Phases
The proposed project will be developed in stages.
Phase 1: Planning and Requirements
Define the problem, investigate user needs, document requirements and establish the system scope.
Phase 2: System Design
Design the database structure, system architecture, user interfaces and API structure.
Phase 3: Backend Development
Develop authentication, database operations, order processing, menu management and order status functionality.
Phase 4: Frontend Development
Develop the interfaces through which students and vendors will interact with the system.
Phase 5: Integration
Connect the frontend, backend and database and ensure that the components communicate correctly.
Phase 6: Testing
Perform functional, security, integration, usability and performance testing.
Phase 7: Deployment
Deploy the system to an environment where selected students and vendors can access it.
Phase 8: Evaluation
Collect user feedback, assess system performance and identify improvements.
________________________________________
32. Preliminary Technical Investigation
Before selecting a programming language or development framework, the technical requirements of the proposed system must be examined.
The system is expected to support user authentication, data storage, menu management, order processing, API communication and order status updates.
A client-server architecture is proposed because it allows the user interface to communicate with a backend service responsible for processing requests and managing data.
The backend will require mechanisms for:
•	Authentication and authorization.
•	Database communication.
•	Input validation.
•	Order processing.
•	Data retrieval and storage.
•	Error handling.
•	API communication.
The database will need to support relationships between users, vendors, menu items, orders and order items.
The technical investigation will help determine which programming languages, frameworks, database technologies and deployment services are suitable for the project.
No final technology selection has been made at this stage.
________________________________________
33. Potential Future Improvements
Future versions of the system may include:
1.	Online payment integration.
2.	Estimated preparation times.
3.	Food delivery options.
4.	Student reviews and ratings.
5.	Vendor sales reports.
6.	Automated inventory management.
7.	Meal recommendations.
8.	Multiple campus support.
9.	Push notifications.
10.	Improved order scheduling.
These features may be introduced based on feedback, system performance, available resources and the needs of users.
________________________________________
34. Research Limitations
The initial research process has limitations.
The survey responses and numerical analysis previously presented were simulated and were not obtained from actual student participants. Consequently, the figures cannot be used as verified evidence of the frequency or severity of food purchasing delays on campus.
The preliminary review of existing food-ordering platforms was also limited and did not establish whether campus vendors currently use similar systems or whether students experience specific shortcomings when using existing platforms.
Further investigation through actual student questionnaires, vendor interviews, observation of food queues and more detailed research into existing solutions will be necessary.
These limitations will be considered when interpreting the proposed system's requirements and expected benefits.
________________________________________
35. Preliminary Project Conclusion
The Campus Food Queue & Pre-order System is a proposed digital solution intended to investigate and potentially address challenges associated with purchasing food from campus vendors during busy periods.
The system is designed to allow students to browse food menus, place orders in advance and monitor order statuses while vendors receive and manage incoming orders.
The proposed solution will consist of a frontend, backend and database. The backend will handle authentication, data validation, menu management, order processing and order status updates.
The initial MVP will focus on the essential features required for students to place orders and for vendors to manage and process those orders.
However, the problem, its severity and the proposed solution's effectiveness must be validated through actual research before implementation.
The project will proceed through planning, technical design, development, testing, deployment and evaluation.
The ultimate goal is to investigate whether a campus-focused digital ordering system can improve the food purchasing experience for students and assist food vendors in managing orders more efficiently.
36. Literature Review
36.1 Design and Implementation of a Web-Based Food Ordering Platform for Academic Environments
Nwekori and Ogbaga (2025) investigated food-ordering inefficiencies within an academic environment at Ebonyi State University, Abakaliki, Nigeria. Their study examined challenges associated with traditional food-ordering processes, including waiting times, incorrect orders and operational difficulties.
The researchers collected information through interviews involving 12 food vendors and 40 student consumers. They subsequently developed a web-based food-ordering platform using the Rapid Application Development methodology.
The study reported improvements in order-processing time and order accuracy, alongside positive usability results.
This research is relevant to the proposed Campus Food Queue & Pre-order System because it demonstrates the application of digital food ordering within a Nigerian university environment. However, it also indicates that similar systems have already been investigated, making it necessary to identify the specific needs and requirements of the intended campus environment.
36.2 Improving Campus Dining Operations Using Capacity and Queue Management
Kambli, Sinha and Srinivas (2020) investigated queue-management challenges in a campus dining facility using simulation techniques.
Their study examined how service capacity and queue-management strategies could improve dining operations. The simulation results suggested that combining queue-management approaches with capacity reallocation could reduce waiting times within the facility studied.
This research is relevant because it demonstrates that queue-related problems in campus dining environments can be investigated through operational analysis and simulation. It also suggests that the proposed system should consider order management and service capacity rather than focusing solely on online ordering.
36.3 Impact of Waiting Time on Evaluation of Service Quality and Customer Satisfaction in Foodservice Operations
Lee (2000) investigated the relationship between waiting time, service quality and customer satisfaction in foodservice operations.
The study examined customers' perceptions of waiting time and service quality within a university cafeteria environment. Its findings indicated that waiting time was related to customers' evaluations of service quality.
This research is relevant because it provides a basis for investigating whether waiting times affect the food-purchasing experience of students and whether improving order management could contribute to a better customer experience.
36.4 Summary of the Literature
The reviewed studies indicate that food-ordering processes, waiting times, queue management and customer satisfaction have been investigated in academic and foodservice environments.
The Nigerian university study demonstrates the potential application of digital ordering systems to university food services, while the campus dining simulation study highlights the importance of queue management and service capacity. The foodservice customer-satisfaction study provides additional context for investigating the relationship between waiting times and customer perceptions.
These studies provide a foundation for further investigation into the food-purchasing experiences of students and the operational needs of campus food vendors.
However, the reviewed literature does not establish the specific nature, frequency or severity of food-purchasing challenges at the campus targeted by this project. Further research will therefore be required to validate the problem and identify the requirements of the intended users.
References to add to your bibliography
1.	Nwekori, F. E., & Ogbaga, I. N. (2025). Design and implementation of a web-based food ordering platform for academic environments. Journal of Digital Food, Energy & Water Systems, 6(2). DOI: 10.36615/918nh382. doaj.org
2.	Kambli, A., Sinha, A. A., & Srinivas, S. (2020). Improving campus dining operations using capacity and queue management: A simulation-based case study. Journal of Hospitality and Tourism Management. ScienceDirect
3.	Lee, W. (2000). Impact of waiting time on evaluation of service quality and customer satisfaction in foodservice operations. Foodservice Research International, 12, 241–254. DOI: 10.1111/j.1745-4506.2000.tb00021.x. DOI
37. Evidence-Based Problem Validation
37.1 Purpose
The purpose of problem validation is to determine whether students experience significant challenges when purchasing food from campus vendors and whether these challenges justify the development of a digital ordering system.
Although existing research has investigated food-ordering challenges and waiting times in academic environments, the extent to which these problems occur within the target campus environment remains unverified.
37.2 Evidence Currently Available
The preliminary literature review identified research relating to food-ordering inefficiencies, waiting times, queue management and digital ordering systems in academic environments.
The reviewed literature provides a basis for investigating the proposed problem. However, findings from other institutions cannot automatically be applied to the target campus.
The initial survey analysis conducted during project planning was simulated and is not considered empirical evidence.
37.3 Questions That Require Validation
The following questions will guide further investigation:
1.	Do students experience long waiting times when purchasing food from campus vendors?
2.	During which periods are food queues most congested?
3.	How frequently do students abandon queues?
4.	Do food-purchasing delays affect students' academic schedules or other activities?
5.	Do campus vendors experience difficulties managing customer orders during busy periods?
6.	Do vendors currently use any digital tools to receive or manage orders?
7.	Would students and vendors be willing to use a campus-focused digital ordering system?
8.	What features would students and vendors consider most useful?
37.4 Validation Methods
The problem will be investigated using the following methods:
•	Student questionnaires to identify purchasing habits, waiting times and challenges.
•	Vendor interviews to understand order-processing methods and operational difficulties.
•	Observation of food queues during busy periods.
•	Examination of existing food-ordering methods used within the campus environment.
37.5 Validation Criteria
The problem will be considered worthy of further investigation if actual research identifies recurring food-purchasing delays, queue-management challenges or difficulties that students and vendors believe could be improved.
The proposed solution will also need to be evaluated to determine whether it addresses the identified problems effectively.
The validation process will help prevent the development of a system based solely on assumptions.

