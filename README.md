# PetVet UXD
User Experience Design for PetVet: An Integrated Platform Connecting Pet Owners with Veterinary Services for Efficient Search, Comparison, and Appointment Booking.
## Index
1.  [**Introduction**](#1-introduction)
    * [1.1. The Problem](#11-the-problem)
    * [1.2. Our Solution](#12-our-solution)
2.  [**Team & Roles**](#2-team--roles)
3.  [**Strategy**](#3-strategy)
    * [3.1. Value Proposition Canvas](#31-value-proposition-canvas)
    * [3.2. UX Person](#32-ux-person)
    * [3.3. Benchmarking](#33-benchmarking)
    
4.  [**Scope**](#4-scope)
    * [4.1. Customer Journey Map](#41-customer-journey-map)
5.  [**Structure**](#5-structure)
   * [5.1. Navigation Flow](#51-navigation-flow)
6.  [**Skeleton**](#6-skeleton)
   * [6.1. Low-Fi Wireframes](#61-low-fi-wireframes)
7.  [**Surface**](#7-surface)
   * [7.1. Interface Evolution](#71-interface-evolution)
   * [7.2. Results of the Heuristic Evaluation](#72-results-of-the-heuristic-evaluation)
   * [7.3. High Definition Interfaces](#73-high-definition-interfaces)

---
## 1. Introduction

### 1.1. The Problem
- What if I can’t find a reliable veterinarian nearby when I need one the most?  
- What if I forget my pet’s vaccination schedule?  
- What if emergency services are not available in time?  

Pet owners face significant challenges when trying to access veterinary care. Information about clinics is often scattered across social media, outdated websites, or word-of-mouth recommendations. This leads to wasted time, uncertainty about service quality, and limited transparency regarding pricing or specializations.

In preliminary interviews with pet owners:
- **60%** reported difficulties in comparing veterinary clinics.  
- **70%** expressed frustration over missing reminders for vaccines or regular check-ups.  

The lack of a centralized, user-friendly platform reveals both a gap in accessibility and a strategic opportunity to improve the pet healthcare experience.

---

### 1.2. Our Solution

**PetVet** is an integrated platform that connects pet owners with veterinary services, offering efficient search, comparison, and appointment booking.

#### 🐾 Complete Veterinary Profiles
- Location with interactive maps  
- Services and specializations (exotic animals, emergency care, surgeries)  
- Verified staff credentials and photo galleries  

#### 📅 Smart Appointment Booking
- Real-time scheduling and availability  
- Automated reminders for upcoming visits  
- Patient history management (with owner consent)  

#### 🔍 Intelligent Search and Comparison
- Filters by location, price, ratings, and specialties  
- Interactive map displaying nearby clinics  
- Direct comparisons between multiple options  

#### 💬 Enhanced User Experience
- Pet profiles with medical history and alerts  
- Notifications for vaccinations and deworming  
- Emergency alerts and quick access to 24h services  
- Direct chat with veterinary staff for quick consultations  

---
## 2. Team & Roles
Orlando Caullan - Project Manager 

Joaquín Aravena - Analyst

Martín Zuñiga - Designer

Julio Contreras - Designer

Nicolas Toledo - Presenter

---
## 3. Strategy

### 3.1. Value Proposition Canvas
How we aligned pet owners’ needs with our solution

**Dual approach:**

- **For Pet Owners:**  
  Smart search and booking system, reminders for vaccinations, medical history tracking, and quick access to emergency care.  

- **For Veterinary Clinics:**  
  Management panel for appointments, patient history (with consent), promotional tools, and complete professional profiles with verified credentials.  

**Identified gaps:**

- **Social:**  
  Lack of trust in service quality due to scattered and unreliable information sources.  

- **Emotional:**  
  Stress during emergencies, uncertainty when choosing clinics, and frustration with forgotten medical tasks.  

- **Technical:**  
  Absence of an integrated, user-friendly platform that centralizes clinic information, offers real-time bookings, and automates reminders.  
<img width="1795" height="1292" alt="Template Value Proposition Canvas" src="https://github.com/user-attachments/assets/b78d4adc-4fa2-4868-bab6-890579547e6c" />

---

### 3.2. UX Person
Developed through interviews, these archetypes represent PetVet's key users. Each has unique motivations and barriers that were fundamental in defining the app's core functionalities.

👥🔹 **Laura Gomez: The Busy Professional**
> "I need the app to remind me of everything, otherwise I'm sure I'll forget."

👥🔹 **Andrés Torres: The First-Time Owner**
> "I want the app to be easy to use, because this is the first time I'm taking care of a cat."

👥🔹 **Carmen Rodríguez: The Multi-Pet Household Manager**
> "With so many animals, I need an app that helps me not get tangled up."
<img width="513" height="704" alt="UxPersona1LauraGomez" src="https://github.com/user-attachments/assets/1e3ae767-8651-428a-a906-665fd5988321" />
<img width="513" height="704" alt="UxPersona2AndresTorres" src="https://github.com/user-attachments/assets/9e9561da-4542-4fff-8675-24d74fb7a179" />
<img width="513" height="704" alt="UxPersona3CarmenRodriguez" src="https://github.com/user-attachments/assets/e3fc4a19-dd01-4339-9b3a-b6071037c17b" />

---

### 3.3. Benchmarking
To develop an application that truly meets the needs and expectations of pet owners seeking veterinary care, it was essential to analyze existing platforms—including both direct competitors and indirect references known for their efficient booking systems and user-friendly design.

The goal was to identify the strengths and weaknesses of current solutions, both functionally and visually, in order to incorporate best practices and avoid common pitfalls.

**Types of platforms analyzed:**
* 🐾 **Direct Competitors (Telemedicine & Booking):** Platforms like `Vetster` and `BuddyVet`, which directly connect owners with vets for consultations and appointments.
* 🏥 **Clinic Directories & Management:** Services like `WhereVets`, `CuidaPet`, and `GVet`, which focus on finding clinics or managing patient information.
* 📅 **Indirect References (Service Booking):** Apps like `Zocdoc` or `Booking.com`, valued for their powerful search filters, clear comparisons, and seamless booking experience.
<img width="752" height="557" alt="Benchmark" src="https://github.com/user-attachments/assets/7678096a-ff3c-4cd0-9d44-e270abeb2ac3" />

---
## 4. Scope

### 4.1. Customer Journey Map

#### 4.1.1 Decision Stage Interfaces

---

## 5. Structure

### 5.1. Navigation Flow
The PetVet navigation flowchart outlines a task-oriented and clear structure designed to streamline the process of finding and booking veterinary care. After logging in, the app is built around three main sections:

- **Dual Veterinary Search:** Users can find clinics through an interactive `Map` or a filterable `List of veterinary clinics`.
- **Streamlined Booking Process:** Both search paths converge on a simple, step-by-step flow: `Select Veterinary` -> `Select Hour` -> `Select Pet`.
- **Pet & User Management:** A dedicated `Profiles` section allows users to modify their account, add new pets, and manage existing pet information.

The structure requires users to `Login` before accessing the main functionalities. This decision allows for a personalized experience from the start, such as having pet information readily available when booking.
<img width="1798" height="1202" alt="Untitled" src="https://github.com/user-attachments/assets/bec9ef9f-e467-4600-9bec-102e2c6a6033" />

---

## 6. Skeleton
### 6.1. Low-Fi Wireframes
These wireframes establish the architectural blueprint for the PetVet platform, focusing on the system's core functionalities as defined in our solution. The navigation is designed around a persistent bottom tab bar, ensuring that users can effortlessly switch between the main sections: searching for clinics, managing appointments, and viewing their pets' profiles.

In our initial design phase, the interfaces were structured around three key user journeys, derived directly from the primary needs of our UX Personas:

Veterinary Discovery and Comparison: Includes all screens dedicated to searching for clinics, applying filters (by location, ratings, etc.), comparing service options, and viewing detailed veterinary profiles.


Appointment Booking Flow: Encompasses the entire process from selecting a time slot on a clinic's schedule to confirming the appointment and receiving automated reminders.


Pet Health Management: Contains the interfaces for creating and managing individual pet profiles, tracking their medical history, and receiving notifications for upcoming vaccinations.


📁 Wireframes Workspace – PetVet (Figma)

All complete views of the initial low-fidelity wireframes for the project, as these may change in the future, are attached in Figma and include the conceptual designs covering the first stage of the PetVet project.

📄 Low-Fi Wireframes – PetVet (PDF)

A comprehensive PDF document containing the complete set of initial wireframes with great detail for each view for quick comprehension and to avoid ambiguity, showing the main screens and user interactions defined during the initial design phase.

As the design evolved based on initial feedback, the "direct chat" feature was strategically deprioritized to concentrate on perfecting the core user experience. The focus shifted to strengthening the search and comparison tools and ensuring the appointment booking process was as seamless and intuitive as possible, directly addressing the main pain points identified in our research.

---

## 7. Surface
### 7.1. Interface Evolution
Our design process focused on turning low-fidelity sketches into a clean, professional, and reliable high-definition interface. As a key design decision, we deliberately avoided a pure white background (#ffffff), as it can be visually aggressive or invasive. Instead, we opted for a soft off-white (#FAFAFA) to create a sense of order, comfort, and professionalism.

This background was combined with a palette of greens. From our team's perspective, green was chosen because we believe it provides a sense of health and is intuitively associated with veterinary care.

A key decision made during our “Structure” phase was the “Login first” approach. This is essential because PetVet is a profile-centric application. Users need immediate access to their pets' stored data and medical history in order to enjoy a “fast and convenient” service.


Appointment Booking Flow Evolution

This was one of the most significant usability improvements. The initial wireframe showed a traditional full-month calendar, which forced users to hunt for a day and then see available times. This cluttered the view and didn't clearly show which times were free.

To streamline this, the design was changed to focus on one day at a time. The final mockup features a horizontal day-selector and a large, clear grid of available time slots. This change drastically reduces cognitive load and booking time, as it shows specific available times much more clearly.

<img width="734" height="710" alt="ui-evolution-booking" src="https://github.com/user-attachments/assets/a4299304-e912-49a0-820d-216d015dc8f9" />

User account evolution

The user account screen was redesigned to be more efficient and visually organized. The layout was a simple list, which was functional but wasted space.

In the high-fidelity version, the user's contact information (email, phone number) was moved directly below their name, and the edit profile option was moved to the right. This improved the visual hierarchy and saved vertical space. The space saved was used to add a new key feature: “Most recent visit,” which provides immediate value by showing the user their last appointment and, below it, another button to view the user's other appointments. Finally, the simple “Log out” text was replaced with a large, colored button, making the action more deliberate and visually consistent.

<img width="734" height="710" alt="ui-evolution-account" src="https://github.com/user-attachments/assets/05ebf54a-9344-43a6-9824-2f96bcbf0712" />

Confirmation screen evolution

Finally, the confirmation screen format was completely redesigned to make it clearer. The previous design had a lot of text and boxes, which made it difficult to read and did not make the hierarchy clear.

The new design uses a clean and orderly structure. It clearly separates the pet's profile (with a photo) from the pet's personal data and then, in a more compact format, the clinic's data. The buttons have also been significantly improved, using clear, action-oriented colors to guide the user and make the final action intuitive and error-free.

<img width="731" height="713" alt="ui-evolution-confirmation" src="https://github.com/user-attachments/assets/2a565775-6e75-4494-9e9b-5e6e22a6bf00" />

### 7.2. Results of the Heuristic Evaluation
A heuristic evaluation was conducted on the high-fidelity PetVet prototype to identify key usability issues before the final design. The evaluation, performed by our design team, focused on critical user flows such as appointment booking. While several minor adjustments were made, the evaluation identified one major usability flaw in the 'Confirm Appointment' screen, which was prioritized and completely redesigned.

| Problem | Solution |
| :--- | :--- |
| The initial 'Confirmar hora' screen had a confusing and redundant information hierarchy. It incorrectly used the same title ("Información de la mascota") for two different sections (the pet and the clinic). The layout was a text-heavy list, making it difficult for the user to scan and verify the appointment details quickly. | The screen was completely redesigned to create a more "ordered and logical" flow. The layout was simplified into two distinct, scannable cards: one for the Pet & Service details, and one for the Clinic. This "drastic change" clarified the information hierarchy, making it intuitive, and clear action buttons were added to complete the flow. |


Additional heuristic-based improvements:

-The order of filters on the main map and in the veterinary search has been improved.

-Better color on the buttons.



### 7.3. High Definition Interfaces
After several iterations and critical improvements guided by our heuristic evaluation, below are the final high-fidelity interfaces for PetVet. These interfaces have been designed to be clean, intuitive, and reliable, directly responding to the user needs identified in our “Strategy” phase.

But now the key question is:

Does this final prototype really help pet owners manage their animals' health?

Reviewing our UX personas, we can now conclude the following:

👥🔹 Laura Gomez (the busy professional), who feared “forgetting everything,” can now use the app to receive automatic reminders for vaccinations and appointments and easily view her pet's medical history.

👥🔹 Andrés Torres (the first-time owner), who needed an “easy-to-use” app, now has a simple, guided booking process, clear comparisons between clinics, and a professional interface that gives him confidence.

👥🔹 Carmen Rodríguez (the multi-pet caregiver), who needed help “staying organized,” can now use the “Account” screen to manage all her animals from one place, each with its own profile and history.

Below are the resources linked to the final high-fidelity interface designs:

📁 [Hi-Fi Interfaces Workspace – PetVet (Figma)]

📁 [Hi-Fi Prototype – PetVet (Figma)]

📄 [Hi-Fi Interfaces – PetVet (PDF)]

