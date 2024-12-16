# SWENG837_FinalProject

Welcome to the **SWENG837 Final Project** repository. This project explores software System Design principles through UML diagrams and design components.

---

## Project Overview
This repository contains the final project submission for SWENG837. Which is a Online Appointment Booking System. UML diagrams and related design elements are used to illustrate how software design approaches are used. By applying a methodical and scalable approach to software design, the project seeks to address an issue.

---

## Repository Structure
- **/Images/**: Contains all UML diagrams created for the project.
- **/Scripts/**: Includes the source code for the project. 
- **/PowerPoint/**: Supporting powerpoint for the project.
- **/Word/**: Supporting doc for the project.
- **README.md**: An overview of the project.

---

## UML Diagrams and Explanations
The project includes the following UML diagrams:

### 1. **Class Diagram**
   **folder** 'Images'
   **File:** `UML_Diagrams/Class_Diagram.png`
   - **Purpose:** Depicts classes, their properties, methods, and relationships to represent the system's static structure.
   - **Key Features:**
     - shows the relationships, dependencies, and inheritance between classes.
     - Highlights key classes such as `User`, `SystemController`, and `DatabaseHandler`.

### 2. **Sequence Diagram**
   **folder** 'Images'
   **File:** `UML_Diagrams/Sequence_Diagram.png`
   - **Purpose:** shows the interactions between objects in a certain use case scenario.
   - **Key Features:**
     - Illustrates how messages move between things.
     -  This includes the steps involved in retrieving data and logging users in.

### 3. **Use Case Diagram**
   **folder** 'Images'
   **File:** `UML_Diagrams/Use_Case_Diagram.png`
   - **Purpose:** shows actors and how they interact with the system to give a high-level picture of how the system works.
   - **Key Features:**
     - Identifies key actors: `Admin` and `User`.
     - Maps core use cases such as `Manage Accounts` and `View Reports`.

### 4. **Activity Diagram**
   **folder** 'Images'
   **File:** `UML_Diagrams/Activity_Diagram.png`
   - **Purpose:** illustrates the system's dynamic features by emphasizing the processes involved in different tasks.
   - **Key Features:**
     - Decision points and ongoing procedures are highlighted.
     - Description Shows how the user registration procedure works.

### 5. **State Diagram**
   **folder** 'Images'
   **File:** `UML_Diagrams/State_Diagram.png`
   - **Purpose:** explains a particular class's states and the changes between them.
   - **Key Features:**
     - Tracks the lifecycle of a `User` object.
     - Details states such as `New`, `Active`, `Suspended`, and `Deleted`.


---

## Design Components

### 1. **System Architecture**
   - The system follows an **MVC (Model-View-Controller)** architecture.
   - **Model:** Manages data and business logic.
   - **View:** oversees the user interface.
   - **Controller:** interprets user input and makes the necessary modifications to the model and view.


### 2. **Scalability and Modularity**
   - Extension and maintenance are made simple by modular components.
   - Every module communicates with the others through clear interfaces.




