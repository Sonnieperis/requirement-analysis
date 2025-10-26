## ❓ What is Requirement Analysis?

**Requirement Analysis** is the process of collecting, clarifying, organizing, and validating the needs and constraints of stakeholders for a software system. It transforms high-level ideas and stakeholder requests into a clear set of documented, testable, and prioritized requirements that guide design, development, and testing.

### Why it matters
Requirement analysis is critical because it establishes *what* the system must do and *why*. Good requirement analysis reduces wasted effort, prevents misunderstandings, and ensures the delivered product aligns with user needs and business goals. When done poorly (or skipped), projects commonly suffer from scope creep, missed expectations, repeated rework, delayed timelines, and inflated costs.

### Role in the SDLC
Requirement analysis sits near the start of the Software Development Life Cycle (SDLC) and feeds all subsequent phases:

1. **Planning / Initiation** — identifies stakeholders and basic goals.  
2. **Requirement Analysis** — collects detailed functional and non-functional requirements.  
3. **Design** — architects and designers create solutions that meet the documented requirements.  
4. **Implementation** — developers build features according to the design and requirements.  
5. **Testing** — testers verify the implementation satisfies the documented requirements.  
6. **Deployment & Maintenance** — delivered software is monitored and evolved; requirements inform future iterations.

### Types of requirements
- **Functional Requirements**: Specific behaviors or functions the system must provide (e.g., “Users can search properties by location and date”).  
- **Non-Functional Requirements (NFRs)**: Quality attributes such as performance, security, accessibility, usability, and scalability (e.g., “Search results must load within 2 seconds”).  
- **Constraints & Assumptions**: Limitations or fixed conditions (e.g., supported browsers, third-party APIs, budget, or regulatory rules).  
- **Business Requirements**: High-level objectives the business needs the system to achieve (e.g., increase bookings by 20% in 6 months).

### Common activities in requirement analysis
- **Stakeholder identification & interviews** — find who will use the system and who has decision power.  
- **Workshops & brainstorming** — gather varied perspectives and align on goals.  
- **User stories / use cases** — describe desired functionality from the user’s perspective.  
- **Wireframes & low-fidelity prototypes** — visualize flows early to validate understanding.  
- **Prioritization** — decide which requirements are must-have vs. nice-to-have.  
- **Validation & sign-off** — stakeholders confirm the documented requirements are correct.

### Key deliverables
- **Requirements document / PRD** (Product Requirements Document)  
- **User stories and acceptance criteria** (for Agile teams)  
- **Wireframes / mockups** (to clarify UI expectations)  
- **Data models / API contracts** (if applicable)  
- **Traceability matrix** (maps requirements to tests and implementation)

### Who should be involved
- **Product Owner / Sponsor** — defines business goals and priorities.  
- **Business Analysts / Requirement Engineers** — lead the analysis and documentation effort.  
- **Designers (UX/UI)** — translate requirements into usable interfaces.  
- **Developers** — validate technical feasibility and provide estimates.  
- **QA/Testers** — ensure requirements are testable and define acceptance tests.  
- **Stakeholders / End users** — provide domain knowledge and validate needs.

### Risks of poor requirement analysis
- Misaligned expectations and features that don’t solve user problems.  
- Costly rework and schedule overruns.  
- Increased technical debt and brittle designs.  
- Low user adoption and negative business impact.

### Practical tip
Treat requirement analysis as an iterative, collaborative process — especially in Agile environments. Start with a minimal validated slice (MVP), deliver quickly, gather user feedback, and evolve requirements. That approach reduces risk and increases the chance of delivering real value.

## 🚀 Why is Requirement Analysis Important?

Requirement Analysis is one of the most critical phases in the Software Development Life Cycle (SDLC) because it lays the foundation for everything that follows — from design and development to testing and deployment. Without a clear understanding of what needs to be built, even the most skilled team can deliver the wrong product. Below are key reasons why Requirement Analysis is essential:

### 1. Ensures Clear Understanding and Alignment
It establishes a shared understanding between stakeholders, developers, and designers about what the system should accomplish. By clearly defining functional and non-functional requirements, the team avoids ambiguity, miscommunication, and conflicting expectations.

### 2. Reduces Development Costs and Rework
A well-conducted requirement analysis helps identify potential issues, missing features, and unrealistic expectations early in the process. Fixing mistakes at the requirements stage is far cheaper and faster than correcting them during or after development. This saves both time and resources.

### 3. Guides Design, Development, and Testing
Requirements serve as a blueprint for the design and implementation of the system. They inform architecture decisions, define what needs to be built, and provide measurable acceptance criteria for testing and validation. In short, they act as the *contract* that connects all SDLC phases.

### 4. Improves User Satisfaction and Product Quality
When requirements accurately capture real user needs and business objectives, the resulting product provides genuine value. Proper analysis ensures that usability, performance, and reliability are prioritized — leading to higher customer satisfaction and product adoption.

### 5. Minimizes Scope Creep and Project Risks
Scope creep often happens when new features are added without proper evaluation. Requirement analysis sets clear boundaries and priorities, helping teams manage change requests in a controlled way and keeping the project focused on core goalsv.


## 🧩 Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that help ensure the final software product meets user and business expectations. Below are the five key activities typically performed during this phase:

### 1. Requirement Gathering
- Involves collecting all possible requirements from stakeholders, clients, and end users.  
- Focuses on understanding what users need and what problems the system should solve.  
- Techniques include interviews, surveys, brainstorming sessions, and reviewing existing documentation.

### 2. Requirement Elicitation
- Focuses on uncovering hidden, implied, or conflicting needs through deep discussions and observations.  
- Helps clarify assumptions and identify constraints, priorities, and dependencies.  
- Common techniques include workshops, focus groups, use case development, and prototyping.

### 3. Requirement Documentation
- Involves recording all gathered and elicited requirements in a structured and understandable format.  
- The output is typically a **Software Requirements Specification (SRS)** document.  
- Ensures traceability and serves as a reference point for design, development, and testing teams.

### 4. Requirement Analysis and Modeling
- Focuses on studying the documented requirements to check for completeness, consistency, and feasibility.  
- Involves using diagrams, models, and workflows to visualize the system’s structure and behavior.  
- Techniques include data flow diagrams (DFD), use case diagrams, and entity-relationship (ER) models.

### 5. Requirement Validation
- Ensures that the documented requirements accurately represent stakeholder needs and business objectives.  
- Detects missing, incorrect, or conflicting requirements before development begins.  
- Validation techniques include walkthroughs, reviews, inspections, and prototype evaluations.

## 🧱 Types of Requirements

Software requirements are divided into two main types: **Functional** and **Non-functional Requirements**.

---

### ⚙️ Functional Requirements

Define **what the system should do** — the main features and behaviors.

**Examples (for a hotel booking system like Airbnb/OYO):**
- Users can create accounts and log in.
- Search and filter properties by location, date, or price.
- View property details (images, reviews, price).
- Book and pay online securely.
- Property owners can list and manage their properties.
- Admins can manage users and bookings.

---

### ⚡ Non-functional Requirements

Define **how the system should perform** — quality and performance standards.

**Examples:**
- **Performance:** Handle 1,000+ users at once.  
- **Security:** Encrypt all user and payment data.  
- **Usability:** Mobile-friendly and easy to navigate.  
- **Reliability:** Maintain 99.9% uptime.  
- **Speed:** Load main pages in under 3 seconds.  

---

> Functional requirements describe features.  
> Non-functional requirements ensure quality, speed, and reliability.

## 🎯 Use Case Diagrams

### What is a Use Case Diagram?

A **Use Case Diagram** is a visual representation of how different users (actors) interact with a system.  
It helps identify **functional requirements** by showing the relationships between **actors** and **use cases** (system functions).

Use Case Diagrams are widely used during **Requirement Analysis** to:
- Visualize the system’s scope and user interactions.  
- Clarify system behavior before development begins.  
- Improve communication between developers, designers, and stakeholders.  

---

### Benefits of Use Case Diagrams
- Provides a **clear overview** of all user interactions.
- Helps identify **missing or redundant functionalities** early.  
- Serves as a **blueprint** for defining system requirements.  
- Facilitates **better collaboration** between technical and non-technical teams.  

---

### 🧍 Actors in the Booking System
- **Guest/User** – Searches, views, and books properties.  
- **Host/Property Owner** – Lists and manages property details.  
- **Admin** – Oversees users, bookings, and overall platform operations.  

---

### ⚙️ Main Use Cases
- Register / Log In  
- Search for Properties  
- View Property Details  
- Book a Property  
- Make Payment  
- Manage Bookings  
- List / Edit Properties  
- Manage Users (Admin)

---

### 📊 Use Case Diagram

Below is the Use Case Diagram representing the main interactions in the system.

![Booking System Use Case Diagram](./alx-booking-uc.png)

*(Diagram created using [Draw.io](https://app.diagrams.net/) and exported as **alx-booking-uc.png**)*

---

### Notes
- Place the image file in your repository root or `assets/` folder.  
- Ensure the file is named exactly `alx-booking-uc.png` so the link displays correctly in GitHub.

## ✅ Acceptance Criteria

**Acceptance Criteria** define the specific conditions that a feature must meet to be considered complete and accepted by the client or product owner.  
They ensure clarity between developers, testers, and stakeholders on what “done” means.

### Importance
- Prevents misunderstandings about feature expectations.  
- Guides development and testing processes.  
- Ensures the product meets user needs and business goals.  

### Example: Checkout Feature
**Feature:** Complete a property booking.

**Acceptance Criteria:**
- User can review booking details before payment.  
- User can securely enter and process payment information.  
- A confirmation message and booking ID appear after successful payment.  
- Failed payments show an error message and allow retry.  
