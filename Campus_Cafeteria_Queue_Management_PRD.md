# Product Requirements Document (PRD)

## Campus Cafeteria Queue and Order Management System

**Course:** BU-209 Backend Engineering  
**Version:** 1.0

## 1. Introduction

The Campus Cafeteria Queue and Order Management System is a proposed web-based platform for students and authorized cafeteria staff to browse menus, place pre-orders, join virtual queues, track order preparation statuses, and manage meal pickups.

The first version will focus on the backend and the essential digital queuing and order-handling process.

## 2. Problem Statement

Students frequently experience long physical queues and extended wait times at campus cafeterias, especially during peak break periods between lectures. Standing in congested lines can cause students to miss afternoon classes, skip meals, or overcrowd dining areas.

There is currently no consistent way to view real-time queue lengths, place orders ahead of arrival, or track when a meal is ready for pickup. A central system could streamline food service, reduce physical congestion, and improve time management for both students and cafeteria staff.

## 3. Research and Problem Validation

The problem must be validated through campus research before assumptions are treated as confirmed findings.

Research should involve students who regularly eat at campus cafeterias and cafeteria staff who prepare and serve meals. It should explore peak operating hours, average wait times, bottlenecks in ordering or payment, food abandonment rates, and existing kitchen workflows.

**Research status:** Interview responses and survey results have not yet been provided. Add the number and general roles of participants, research dates, and a summary of collected findings before final submission. Do not present uncollected results as facts.

## 4. Goal and Objectives

**Goal:** Provide a simple, organized platform for managing cafeteria queues, pre-ordering meals, and tracking order readiness.

The system should:
- Provide one place to view available menu items and current cafeteria wait times.
- Support placing orders remotely to join a digital queue.
- Allow cafeteria staff to manage incoming orders and update preparation statuses.
- Track queue positions and notify users of order readiness within the app.
- Prevent unauthorized order pickups using unique verification codes.

## 5. Proposed Solution and Users

The system will allow students to view available food items, select a cafeteria vendor, and place an order to receive a virtual queue ticket. Authorized cafeteria staff can view incoming tickets in order of arrival, update meal preparation statuses, and verify pickups at the counter.

**Primary users:** Students, faculty/staff dining on campus, and authorized cafeteria workers such as cashiers, cooks, and counter attendants.

**Other stakeholders:** University administration, cafeteria vendors/management, the course instructor, and the student community.

The system will support queue coordination and order tracking; it will not handle physical food delivery, external payment gateway processing (unless integrated later), or kitchen inventory supply chain management.

## 6. Main User Stories

- As a student, I want to create an account and view available menu items and current queue wait times.
- As a student, I want to place a meal order remotely so I do not have to stand in a long physical line.
- As a customer, I want to view my current position in the queue and track my order's preparation status.
- As a customer, I want to cancel my order before preparation begins if my schedule changes.
- As cafeteria staff, I want to view incoming orders in sequence and update their status (e.g., Preparing, Ready for Pickup).
- As cafeteria staff, I want to verify a customer's pickup code before handing over an order.
- As a cafeteria manager, I want to update menu item availability so students cannot order sold-out meals.

## 7. Functional Requirements

The backend must:

1. Allow users to register, log in, and log out.
2. Allow authorized staff to create, update, and toggle the availability of menu items.
3. Allow users to browse active menus and view estimated queue wait times.
4. Allow authenticated users to place orders and automatically assign them a sequential queue number and unique pickup code.
5. Allow users to view their active queue position and order status.
6. Allow users to cancel orders that have not yet moved to the "Preparing" stage.
7. Allow authorized staff to view active queues and update order statuses (Pending, Preparing, Ready, Completed, Cancelled).
8. Allow authorized staff to validate pickup codes and mark orders as completed upon handover.
9. Allow users to view their past order history.
10. Automatically recalculate estimated wait times based on active orders in the queue.

Orders and queue tickets must have unique IDs and clear statuses. The system must reject invalid requests (such as ordering out-of-stock items) and prevent users from performing actions they are not authorized to perform.

## 8. Non-Functional Requirements

- **Security:** Hash passwords, require authentication for protected actions, and enforce role-based permissions on the backend.
- **Privacy:** Do not expose personal user details or active pickup verification codes to other customers in the queue.
- **Reliability:** Preserve order data accurately and prevent race conditions when assigning queue numbers or updating stock.
- **Performance:** Support fast status polling and pagination for menus and order histories during peak lunch hours.
- **Maintainability:** Keep requirements and API behavior documented and organize backend functionality into understandable modules.

## 9. Scope and MVP

The first version will include account management, menu browsing, digital queue assignment, order placement and cancellation, status tracking, pickup code verification, basic staff permissions, and clear error handling.

The system will not include native mobile apps, third-party online payment processing (payments will be handled at the counter or via existing campus meal cards), push or SMS notifications, dorm delivery services, nutritional/calorie tracking, multi-campus support, or advanced predictive AI analytics.

## 10. Roles and Permissions

- **Customer (Student/Faculty):** Register, sign in, browse menus, place orders, view queue status, cancel eligible orders, and view order history.
- **Cafeteria Staff:** View incoming order queues, update order statuses, verify pickup codes, and toggle menu item availability.
- **Administrator:** Manage staff accounts, configure cafeteria vendor profiles, and oversee system operations.

The backend must enforce these permissions. The process for verifying cafeteria staff accounts must be agreed upon before implementation.

## 11. Main Workflow

1. A user signs in, checks current cafeteria wait times, and browses available menu items.
2. The user submits an order; the system validates item availability and assigns a unique order ID, queue position, and pickup code.
3. Cafeteria staff view the order in their active queue and update its status to "Preparing."
4. Once the meal is packed, staff update the status to "Ready for Pickup."
5. The user arrives at the designated express pickup counter and presents their pickup code.
6. Staff verify the code, hand over the meal (and collect payment if applicable), and mark the order as "Completed."

Placing an order reserves a spot in the digital queue; uncollected orders after a set grace period may be flagged by staff.

## 12. Data and API Requirements

The system will store user details, menu items, orders, queue positions, pickup codes, and status timestamps. It should collect only necessary information and protect private user and order verification details.

The backend will provide endpoints for accounts, menus, orders, queue tracking, and staff actions. These endpoints will support browsing, ordering, tracking, status updates, and pickup verification.

## 13. Conclusion

The Campus Cafeteria Queue and Order Management System aims to eliminate long physical wait times and reduce overcrowding during peak dining hours. A central platform for digital queuing, pre-ordering, and status tracking can improve dining efficiency for students and staff alike. Campus research will be used to validate the problem and guide the final design.