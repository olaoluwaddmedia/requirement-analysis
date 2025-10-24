# Requirement Analysis in Software Development.

## Introduction
The Requirement Analysis Project involves documenting and analyzing requirements to build a solid foundation for software development. Learners will create a detailed blueprint for a booking management system, simulating a real-world scenario that emphasizes clarity, precision, and structure in defining requirements for successful project execution.

## What is Requirement Analysis?
Requirement Analysis, also known as requirements engineering, involves the process of identifying, gathering, analyzing, documenting, and validating the requirements of a software system. It aims to answer key questions such as:
    .What problem is the software trying to solve?
    .Who will use the software and how?
    .What are the system’s functional and non-functional requirements?

# Importance of Requirement Analysis in the SDLC
 1-Establishes a Clear Project Scope
 2-Improves Communication
 3-Reduces Development Costs and Time
 4-Enhances Quality and User Satisfaction
 5-Guides Design, Testing, and Maintenance

 ## Why is Requirement Analysis Important?
    1. Prevents Misunderstandings and Miscommunication
       Requirement Analysis ensures that both stakeholders (clients, users, and managers) and developers share a common understanding of          the project’s goals.
    2. Saves Time and Reduces Development Costs
       Identifying and resolving requirement issues early in the SDLC is far less costly than fixing them later during coding or testing.
    3. Ensures Software Quality and User Satisfaction
       When requirements are well-defined, validated, and agreed upon, the resulting software is more likely to meet user needs and business objectives.

## Key Activities in Requirement Analysis.

## Requirement Analysis — Key Activities

- **Requirement Gathering**
  - Identify stakeholders and collect functional & non-functional needs.
  - Techniques: interviews, surveys, observation.

- **Requirement Elicitation**
  - Explore the "why" behind needs and uncover implicit requirements.
  - Techniques: workshops, prototyping, use cases.

- **Requirement Documentation**
  - Produce a clear, testable Software Requirements Specification (SRS).
  - Include scope, acceptance criteria, constraints, and assumptions.

- **Requirement Analysis & Modeling**
  - Check for consistency, completeness, and feasibility.
  - Create visual models: Use Case Diagrams, DFDs, ERDs.

- **Requirement Validation**
  - Validate requirements with stakeholders and obtain sign-off.
  - Techniques: reviews, walkthroughs, prototypes, test-case alignment.

## Types of Requirements

### 1. Functional Requirements
Functional requirements define **what the system should do** — the specific features, behaviors, and functions that enable it to meet user and business needs.  
They describe how the system should respond to inputs and handle specific situations.

**Examples:**
- The system must allow users to create, edit, and cancel bookings.  
- The application should send an email confirmation after each successful booking.  
- Users should be able to log in using a registered email and password.  

---

### 2. Non-Functional Requirements
Non-functional requirements specify **how the system performs its functions**, focusing on quality attributes such as performance, security, usability, and scalability.  
They determine the overall user experience and operational standards of the software.

**Examples:**
- The system should load the booking page within 3 seconds.  
- The application must support up to 1,000 concurrent users.  
- User data must be encrypted to ensure security and privacy.

## Use Case Diagrams
Use Case Diagrams are visual representations used in software development to show how different users (called actors) interact with a system. They focus on what the system should do, not how it does it.

# Benefits of Use Case Diagrams
1-Simplify Understanding of System Functions
2-Enhance Communication
3-Define System Boundaries
4-Aid in Requirement Gathering and Validation
5-Support Design and Testing

# A use case diagram for the booking system

![image alt](https://github.com/olaoluwaddmedia/requirement-analysis/blob/2feed75207824546e3b9d90ff71e08eefa85607f/alx-booking-uc.png)

## Acceptance Criteria
Acceptance Criteria are a set of predefined conditions or requirements that a software product must satisfy to be accepted by the client, stakeholders, or end users. They describe the boundaries of a user story or requirement, outlining what must be true for the feature or system to be considered complete and functioning as intended.

- **Booking Review**
  - Users must be able to view a summary of their booking details (date, time, service type, and total cost) before proceeding.
  - The summary must be accurate and reflect all selected services.

- **Payment Method Selection**
  - The system must display available payment options (e.g., credit/debit card, bank transfer, digital wallet).
  - Users must select one valid payment method before continuing to checkout.

- **Payment Processing**
  - The system must securely process the payment through an integrated payment gateway.
  - On successful payment, the booking must be marked as *confirmed*.






