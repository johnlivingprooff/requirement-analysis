# Requirement Analysis in Software Development.

_This repository explains the purpose of Requirement Analysis in Software Development and provides practical guidance on gathering, documenting, and refining user requirements to ensure alignment with project goals._

## **What is Requirement Analysis?**

Requirement Analysis involves identifying, documenting from a place of understanding, and validating stakeholders' needs and expectation for a Software Development project.

The process plays an important role in the Software Development Life Cycle **(SDLC)** as it lays the foundation for all subsequent phases
 by ensuring a clear understanding of what needs to be built.


## Why is Requirement Analysis Important?

 ### It Helps to: 
 - Define Scope: Prevents scope creep by clearly outlining project boundaries.
 - Avoid Miscommunication: Bridges gaps between stakeholders, developers, and designers.
 - Ensure Quality: Establishes criteria for testing and validation to meet user expectations.
 - Save Time and Cost: Reduces errors and rework by identifying potential issues early.
 - Align Goals: Ensures the software aligns with business objectives and user needs.

*In essence, it sets the stage for a successful, efficient, and user-centric development process.*

## Key Activities in Requirement Analysis.

### **1. Requirement Gathering**  
The process of collecting raw data and initial inputs from stakeholders to understand their needs, expectations, and constraints for the software project.  


### **2. Requirement Elicitation**  
A deeper exploration of stakeholder needs using techniques like interviews, workshops, and surveys to clarify, refine, and uncover implicit or hidden requirements.  


### **3. Requirement Documentation**  
The act of formally recording requirements in a clear, structured, and accessible format, such as Requirement Specifications or User Stories, for reference throughout the project.  


### **4. Requirement Analysis and Modeling**  
Evaluating gathered requirements for feasibility, consistency, and completeness while using tools like flowcharts, UML diagrams, or wireframes to visualize and organize them.  


### **5. Requirement Validation**  
The process of confirming with stakeholders that the documented requirements accurately reflect their needs and are practical to implement within project constraints.  

## Types of Requirements.

Here we explore the essential differences between what a system does (functional requirements) and how it performs (non-functional requirements), with practical examples from a Booking Management Project.

**Functional Requirements**

Define what the system should do, focusing on specific features, behaviors, and tasks.
Related to user actions, system interactions, and business processes.
Example: "The system must allow users to book, reschedule, or cancel an appointment."

**Non-Functional Requirements**

Define how the system should perform, focusing on quality attributes like performance, security, and usability.
Related to system characteristics and constraints.
Example: _"The system should respond to booking requests within 2 seconds."_

---

### **More Examples**

**1. Functional Requirements:**

- Users must be able to create a booking by selecting a date, time, and service.
- The system should send an email confirmation to users after a booking is made.
- Administrators should be able to view and manage all bookings through a dashboard.
- Users must be able to check the availability of services in real-time.
- The system should allow users to modify their bookings up to 24 hours before the scheduled time.

**2. Non-Functional Requirements:**

- The system must handle up to 500 concurrent booking requests without downtime.
- Booking data must be encrypted to ensure security and comply with GDPR standards.
- The application should be compatible with all major browsers and mobile devices.
- The system should maintain 99.9% uptime during business hours.
- The user interface must load within 3 seconds on a standard 4G connection.

## Use Case diagrams

Use Case Diagrams are visual representations that illustrate the interactions between users (actors) and the system to achieve specific goals. They show the system's functionality from the user's perspective, focusing on what the system should do rather than how it does it.

Here's an example of a use-case diagram for a Hotel Booking System:

![test](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fdrive.google.com/uc?id=1soe5dxNdnGCkKCryd_LgBMcCCQx7EQh3)

*A Use Case Diagram Shoing a typical accommodation booking system*

Click [here](https://drive.google.com/file/d/1soe5dxNdnGCkKCryd_LgBMcCCQx7EQh3/view) to download the image

## Acceptance Criteria.

Acceptance criteria define the specific conditions a feature must meet to be considered complete and acceptable to stakeholders. They are critical in requirement analysis because they:

- Clarify Expectations: Ensure developers, testers, and stakeholders have a shared understanding of what the feature should achieve.
- Guide Development: Provide a clear roadmap for implementing the feature.
- Support Testing: Serve as a basis for test cases to validate the feature.
- Reduce Miscommunication: Minimize misunderstandings and ambiguities about the requirements.
- Facilitate Decision-Making: Help stakeholders determine when the feature is ready for release.

### Example of Acceptance Criteria for a Checkout Feature

*Feature: **Checkout functionality in a booking management system.***

_Acceptance Criteria:_

1. The user must be able to review their booking details (e.g., room type, dates, total cost) on the checkout page.
2. The system must calculate the total cost, including applicable taxes and discounts.
3. The checkout page must display available payment options (e.g., credit card, PayPal).
4. The user must be able to complete the payment securely via a selected payment method.
5. A booking confirmation page must be displayed after successful payment, with a unique booking reference number.
6. The system must send an email confirmation to the user, including booking details and a receipt.
7. The system must prevent duplicate payments by validating the booking status before processing.

**Acceptance criteria ensure the feature meets both functional and non-functional requirements, aligning it with stakeholder goals.**
