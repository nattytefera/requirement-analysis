# requirement-analysis
This repository is dedicated to exploring the concept of **Requirement Analysis** in the software development lifecycle.
The purpose is to document the importance, process, and techniques of gathering and analyzing requirements before implementation.
By breaking down both functional and non-functional requirements, this repository serves as a reference for understanding how well-defined requirements ensure successful project outcomes.

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, and analyzing the needs and expectations of stakeholders to define what a software system should achieve. It serves as one of the most critical steps in the **Software Development Life Cycle (SDLC)** because it lays the foundation for designing, building, and testing a system that meets business goals and user expectations.

During this stage, developers and analysts work closely with clients, end-users, and other stakeholders to understand the **problem domain** and translate it into clear, structured requirements. These requirements are usually divided into:

- **Functional Requirements**: Define the specific behaviors, features, and operations of the system.  
  *Example: "The system must allow users to register and log in using an email and password."*

- **Non-Functional Requirements**: Define quality attributes such as performance, security, usability, and scalability.  
  *Example: "The system must handle at least 5,000 concurrent users with a response time under 2 seconds."*

### Importance in SDLC
- **Prevents Misunderstandings**: Clear requirements ensure developers and stakeholders share the same vision.  
- **Reduces Cost and Rework**: Errors discovered at this stage are far cheaper to fix than later in development.  
- **Ensures Quality**: Well-defined requirements help testers validate that the final product works as intended.  
- **Supports Planning**: Accurate requirements make project scheduling, budgeting, and resource allocation more reliable.  

In short, Requirement Analysis answers the question: **"What needs to be built, and why?"** before moving into design and implementation.

## Why is Requirement Analysis Important?

Requirement Analysis is a crucial step in the **Software Development Life Cycle (SDLC)** because it ensures that the final product meets the needs of its users and stakeholders. Without this stage, projects risk running over budget, missing deadlines, or failing to deliver expected value. Below are some key reasons why Requirement Analysis is critical:

1. **Clarity and Alignment**  
   It ensures that all stakeholders (clients, developers, testers, and users) have a shared understanding of the system’s objectives. This reduces ambiguity and prevents misinterpretations of what needs to be built.  

2. **Cost and Time Efficiency**  
   Detecting and correcting requirement issues early is much cheaper and faster than fixing problems during later stages like development or deployment. A well-defined set of requirements minimizes rework and delays.  

3. **Improved Quality and User Satisfaction**  
   By gathering and analyzing user needs upfront, the final product is more likely to align with user expectations, leading to higher satisfaction and better adoption.  

4. **Better Project Planning and Risk Management**  
   Clear requirements allow for more accurate project estimates in terms of time, cost, and resources. They also help in identifying potential risks early in the process.  

## Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities to ensure that the final system meets business and user needs. The five key activities are:

- **Requirement Gathering**  
  Collecting raw requirements from stakeholders such as clients, users, managers, and subject matter experts. This step focuses on understanding the high-level expectations and goals of the project.  

- **Requirement Elicitation**  
  Using techniques like interviews, surveys, brainstorming sessions, workshops, and observation to draw out detailed and hidden requirements that may not be explicitly stated by stakeholders.  

- **Requirement Documentation**  
  Recording requirements in a clear, structured, and standardized format (often in a Software Requirements Specification (SRS) document). This ensures requirements are accessible and understandable for all team members.  

- **Requirement Analysis and Modeling**  
  Examining the gathered requirements to identify conflicts, overlaps, or gaps. This often includes creating models such as use case diagrams, data flow diagrams, or UML diagrams to visualize the system’s behavior and structure.  

- **Requirement Validation**  
  Reviewing the documented requirements with stakeholders to confirm accuracy, completeness, and feasibility. This ensures that the requirements truly reflect user needs and can be implemented within given constraints.  

## Types of Requirements

In software development, requirements are generally divided into two main categories: **Functional Requirements** and **Non-functional Requirements**. Both are essential to building a system that not only works correctly but also performs efficiently and delivers a good user experience.  

### Functional Requirements
Functional requirements define **what the system should do** — the specific features, behaviors, and functions it must provide to meet user needs.  

**Examples for a Booking Management System (like Airbnb or OYO):**  
- The system must allow users to create an account and log in using email or social media credentials.  
- The system must allow users to search for properties by location, price range, and amenities.  
- The system must provide real-time availability and booking confirmation.  
- The system must allow hosts to list properties with details like photos, descriptions, and pricing.  
- The system must allow users to make payments through multiple payment gateways (credit card, PayPal, etc.).  

### Non-functional Requirements
Non-functional requirements define **how the system should perform**. They are quality attributes that ensure the system is efficient, secure, and user-friendly.  

**Examples for a Booking Management System (like Airbnb or OYO):**  
- The system must handle at least 10,000 concurrent bookings without performance degradation.  
- The system must respond to user actions (e.g., search queries) within 2 seconds.  
- The system must ensure secure transactions by using encryption protocols (e.g., SSL/TLS).  
- The system must maintain 99.9% uptime availability.  
- The system must support mobile devices with a responsive and intuitive user interface.  

## Use Case Diagrams

A **Use Case Diagram** is a visual representation of the interactions between users (called *actors*) and a system. It illustrates the functionality of a system from the user’s perspective, showing what the system should do rather than how it should be implemented. Use Case Diagrams are part of the Unified Modeling Language (UML) and are widely used during the Requirement Analysis phase.  

### Benefits of Use Case Diagrams
- **Clarify System Scope**: They help define the system boundaries by showing what is inside (system functions) and what is outside (external actors).  
- **Improve Communication**: They provide a simple and intuitive way for stakeholders, developers, and testers to understand system behavior.  
- **Identify Functional Requirements**: Each use case corresponds to a specific functional requirement, making it easier to track and verify requirements.  
- **Support Design and Testing**: They serve as a foundation for creating detailed design models and test cases.  
- **Highlight User Perspective**: By focusing on how users interact with the system, they ensure the product aligns with user expectations and needs.  
https://drive.google.com/file/d/1H75vuDPgeJnAuj9ybXGk2M54hbZjZD9X/view?usp=sharing

## Acceptance Criteria

**Acceptance Criteria** are predefined conditions that a software product or feature must meet to be accepted by stakeholders, users, or the client. They describe the boundaries of a user story or requirement and act as a checklist to confirm whether the implementation is successful.  

### Importance of Acceptance Criteria in Requirement Analysis
- **Ensures Clarity**: Provides a shared understanding between stakeholders and the development team about what needs to be delivered.  
- **Defines Scope**: Clearly specifies the limits of a feature, preventing scope creep and ambiguity.  
- **Supports Testing**: Serves as the basis for writing test cases and verifying that the system works as expected.  
- **Increases Confidence**: Helps stakeholders confirm that the feature fulfills business goals and user needs.  

### Example: Checkout Feature in a Booking Management System
**Feature**: Checkout Process  

**Acceptance Criteria**:  
- The system must allow the user to view a booking summary before making payment.  
- The system must display available payment options (credit card, PayPal, etc.).  
- The system must securely process the payment and confirm the transaction.  
- The user must receive a booking confirmation message and an email receipt after successful checkout.  
- If the payment fails, the system must display an error message and allow the user to retry.  
