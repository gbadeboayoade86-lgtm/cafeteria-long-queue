# PRODUCT REQUIREMENTS DOCUMENT (PRD)

## Campus Food Queue & Pre-order System

**Course:** BU-209 Backend Engineering  
**Assignment:** Week 4 — Product Requirements Document (PRD)  
**Project Name:** Campus Food Queue & Pre-order System  
**Project Type:** Web-Based Food Pre-order and Order Tracking System  
**Project Stage:** Prototype Development  
**Author:** Osungade John Olamilekan  
**Institution:** Babcock University  
**Date:** November 2026

---

# 1. EXECUTIVE SUMMARY

The Campus Food Queue & Pre-order System is a web-based platform designed to help students order food from campus food vendors before arriving at the vendor's location.

Students frequently experience delays when purchasing food due to queues, limited time between lectures, crowded food outlets, and uncertainty about whether certain meals are available. These challenges may make it difficult for students to manage their time effectively during busy academic periods.

The proposed system allows students to view food vendors, browse available meals, place food orders, and track the status of their orders using an order reference number.

Food vendors or administrators can also manage orders by updating their status as orders progress from pending to preparation and pickup.

The project aims to improve convenience, reduce unnecessary waiting, and provide a more organized process for ordering food on campus.

The initial implementation is a prototype intended to demonstrate the core functionalities of the proposed system.

---

# 2. PROBLEM STATEMENT

Students within university campuses often experience difficulties when purchasing food from campus food vendors.

During busy periods, students may encounter long queues, delays in food preparation, limited time between lectures, and uncertainty about available food items.

These challenges may result in students spending excessive time waiting for meals instead of attending lectures, completing academic tasks, or participating in other activities.

Traditional food ordering methods usually require students to physically visit food vendors before making their selections and placing their orders.

There is a need for a simple digital solution that allows students to view available meals, place orders in advance, and monitor the progress of their orders.

---

# 3. PROBLEM HYPOTHESIS

If students are provided with a simple web-based platform through which they can browse meals, place food orders in advance, and track order progress, then the amount of unnecessary waiting and uncertainty associated with purchasing food on campus may be reduced.

The system may also help food vendors organize incoming orders and improve the overall ordering experience.

This hypothesis will require further validation through actual student and vendor feedback.

---

# 4. TARGET USERS

## 4.1 Primary Users: Students

Students are the primary users of the system.

They need a convenient way to:

- View available food vendors.
- Browse food menus.
- Check food availability.
- Place food orders.
- Specify order quantities.
- Receive order reference numbers.
- Track order progress.
- Access order information without physically visiting the vendor first.

## 4.2 Secondary Users: Food Vendors

Food vendors are secondary users.

They may use the system to:

- View incoming orders.
- Identify orders awaiting processing.
- Update order statuses.
- Organize meal preparation.
- Manage customer order information.

## 4.3 Administrator

An administrator may oversee the platform and manage the system.

Potential administrative responsibilities include:

- Managing vendors.
- Managing menus.
- Monitoring orders.
- Reviewing system activity.
- Resolving issues associated with orders.

Administrative functionality may be introduced in future versions.

---

# 5. USER RESEARCH

## 5.1 Research Objective

The research objective is to understand the challenges students face when purchasing food within a university campus environment.

The research seeks to investigate:

- How students currently purchase food.
- Whether students experience long queues.
- How much time students spend waiting for food.
- Whether students would prefer ordering food before arriving.
- Whether students would use an order-tracking system.
- The challenges faced by campus food vendors when handling orders.

## 5.2 Research Method

The proposed research methods include:

- Student surveys.
- Interviews with students.
- Interviews with food vendors.
- Observation of food-ordering activities.
- Review of existing food-ordering solutions.

A preliminary research exercise and simulated survey analysis were used during the initial planning stage of this project.

The simulated survey responses are illustrative and are not verified responses collected from actual participants.

Further research involving actual students and vendors is required to validate the findings.

## 5.3 Proposed Survey Questions

1. Do you regularly purchase food from campus vendors?
2. How often do you purchase food on campus?
3. Do you experience long queues when purchasing food?
4. How long do you usually wait before receiving your food?
5. Have you ever missed or been late for an activity because of waiting for food?
6. Would you prefer ordering food before arriving at a vendor?
7. Would you find it useful to track the progress of your food order?
8. What challenges do you experience when purchasing food on campus?
9. What features would you like to see in a campus food-ordering platform?
10. Would you use a web-based food-ordering platform if it were available?

## 5.4 Preliminary Research Findings

The preliminary research exercise suggested several possible challenges associated with campus food purchasing:

- Long queues during busy periods.
- Delays during food preparation.
- Limited time between academic activities.
- Uncertainty about meal availability.
- Difficulty managing orders during peak periods.

These findings represent preliminary observations and simulated research insights rather than verified results from a formally conducted survey.

## 5.5 Research Limitations

The initial research has several limitations:

- Survey results were simulated.
- No statistically representative student sample was established.
- Vendor interviews have not been formally documented.
- Campus-wide observations have not been systematically recorded.
- The findings cannot be generalized to all students.

Actual research will be required before making strong claims about user behaviour or the effectiveness of the proposed solution.

---

# 6. EXISTING SOLUTIONS

Existing digital food-ordering platforms provide functionalities such as online menus, food selection, payment processing, order confirmation, and order tracking.

Examples of existing solutions include:

- Food delivery applications.
- Restaurant websites.
- Online food-ordering platforms.
- Restaurant-specific ordering systems.

These solutions demonstrate that digital food ordering is an established approach to improving the ordering process.

However, general food delivery platforms may not always be specifically designed around the daily needs of students purchasing food within a university campus.

The proposed system focuses on a campus-based environment, where students may need to order food quickly, collect it within a short period, and avoid unnecessary waiting between academic activities.

---

# 7. PRELIMINARY GAP ANALYSIS

The proposed system focuses on the following potential gaps:

| Existing Challenge | Proposed System Response |
|---|---|
| Students may need to queue before placing orders | Allow students to place orders online |
| Students may not know what meals are available | Display available menus |
| Students may not know whether their orders are being prepared | Provide order status tracking |
| Ordering may be disorganized during busy periods | Maintain a structured order list |
| Students may need to repeatedly ask vendors about orders | Allow order tracking through reference numbers |

The identified gaps are preliminary and will require further validation through actual research.

---

# 8. PROPOSED SOLUTION

The proposed solution is a Campus Food Queue & Pre-order System.

The system will provide a web-based interface through which students can view vendors, browse meals, place orders, and monitor their order status.

Each successful order will receive a unique reference number that can be used to identify and track the order.

The system will also provide an order management interface through which order statuses can be updated.

The initial prototype will focus on essential functionalities rather than implementing every feature of a commercial food-ordering platform.

---

# 9. PRODUCT OBJECTIVES

The objectives of the system are:

1. Provide students with convenient access to campus food menus.
2. Allow students to place food orders online.
3. Reduce unnecessary waiting associated with physically placing orders.
4. Provide order reference numbers for tracking.
5. Enable students to monitor the progress of their orders.
6. Provide an organized system for managing incoming orders.
7. Demonstrate the application of backend engineering principles.
8. Develop a functional prototype that can be expanded in the future.

---

# 10. PRODUCT SCOPE

## 10.1 In Scope

The initial prototype includes:

- Homepage.
- Vendor listing.
- Menu listing.
- Individual vendor menu viewing.
- Food selection.
- Order placement.
- Customer name input.
- Matriculation number input.
- Food quantity selection.
- Automatic total price calculation.
- Unique order reference generation.
- Order confirmation.
- Order listing.
- Order management interface.
- Order status updates.
- Order cancellation.
- Order tracking using reference numbers.
- REST API endpoints.
- File-based order persistence.

## 10.2 Out of Scope

The initial prototype does not include:

- Real online payment processing.
- Student account registration.
- Student login and authentication.
- Vendor account registration.
- Real-time notifications.
- SMS notifications.
- Email notifications.
- GPS tracking.
- Delivery management.
- Live integration with actual campus food vendors.
- Production-level security.
- Automated refunds.
- A production database.

These features may be considered in future development.

---

# 11. MINIMUM VIABLE PRODUCT (MVP)

The Minimum Viable Product is a functional web-based food-ordering prototype that demonstrates the essential ordering process.

The MVP consists of the following:

### 11.1 Homepage

Provides an introduction to the platform and access to the main features.

### 11.2 Vendor Listing

Displays available food vendors and their operational status.

### 11.3 Menu

Displays meals, prices, and availability.

### 11.4 Order Placement

Allows users to select meals, specify quantities, and submit their orders.

### 11.5 Order Confirmation

Displays the submitted order details and a unique reference number.

### 11.6 Order Tracking

Allows users to search for their orders using their order reference numbers.

### 11.7 Order Management

Provides an interface for viewing orders and updating their statuses.

### 11.8 Order Persistence

Stores orders in a JSON file to ensure that orders remain available after restarting the server.

---

# 12. FUNCTIONAL REQUIREMENTS

## FR-01: Homepage

The system shall display a homepage providing navigation to the major features of the platform.

## FR-02: Vendor Listing

The system shall display registered vendors and their operational statuses.

## FR-03: Menu Display

The system shall display available food items, their prices, and availability.

## FR-04: Food Selection

The system shall allow users to select food items from the available menu.

## FR-05: Quantity Selection

The system shall allow users to specify the quantity of food they wish to order.

## FR-06: Order Submission

The system shall allow users to submit orders after providing the required information.

## FR-07: Order Validation

The system shall validate order information before accepting an order.

The validation shall include:

- Customer name.
- Matriculation number.
- Selected food item.
- Quantity.
- Food availability.

## FR-08: Price Calculation

The system shall calculate the total cost of an order based on the price of the selected food item and the quantity.

## FR-09: Order Reference Generation

The system shall generate a unique reference number for each successful order.

## FR-10: Order Confirmation

The system shall display order details and the order reference number after successful submission.

## FR-11: Order Tracking

The system shall allow users to search for their orders using their order reference numbers.

## FR-12: Order Status Management

The system shall allow authorized order managers to update the status of an order.

## FR-13: Order Cancellation

The system shall provide an order cancellation functionality within the prototype.

## FR-14: Order Listing

The system shall display recorded orders.

## FR-15: Order Persistence

The system shall store order information in a file so that orders remain available after restarting the server.

## FR-16: API Access

The system shall provide API endpoints for retrieving vendor information, menu information, and order information.

---

# 13. NON-FUNCTIONAL REQUIREMENTS

## 13.1 Usability

The system should be easy to understand and navigate.

Users should be able to access the main features without complicated procedures.

## 13.2 Performance

The system should respond to normal user requests within a reasonable period under typical prototype conditions.

## 13.3 Reliability

The system should process valid orders and maintain stored order information during normal operation.

## 13.4 Maintainability

The application should have a structured codebase that allows future modifications.

## 13.5 Compatibility

The system should work with modern web browsers.

## 13.6 Responsiveness

The interface should be usable on desktop computers, tablets, and mobile devices.

## 13.7 Data Integrity

The system should validate order information and maintain consistent order records.

## 13.8 Security

The prototype should avoid exposing unnecessary information and should eventually implement appropriate authentication, authorization, validation, and secure data storage.

The current prototype does not implement full production-level security.

---

# 14. USER STORIES

## Student User Stories

### US-01

As a student, I want to view available food vendors so that I can choose where to purchase food.

### US-02

As a student, I want to view food menus so that I can know which meals are available.

### US-03

As a student, I want to select meals and specify quantities so that I can place an order.

### US-04

As a student, I want to receive an order reference number so that I can identify my order.

### US-05

As a student, I want to track my order so that I can know its current status.

### US-06

As a student, I want to know the total price of my order so that I can understand how much I need to pay.

## Vendor User Stories

### US-07

As a vendor, I want to view incoming orders so that I can organize food preparation.

### US-08

As a vendor, I want to update order statuses so that students can know the progress of their orders.

### US-09

As a vendor, I want to identify pending orders so that I can prioritize order preparation.

---

# 15. ACCEPTANCE CRITERIA

## AC-01: Viewing Vendors

Given that the user opens the vendor page,

When the page loads,

Then the system should display the available vendors.

## AC-02: Viewing Food Menus

Given that the user opens the menu page,

When the page loads,

Then the system should display the food items, prices, and availability.

## AC-03: Placing an Order

Given that the user provides the required information,

When the user submits a valid order,

Then the system should create the order and display a confirmation.

## AC-04: Invalid Order

Given that required information is missing or invalid,

When the user submits the order,

Then the system should prevent the invalid order from being accepted.

## AC-05: Order Reference

Given that an order has been successfully created,

When the system processes the order,

Then the system should generate a unique reference number.

## AC-06: Order Tracking

Given that a valid order reference number exists,

When the user searches using the reference number,

Then the system should display the matching order details and status.

## AC-07: Updating Order Status

Given that an order exists,

When the order manager updates its status,

Then the system should save and display the updated status.

## AC-08: Order Persistence

Given that an order has been saved,

When the server is restarted,

Then the system should retain the order information.

## AC-09: Order Cancellation

Given that an order exists,

When the cancellation function is used,

Then the system should update the order status to Cancelled.

---

# 16. SYSTEM WORKFLOW

## Student Ordering Workflow

1. The student opens the website.
2. The student views available vendors.
3. The student selects a vendor or browses the available menu.
4. The student selects a meal.
5. The student specifies the quantity.
6. The student enters their name and matriculation number.
7. The student submits the order.
8. The system validates the information.
9. The system calculates the total price.
10. The system creates the order.
11. The system generates a unique order reference.
12. The system saves the order.
13. The system displays the order confirmation.
14. The student uses the reference number to track the order.
15. The student checks the order status.

## Vendor Order Management Workflow

1. The vendor or order manager opens the order management page.
2. The manager views recorded orders.
3. The manager identifies a pending order.
4. The manager updates the order status.
5. The system saves the updated status.
6. The student can view the updated status through the tracking interface.

---

# 17. SYSTEM ARCHITECTURE

The system follows a basic client-server architecture.

## 17.1 Frontend

The frontend provides the user interface through which students and order managers interact with the system.

Technologies:

- HTML.
- CSS.
- JavaScript.

Responsibilities:

- Displaying vendors.
- Displaying food menus.
- Collecting user input.
- Submitting orders.
- Displaying order information.
- Tracking orders.

## 17.2 Backend

The backend processes requests and manages application logic.

Technologies:

- Node.js.
- Express.js.

Responsibilities:

- Handling HTTP requests.
- Processing submitted orders.
- Validating order information.
- Calculating order totals.
- Generating order references.
- Updating order statuses.
- Serving API endpoints.
- Reading and writing order information.

## 17.3 Data Storage

The prototype uses JSON file storage.

Orders are stored in a JSON file named `orders.json`.

The file is used to preserve order records between server restarts.

JSON file storage is being used for the prototype. A relational database may be introduced in a future version.

---

# 18. TECHNOLOGY STACK

| Technology | Purpose |
|---|---|
| HTML | Structure of the frontend |
| CSS | Styling and responsive layout |
| JavaScript | Frontend functionality |
| Node.js | Backend runtime environment |
| Express.js | Backend framework |
| JSON | Data storage format |
| Visual Studio Code | Development environment |
| Web Browser | Testing and interaction |

---

# 19. DATABASE AND DATA STRUCTURE DESIGN

The initial prototype uses JavaScript objects and JSON file storage.

## 19.1 Vendor Data

Vendor records contain information such as:

- Vendor ID.
- Vendor name.
- Vendor location.
- Vendor status.

Example:

```json
{
  "id": 1,
  "name": "Campus Kitchen",
  "location": "Babcock University",
  "status": "Open"
}
```

## 19.2 Menu Data

Menu records contain information such as:

- Menu ID.
- Vendor ID.
- Food name.
- Price.
- Availability.

Example:

```json
{
  "id": 1,
  "vendorId": 1,
  "name": "Jollof Rice",
  "price": 1500,
  "available": true
}
```

## 19.3 Order Data

Order records contain information such as:

- Order ID.
- Order reference.
- Customer name.
- Matriculation number.
- Food item.
- Quantity.
- Unit price.
- Total price.
- Order status.
- Creation date.

Example:

```json
{
  "id": 1,
  "reference": "CFQ-1795675373151",
  "name": "Student Name",
  "matric": "25/0000",
  "food": "Jollof Rice",
  "quantity": 2,
  "price": 1500,
  "total": 3000,
  "status": "Pending",
  "createdAt": "2026-11-26T08:00:00.000Z"
}
```

The values shown in this example are illustrative.

---

# 20. API DESIGN

The system exposes basic API endpoints.

## 20.1 GET /api/vendors

Purpose:

Retrieve vendor information.

Expected response:

A list of available vendors and their details.

## 20.2 GET /api/menu

Purpose:

Retrieve food menu information.

Expected response:

A list of food items and their details.

## 20.3 GET /api/orders

Purpose:

Retrieve recorded orders.

Expected response:

A list of recorded orders.

## 20.4 GET /api/orders/:id

Purpose:

Retrieve a specific order using its numeric ID.

Expected response:

The matching order information.

## 20.5 POST /order

Purpose:

Submit a new food order.

Input information:

- Customer name.
- Matriculation number.
- Food item.
- Quantity.

Expected outcome:

The system validates the information, calculates the total, creates an order reference, stores the order, and displays confirmation.

## 20.6 POST /manage/:id

Purpose:

Update the status of an order.

Expected outcome:

The system updates the order status and saves the change.

## 20.7 POST /cancel/:id

Purpose:

Cancel an existing order.

Expected outcome:

The system updates the order status to Cancelled.

---

# 21. ORDER STATUS DEFINITIONS

The system uses the following order statuses:

| Status | Description |
|---|---|
| Pending | The order has been submitted and is awaiting processing |
| Confirmed | The order has been acknowledged |
| Preparing | The food is being prepared |
| Ready for Pickup | The order is ready for collection |
| Completed | The order has been collected or completed |
| Cancelled | The order has been cancelled |

---

# 22. TESTING PLAN

The prototype should be tested to ensure that its core functionalities work correctly.

## Test Case 1: Homepage

Objective: Verify that the homepage loads.

Expected Result: The homepage should display its content and navigation links.

## Test Case 2: Vendor Listing

Objective: Verify that vendors can be displayed.

Expected Result: Vendor information should be visible.

## Test Case 3: Menu Listing

Objective: Verify that menu items are displayed.

Expected Result: Food items, prices, and availability should be displayed.

## Test Case 4: Valid Order

Objective: Submit a valid food order.

Expected Result: The system should create the order and display a confirmation.

## Test Case 5: Invalid Order

Objective: Submit an order with missing or invalid information.

Expected Result: The system should prevent the order from being accepted.

## Test Case 6: Order Reference

Objective: Verify the reference number generated after an order.

Expected Result: The system should display a unique reference number.

## Test Case 7: Order Tracking

Objective: Search for an order using its reference number.

Expected Result: The system should display the correct order details and status.

## Test Case 8: Order Status Update

Objective: Update an order status.

Expected Result: The system should save and display the updated status.

## Test Case 9: Order Cancellation

Objective: Cancel an order.

Expected Result: The order status should be updated to Cancelled.

## Test Case 10: Persistence

Objective: Restart the backend server after saving an order.

Expected Result: Previously saved orders should remain accessible.

## Test Case 11: API Testing

Objective: Access API endpoints through a web browser.

Expected Result: The API should return the expected JSON information for the tested endpoints.

---

# 23. SUCCESS METRICS

The success of the prototype may be evaluated using the following metrics:

- Successful order creation.
- Successful order tracking.
- Successful order status updates.
- Successful order cancellation.
- Accurate order total calculations.
- Successful order persistence.
- Ease of navigation.
- Ease of understanding the ordering process.
- Reduction in waiting time during future real-world testing.

The reduction in waiting time cannot be confirmed using the current prototype alone. It would require testing in a real campus environment.

---

# 24. RISKS AND MITIGATION STRATEGIES

## Risk 1: Incorrect Order Information

Users may enter incorrect information.

Mitigation:

Implement input validation.

## Risk 2: Food Availability Changes

A food item may become unavailable after it has been displayed.

Mitigation:

Validate availability when the order is submitted.

## Risk 3: Data Loss

Data may be lost if files are deleted or damaged.

Mitigation:

Use backups and eventually migrate to a proper database.

## Risk 4: Unauthorized Order Management

Unauthorized users may modify order statuses.

Mitigation:

Implement authentication and authorization in a future version.

## Risk 5: Server Failure

The application may become unavailable if the server fails.

Mitigation:

Implement improved error handling, monitoring, and deployment infrastructure in future versions.

## Risk 6: Unverified User Needs

The proposed solution may not fully address the needs of actual students.

Mitigation:

Conduct real surveys, interviews, and usability testing.

## Risk 7: Fake or Demonstration Data

The prototype uses sample vendors and menu items.

Mitigation:

Clearly identify demonstration data and replace it with verified vendor information before real deployment.

---

# 25. ASSUMPTIONS

The project assumes that:

- Students have access to smartphones or computers.
- Students can access the internet.
- Campus vendors are willing to consider digital ordering.
- Vendors can receive and process online orders.
- Food availability can be updated.
- Students are willing to use a digital platform.
- Vendors can prepare orders within an appropriate period.
- Students can collect their orders.

These assumptions require further validation.

---

# 26. LIMITATIONS

The current prototype has the following limitations:

- It does not use a production database.
- It does not implement user authentication.
- It does not implement vendor authentication.
- It does not process online payments.
- It uses sample vendor information.
- It does not send notifications.
- It does not provide real-time delivery tracking.
- It does not implement production-level security.
- Its research findings have not been formally validated with actual participants.
- The order management functionality is a prototype and is not restricted through a complete authentication and authorization system.

---

# 27. FUTURE IMPROVEMENTS

Future versions may include:

1. Student account registration and login.
2. Vendor account registration and login.
3. A proper database such as PostgreSQL or MySQL.
4. Online payment integration.
5. Vendor dashboard.
6. Menu management.
7. Automated email notifications.
8. SMS notifications.
9. Real-time order updates.
10. Improved security.
11. Order history.
12. Customer feedback and ratings.
13. Search and filtering.
14. Mobile application.
15. Delivery functionality.
16. Integration with actual campus vendors.
17. Analytics and reporting.
18. Improved cancellation rules.
19. Role-based access control.
20. Deployment to a public hosting platform.

---

# 28. DEVELOPMENT IMPLEMENTATION STATUS

The project has progressed from problem identification and requirements planning into prototype development.

The following components have been implemented or developed in the prototype:

| Component | Status |
|---|---|
| Problem identification | Completed |
| Problem hypothesis | Completed |
| Target user identification | Completed |
| Survey question design | Completed |
| Preliminary simulated survey analysis | Completed |
| Existing solutions review | Initial review completed |
| Preliminary gap analysis | Completed |
| Proposed solution | Completed |
| Functional requirements | Documented |
| Non-functional requirements | Documented |
| User stories | Documented |
| Acceptance criteria | Documented |
| System workflow | Documented |
| System architecture | Documented |
| API design | Documented |
| Backend server | Implemented |
| Vendor listing | Implemented |
| Menu listing | Implemented |
| Homepage | Implemented |
| Food ordering | Implemented |
| Order confirmation | Implemented |
| Order reference generation | Implemented |
| Order tracking | Implemented |
| Order management page | Implemented |
| Order status updates | Implemented |
| Order cancellation | Implemented |
| JSON file persistence | Implemented |
| API endpoints | Implemented |
| Real online payments | Not implemented |
| Authentication | Not implemented |
| Production database | Not implemented |
| Real campus vendor integration | Not implemented |
| Formal usability testing | Pending |

Implementation statuses should be updated if any of the listed functionalities have not yet been tested or completed.

---

# 29. CONCLUSION

The Campus Food Queue & Pre-order System is a proposed digital solution to the challenges associated with purchasing food within university campuses.

The system aims to improve convenience by allowing students to view menus, place orders, receive order references, and track order progress.

The initial prototype demonstrates the core functionalities of the proposed solution through a web-based application built using HTML, CSS, JavaScript, Node.js, and Express.js.

The prototype also demonstrates basic backend concepts such as request handling, validation, order processing, API development, and file-based persistence.

Although the system currently operates with demonstration data and has not undergone formal real-world validation, it provides a foundation for further development.

Future work will focus on conducting actual user research, implementing a proper database, introducing authentication, integrating payments, and testing the system with students and vendors.

The long-term objective is to develop a practical, reliable, and accessible campus food-ordering platform that improves the experience of both students and food vendors.
