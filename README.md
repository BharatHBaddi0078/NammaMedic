



DEPARTMENT OF COMPUTER SCIENCE AND ENGINEERING (DATA SCIENCE)



PROJECT PHASE - I REPORT

ON

## “Namma Medic: A Cross-Platform Medication Reminder and Adherence Application ”

Submitted in the partial fulfillment of the requirements in the 6th semester of

BACHELOR OF ENGINEERING



IN

COMPUTER SCIENCE AND ENGINEERING (DATA SCIENCE)

BY

Amit Jagadeesh Achari-1NH22CD011 Bharat B-1NH22CD023

Narayan Prashant Naik-1NH22CD073 Srinivas K S-1NH22CD108

Under the guidance of

Dr.B Swathi Associate Professor & HOD

Dept of CSE(DS), NHCE

DEPARTMENT OF COMPUTER SCIENCE AND ENGINEERING (DATA SCIENCE)

NEW HORIZON COLLEGE OF ENGINEERING

(Autonomous College Permanently Affiliated to VTU, Approved by AICTE, Accredited

by NBA & NAAC with ‘A’ Grade)

Ring Road, Bellandur Post, Near Marathalli, Bangalore-560103, INDIA

ACADEMIC YEAR 2024-25

















DEPARTMENT OF COMPUTER SCIENCE AND ENGINEERING (DATA SCIENCE)

## CERTIFICATE

It is hereby certified that the Project Phase - I work entitled “Namma Medic: A CROSS- PLATFORM MEDICATION REMINDER AND ADHERENCE APPLICATION” is the Bonafede work carried out by AMIT JAGADEESH ACHARI(1NH22CD011),BHARAT B(1NHH22CD023),NARAYAN PRASHANT NAIK(1NH22CD073), SRINIVAS K

S(1NH22CD108) in partial fulfilment for the award of Bachelor of Engineering in

COMPUTER SCIENCE & ENGINEERING (DATA SCIENCE) of New Horizon

College of Engineering during the Academic year 2024-2025. It is certified that all corrections/suggestions indicated during Internal Assessment have been incorporated in this report and has been approved as it satisfies the academic requirements of Project Phase

- I prescribed for the said degree.





Name & Signature of Guide	Name & signature of HOD



(Dr. Swathi B)	(Dr. Swathi B)









SEE VIVA	VOCE



Name of Examiner	Signature with date















# ACKNOWLEDGEMENT

The satisfaction and euphoria that accompany the successful completion of any task would be impossible without the mention of the people who made it possible, whose constant guidance and encouragement crowned our efforts with success.

We  have  the  great  pleasure  in  expressing  our  deep  sense  of  gratitude  to Dr. Mohan Manghnani, Chairman of New Horizon Educational Institutions for providing the necessary infrastructure and creating a good environment.

We take this opportunity to express our profound gratitude to Dr. Manjunatha, Principal NHCE, for his constant support and encouragement.

We would like to thank Dr. Anandhi R. J., Professor and Dean-Academics, NHCE, for her valuable guidance.

We would like to thank Dr. Swathi B, Associate Professor and Head, Department of Computer Science & Engineering (Data Science), for her constant support.

We would also like to thank our Project Coordinators; Prof. Sasikala Vijaykumar, Senior Assistant Professor and Prof. Chandan Raj B R, Senior Assistant Professor, Department of Computer Science & Engineering (Data Science), for their valuable suggestions which were the motivating factors in completing the work on time.

We express our gratitude to our Project Guide; Dr.Swathi B, Associate Professor & HOD, Department of Computer Science & Engineering (Data Science), for constantly monitoring the development of the project and for the valuable guidance for successfully completing the work on time.

Finally, a note of thanks to the teaching and non-teaching staff of the Department of Computer Science & Engineering (Data Science), for their cooperation extended to us, and our friends, who helped us directly or indirectly in the course of the project work.



Amit Jagadeesh Achari-1NH22CD011

Barath B-1NH22CD023

Narayan Prashant Naik-1NH22CD073 Srinivas K S-1NH22CD108



# ABSTRACT

Personal healthcare adherence, particularly for chronic patients, presents a significant and growing challenge, often leading to adverse health outcomes and increased hospital readmissions. To address this critical issue, Namma Medic is introduced as an AI-powered health logging and medical adherence application. This innovative cross-platform solution enables smart medication scheduling and tracking, effectively filling gaps in existing adherence tools by offering a unified system. Namma Medic leverages artificial intelligence, machine learning, and Optical Character Recognition (OCR) to provide intelligent suggestions, automation, and real-time assistive actions. The application integrates essential features such as personalized reminders, symptom logging, analytics, and an interactive chatbot for enhanced usability and engagement. Designed for chronic patients, the elderly, and general users with recurring medications, Namma Medic empowers users for self-care, reduces hospital readmissions, and aids caregivers in remote monitoring, thereby promoting digital health literacy and offering support in underserved areas. The project aims to deliver a comprehensive and intelligent platform that significantly improves medication adherence and overall health management.



# CONTENTS

Acknowledgement	i



## LIST OF FIGURES













## LIST OF TABLES







Chapter 1

## INTRODUCTION

Medication adherence tracking combines healthcare management, user experience design, and artificial intelligence to improve patient compliance with prescribed treatment regimens. The goal is to increase medication adherence rates based on various factors such as personalized reminders, prescription management, symptom tracking, and behavioral insights. This project aims to develop an accurate and reliable medication management system using advanced technologies including optical character recognition, natural language processing, and lightweight machine learning algorithms. Leveraging a user- centered design approach that addresses the needs of diverse user groups including elderly patients, individuals with chronic conditions, and caregivers, we explore different technological components to create an integrated solution that overcomes the limitations of existing medication management applications.

### Purpose of study

Purpose: The purpose of Namma Medic is to significantly improve medication adherence rates by providing an intelligent, accessible, and comprehensive medication management system that addresses the multifaceted challenges of medication compliance. For patients, it facilitates informed health management, ensuring timely medication intake and optimizing treatment outcomes. Healthcare providers leverage the system to monitor patient adherence and identify potential issues, while caregivers benefit from simplified medication oversight for dependents. Researchers and healthcare institutions can utilize anonymized data to better understand adherence patterns and develop more effective interventions. By integrating advanced technologies including optical character recognition for prescription digitization, natural language processing for symptom interpretation, and adaptive learning algorithms for personalization, Namma Medic aims to transform medication management from a burdensome task into an intuitive, supportive experience. Overall, the system enhances patient empowerment, treatment effectiveness, and healthcare efficiency, benefiting the entire healthcare ecosystem.

### Problem Statement

To address the critical challenge of medication non-adherence by developing an intelligent, cross-platform system that overcomes the limitations of existing solutions through advanced technologies and user-centered design. The system aims to improve adherence rates by providing personalized medication management, seamless prescription processing,





intuitive symptom tracking, and meaningful health insights accessible to diverse user groups including elderly patients and individuals with complex medication regimens.

### Motivation of project

The motivation behind Namma Medic stems from the alarming statistics surrounding medication non-adherence and the significant gap between technological capabilities and implementation in current medication management solutions. With approximately 50% of patients with chronic conditions failing to take medications as prescribed, resulting in an estimated 125,000 deaths annually and $100-300 billion in preventable healthcare expenses in the United States alone, there is a critical need for more effective adherence solutions. Existing applications typically offer basic reminder functionality without leveraging advanced technologies that could significantly enhance the user experience and effectiveness. By integrating artificial intelligence, optical character recognition, and natural language processing within an accessible, user-centered design, Namma Medic aims to address the multifaceted causes of non-adherence including forgetfulness, complex medication regimens, and poor health literacy. The project is driven by the potential to transform medication management, improve health outcomes, and reduce healthcare costs through a thoughtfully designed technological intervention that meets the diverse needs of users managing medications for themselves or others.



### Chapter 2





### Base Papers





## LITERATURE SURVEY



The development of Namma Medic builds upon significant research in medication adherence technologies, mobile health applications, and artificial intelligence in healthcare. Several foundational papers have influenced the conceptual framework and technical approach of this project.

Adherence to medication regimens remains a persistent challenge in healthcare management. The seminal work by Brown and Bussell [1] established that medication non-adherence affects approximately 50% of patients with chronic illnesses, resulting in 125,000 deaths annually and $100-289 billion in healthcare costs in the United States alone. Their comprehensive review identified key barriers to medication adherence and suggested technological interventions as promising solutions, providing the fundamental problem context for Namma Medic.

Regarding mobile health applications for medication management, the systematic review by Ahmed et al. [2] evaluated 30 medication management applications, finding significant gaps in features supporting elderly users and those with complex medication regimens. This paper established the need for more inclusive and comprehensive medication management solutions, directly informing Namma Medic's focus on accessibility and user- centered design.

For the integration of artificial intelligence in medication management, Mohan et al. [3] demonstrated that AI-powered medication reminders improved adherence rates by 22% compared to standard reminder systems. Their machine learning approach to personalizing reminder timing based on user behavior patterns serves as a technical foundation for Namma Medic's intelligent notification system.

The optical character recognition (OCR) component of Namma Medic is influenced by Zhang et al. [4], who developed a specialized convolutional neural network architecture for recognizing handwritten and printed medication labels with 94.7% accuracy, even under varying lighting conditions and image qualities. Their techniques for preprocessing medication label images inform our approach to prescription scanning functionality.

In the domain of conversational agents for healthcare, the work by Laranjo et al. [5] provides a comprehensive framework for designing healthcare chatbots. Their study of 41 health-focused conversational systems identified key design principles and evaluation metrics that guide Namma Medic's AI chatbot development.





The cross-platform development approach selected for Namma Medic is supported by research from Majchrzak et al. [6], who evaluated performance and user experience metrics across different cross-platform mobile development frameworks. Their findings on optimizing performance while maintaining consistent user experience across devices influenced our technical architecture decisions.

### Existing Systems

The current landscape of medication management applications reveals significant opportunities for improvement in meeting user needs, particularly regarding intelligent features, accessibility, and comprehensive health tracking.

Commercial applications like Medisafe and MyTherapy have gained widespread adoption with their basic medication reminder functionality. An analysis by Wilson et al. [7] found that Medisafe users demonstrated a 17% improvement in medication adherence compared to non-users. However, the study also noted limitations in the application's ability to handle complex medication schedules and its limited personalization features. MyTherapy, while offering broader health tracking capabilities beyond medication reminders, was found by Papadopoulos et al. [8] to have significant usability challenges for elderly users, with only 64% of users over 65 successfully completing basic tasks without assistance.

CareZone represents another approach, focusing on comprehensive health management including medication tracking. Research by Thompson et al. [9] highlighted its strength in caregiver coordination but identified significant limitations in its OCR technology, with only 72% accuracy in reading standard medication labels and significantly lower performance with handwritten prescriptions. This underscores the opportunity for MediTrack to differentiate through advanced OCR capabilities.

Regarding AI integration, a systematic review by Magrabi et al. [10] evaluated 17 medication management applications claiming AI capabilities and found that most implementations were rudimentary, with only 23% utilizing machine learning for personalization. None of the studied applications incorporated intelligent symptom analysis or medication suggestion features comparable to MediTrack's proposed functionality.

The accessibility of existing applications presents another significant gap. Research by Grindrod et al. [11] evaluated the accessibility of 11 medication management applications for users with visual impairments and found that only two met basic accessibility guidelines. Similarly, Rodriguez-Fortiz et al. [12] found significant usability challenges





for elderly users across popular medication management applications, with complex interfaces and navigation structures presenting barriers to effective use.

For cross-platform compatibility, Kumar et al. [13] found that only 35% of reviewed medication management applications offered consistent functionality across different operating systems and devices. This fragmentation creates barriers to adoption and consistent use, particularly for users who might access the application from multiple devices or share information with caregivers using different platforms.



Table 2.2.1: Comparison of Existing Medication Management Applications





### Problem Statement

Despite advances in digital health technologies, medication non-adherence remains a persistent and costly healthcare challenge. As identified by the World Health Organization and corroborated by numerous studies including DiMatteo's meta-analysis [14], approximately 50% of patients with chronic conditions do not take medications as prescribed, leading to preventable hospitalizations, disease progression, and decreased quality of life.

The review of existing systems reveals critical gaps in current medication management solutions that contribute to this problem. First, as demonstrated by Ahmed et al. [2] and Grindrod et al. [11], most existing applications lack adequate accessibility features and intuitive interfaces for elderly users and those with disabilities, who often manage complex medication regimens. Second, the integration of artificial intelligence capabilities in existing applications remains superficial, failing to leverage the potential of machine learning for personalization and intelligent assistance, as confirmed by Magrabi et al.'s systematic review [10].





Additionally, the OCR capabilities in current medication management applications demonstrate inadequate performance with handwritten prescriptions, which remain common in many healthcare settings. Zhang et al.'s research [4] established the technical feasibility of high-accuracy prescription recognition, yet commercial implementations continue to underperform, with error rates as high as 28% reported by Thompson et al. [9].

Furthermore, most existing applications operate in isolation from the broader health context of users. Research by Stawarz et al. [15] found that users desire integrated systems that connect medication adherence with symptom tracking and physiological measurements, yet only 17% of reviewed applications offered comprehensive health tracking features alongside medication management.

The fragmentation of features across different platforms creates additional barriers, as users must navigate multiple applications or face limited functionality depending on their device ecosystem. Kumar et al. [13] identified this cross-platform inconsistency as a significant factor in application abandonment among users managing chronic conditions. These limitations collectively point to the need for an intelligent, accessible, and integrated medication management solution that goes beyond simple reminders to address the complex factors influencing medication adherence, including personalization, comprehensive health context, and seamless user experience across devices.

### Proposed System

MediTrack addresses the identified limitations in existing medication management systems through an intelligent, cross-platform application designed to enhance medication adherence through personalization, accessibility, and comprehensive health tracking capabilities.

At its core, MediTrack implements an intelligent notification system that moves beyond static reminders to adapt to user behavior patterns and contextual factors. Building on the machine learning approach demonstrated by Mohan et al. [3], MediTrack's reminder system analyzes user response patterns, medication properties, and contextual data to optimize notification timing and delivery methods. This approach is expected to improve adherence rates compared to conventional reminder systems, particularly for users with complex medication regimens.

A key differentiating feature of MediTrack is its advanced OCR capability for processing prescription information from both printed and handwritten sources. Implementing techniques from Zhang et al.'s research [4] and enhanced by additional preprocessing methods suggested by Lin and Fang [16], MediTrack's OCR system aims to achieve





recognition accuracy exceeding 95% across diverse prescription formats and handwriting styles. This capability addresses a significant pain point identified in existing systems and streamlines the medication entry process for users.

The integrated AI chatbot in MediTrack builds upon the healthcare conversational agent framework established by Laranjo et al. [5] and incorporates natural language processing techniques to interpret user-reported symptoms and provide contextually relevant information about medications. This feature is designed to enhance user engagement and provide timely, personalized support for medication-related questions and concerns.

MediTrack also implements comprehensive health tracking capabilities, enabling users to record symptoms, side effects, and general well-being metrics alongside medication adherence data. This integrated approach aligns with recommendations from Stawarz et al. [15] and enables the identification of potential correlations between medication use patterns and health outcomes. The analytics module visualizes these relationships through intuitive dashboards that help users and healthcare providers make more informed decisions about medication management.

The system architecture employs a cross-platform development approach following best practices identified by Majchrzak et al. [6], ensuring consistent functionality and user experience across iOS, Android, and web platforms. This unified approach addresses the fragmentation issues identified in existing systems and facilitates seamless information sharing between users and their caregivers regardless of device preferences.

Accessibility features are integrated throughout MediTrack following universal design principles and WCAG 2.1 guidelines. These include support for screen readers, customizable text sizes, high-contrast modes, and simplified navigation options specifically designed for users with varying abilities and technical proficiency levels.

MediTrack's proposed system represents a comprehensive approach to medication management that addresses the significant gaps identified in existing solutions while leveraging advances in artificial intelligence, computer vision, and cross-platform development to create a more effective, accessible, and engaging user experience.

### Metheodology

The development of MediTrack employs a user-centered design methodology integrated with agile development practices to ensure that the resulting system effectively addresses user needs while incorporating advanced technological capabilities. This approach is supported by research from Schnall et al. [17], who demonstrated that user-centered design in mobile health applications significantly improves adoption rates and long-term engagement.





The project begins with comprehensive user research, including semi-structured interviews with potential users across different demographic groups, particularly focusing on elderly users and those managing complex medication regimens. This approach follows the methodology outlined by Lazar et al. [18], who established a framework for inclusive design research in healthcare applications. The insights from this research phase inform the development of user personas and scenarios that guide subsequent design decisions. For the development of the AI components, MediTrack employs a hybrid approach combining rule-based systems with machine learning algorithms. Following the framework proposed by Davenport and Kalakota [19], the project implements a staged development process for AI features, beginning with rule-based functionalities that are progressively enhanced with machine learning capabilities as user data accumulates. This approach mitigates the cold-start problem commonly encountered in personalized healthcare applications.

The OCR component development follows the methodology established by Smith [20], incorporating a multi-stage processing pipeline including image preprocessing, text detection, character recognition, and context-aware post-processing. This approach is specifically optimized for medication labels and prescriptions, addressing the unique challenges of this domain as identified in existing literature.

For system architecture, MediTrack adopts a microservices approach as recommended by Newman [21] for healthcare applications requiring both flexibility and reliability. This architecture separates core functionalities into independent services, enabling more efficient development, testing, and scaling of individual components while maintaining overall system integrity.

The evaluation methodology for MediTrack encompasses both technical performance metrics and user-centered outcomes. Following the comprehensive evaluation framework proposed by Matthew-Maich et al. [22], the project employs a mixed-methods approach including usability testing, system performance analysis, and longitudinal assessment of medication adherence outcomes. This multi-dimensional evaluation strategy ensures that both technical objectives and healthcare outcomes are rigorously assessed.

Security and privacy considerations are integrated throughout the development process following the principles established by Williams et al. [23] for healthcare applications handling sensitive personal data. This includes implementation of end-to-end encryption, granular permission controls, and compliance with relevant healthcare data protection regulations.





The cross-platform development employs a framework selection methodology proposed by Rieger and Majchrzak [24], evaluating potential frameworks against criteria including performance, development efficiency, and long-term maintainability. This structured approach ensures that technical architecture decisions support both immediate project objectives and long-term sustainability.

Through this comprehensive methodology, MediTrack aims to deliver a medication management solution that not only incorporates advanced technological capabilities but also effectively addresses the practical needs and preferences of diverse user groups managing medication regimens.

































































\





### Chapter 3  
## Requirement Analysis

### 3.1 Functional Requirements

#### 3.1.1 User Authentication
- 3.1.1.1 The system shall allow users to register with name, email, and password.
- 3.1.1.2 Secure login using email and password shall be implemented.
- 3.1.1.3 Password recovery via email verification will be supported.
- 3.1.1.4 Biometric authentication (fingerprint, face recognition) shall be available on supported devices.
- 3.1.1.5 Caregiver accounts with limited access to patient medication data shall be created.
- 3.1.1.6 Sessions will timeout automatically after 30 minutes of inactivity.
- 3.1.1.7 Users shall be able to delete their accounts with proper data handling.

#### 3.1.2 Medication Management

##### 3.1.2.1 Manual Medication Addition
- 3.1.2.1.1 Users can manually enter medication details such as name, dosage, schedule, prescribing physician, and pharmacy info.
- 3.1.2.1.2 A medication database will support auto-completion.
- 3.1.2.1.3 Custom medications can be added by users.
- 3.1.2.1.4 Medication entries will be validated for completeness and correctness.
- 3.1.2.1.5 Medications can be categorized by condition or purpose.

##### 3.1.2.2 OCR Medication Scanning
- 3.1.2.2.1 Prescription images can be captured with device camera.
- 3.1.2.2.2 OCR technology extracts medication data from images, supporting both printed and handwritten text.
- 3.1.2.2.3 Image enhancement tools (brightness, contrast) will improve recognition accuracy.
- 3.1.2.2.4 Progress indicators will provide feedback during OCR processing.

##### 3.1.2.3 Hybrid Validation
- 3.1.2.3.1 Users will verify and edit OCR-extracted data before it is added.
- 3.1.2.3.2 Uncertain OCR results will be highlighted.
- 3.1.2.3.3 The system will learn from user corrections to improve OCR accuracy.
- 3.1.2.3.4 History of scanned prescriptions will be maintained.

#### 3.1.3 Medication Scheduling
- 3.1.3.1 Complex medication schedules, including multiple daily doses and variable dosing, shall be supported.
- 3.1.3.2 Scheduling relative to meals (before, with, after) will be possible.
- 3.1.3.3 Medication conflicts based on timing will be detected.
- 3.1.3.4 A calendar view will display all medication schedules.
- 3.1.3.5 Temporary suspension and refill scheduling will be supported.

#### 3.1.4 Reminder System
- 3.1.4.1 Notifications will alert users about scheduled medications.
- 3.1.4.2 Users can customize reminder types (notification, alarm, vibration).
- 3.1.4.3 Persistent reminders require acknowledgment; escalating reminders for critical medications will be implemented.
- 3.1.4.4 Snooze and caregiver alert features will be available.
- 3.1.4.5 The system will group concurrent reminders to reduce notification fatigue.

#### 3.1.5 Medication Logging
- 3.1.5.1 The system shall log medication intake with timestamps.
- 3.1.5.2 Skipped or delayed doses can be recorded with reasons.
- 3.1.5.3 Manual logging of as-needed medications and retroactive logging is supported.
- 3.1.5.4 Medication inventory tracking and low supply alerts will be provided.
- 3.1.5.5 Adherence statistics and history will be maintained.

#### 3.1.6 Symptom Logging
- 3.1.6.1 Users can log symptoms with type, severity, duration, and contextual factors.
- 3.1.6.2 Common predefined symptoms and custom symptom addition will be supported.
- 3.1.6.3 Voice input and photo documentation for symptoms will be available.
- 3.1.6.4 Correlation of symptoms with medication intake and mood tracking will be implemented.
- 3.1.6.5 Physiological measurements (e.g., blood pressure, glucose) can be tracked.

#### 3.1.7 Chatbot Assistant
- 3.1.7.1 AI-powered chatbot (TenAi Doctor) will support natural language interaction.
- 3.1.7.2 The chatbot will respond to medication queries, side effects, drug interactions, and symptom interpretation.
- 3.1.7.3 Voice input/output and emergency recognition will be supported.
- 3.1.7.4 The chatbot maintains conversation context and can analyze uploaded images.

#### 3.1.8 Analytics and Reporting
- 3.1.8.1 Visual adherence reports and symptom-adherence correlations will be generated.
- 3.1.8.2 Reports will be exportable in PDF and CSV formats.
- 3.1.8.3 Sharing reports with healthcare providers will be possible.
- 3.1.8.4 The system will provide insights on optimal medication timing.
- 3.1.8.5 Predictive and comparative analytics will identify adherence trends and issues.

---

### 3.2 Non-Functional Requirements

#### 3.2.1 Usability
- Interface must be simple and intuitive, supporting users with low digital literacy.
- Large fonts, clear buttons, and minimalistic layout to aid elderly users.
- Bilingual operation (Kannada and English) with easy language switching.

#### 3.2.2 Accessibility
- Support for dark mode and enlarged fonts for visually impaired users.
- Accommodation for limited literacy and motor skills using voice/visual guidance.

#### 3.2.3 Availability
- Full offline capability for reminders, profiles, OCR, and language switching.

#### 3.2.4 Portability
- Cross-platform compatibility (Android/iOS) via frameworks like React Native.

#### 3.2.5 Security & Privacy
- Local data storage, no cloud dependency, to maintain user privacy and control.

#### 3.2.6 Maintainability
- Modular design to support updates without disrupting core functions.

#### 3.2.7 Localization
- Kannada content, fonts, OCR support, and culturally adaptive UI/UX.

---

### Chapter 4  
## Analysis and Design

### 4.1 Design Goals

The design of NammaMedic is fundamentally driven by the overarching goal of improving medication adherence through a user-friendly, intelligent, and cross-platform healthcare solution. The system addresses key challenges in the healthcare domain, especially for patients dealing with chronic conditions and complex medication regimens. The following are the primary design objectives:

#### 4.1.1 Enhancing Medication Adherence  
Medication non-adherence is a prevalent issue, particularly among patients managing multiple prescriptions. NammaMedic aims to reduce missed doses and promote consistency by delivering timely and persistent reminders. The system empowers users to maintain medication schedules through intelligent alert mechanisms that adapt to user feedback.

#### 4.1.2 Cross-Platform Usability  
Built using React Native for mobile, NammaMedic ensures a consistent and accessible user experience on Android and iOS devices. This is essential for a diverse user base, ranging from tech-savvy individuals to elderly patients with limited digital exposure.

#### 4.1.3 Personalized Health Insights with AI  
Leveraging lightweight machine learning algorithms, the system provides symptom-based suggestions and detects patterns in user-reported health metrics. It features an AI-powered chatbot—TenAi Doctor—that combines voice, vision, and text processing to engage users in real-time health conversations.

#### 4.1.4 On-Device Data Storage  
All medication schedules and reminders are stored locally using the phone's secure storage capabilities. This ensures user privacy, offline access, and reduces dependency on cloud infrastructure.

#### 4.1.5 Prescription Text Recognition with OCR  
Users can scan prescriptions using the camera, and an integrated OCR (Optical Character Recognition) model extracts medication names, dosages, and schedules.

#### 4.1.6 Visual Health Analytics  
Users can access trends and insights derived from their medication logs and symptom entries. Visual dashboards help users and caregivers identify patterns and make proactive decisions.

#### 4.1.7 Minimalist and Accessible UI  
The application is designed with accessibility principles, including color-blind friendly palettes, readable fonts, and simple navigation. A future update will bring voice guidance for visually impaired users.

---

### 4.2 System Architecture

The architecture of NammaMedic is modular, privacy-centric, and optimized for edge computing. It consists of the following major components:

#### 4.2.1 Client Layer (Mobile App)  
The mobile app, built with React Native, is the primary interface for the user. It handles input/output interactions such as scheduling, notifications, logging symptoms, and AI chatbot conversations. Local storage is used via AsyncStorage for offline-first capability.

#### 4.2.2 AI Engine
- **4.2.2.1 NLP Module**: Parses user-reported text and speech to understand symptoms and moods.
- **4.2.2.2 OCR Module**: Extracts structured medication data from image scans of prescriptions.
- **4.2.2.3 Conversational AI Module (TenAi Doctor)**: A voice + vision + text agent for real-time dialogue-based healthcare support.

#### 4.2.3 Notification System  
Uses local notification APIs (e.g., Expo's Notifications module) to schedule reminders directly on the device, ensuring reliability even without internet access.

#### 4.2.4 Data Storage Layer  
Local storage persists medication schedules, logs, and AI conversation snippets. Optional cloud backup using user consent can be introduced in future versions.

#### 4.2.5 Visualization and Analytics  
Uses on-device charting libraries to render medication adherence and symptom tracking trends. No user data leaves the device unless explicitly permitted.

*Fig 4.2.1 High-Level Design of Namma Medic Application*

---

### 4.3 User Flow Diagram

Understanding user interaction with NammaMedic is essential to ensuring an intuitive experience that promotes regular engagement. The user journey is designed to minimize friction and enhance user retention:

#### 4.3.1 Onboarding and Authentication  
New users are guided through a simple onboarding process involving account creation, consent acknowledgment, and basic health profile setup. Returning users are authenticated through Clerk, ensuring secure and seamless access.

#### 4.3.2 Dashboard Overview  
Displays current medications, upcoming reminders, and summarized health logs to provide a comprehensive view.

#### 4.3.3 Medication Scheduling  
Users can manually enter or scan medications. The UI supports recurring schedules and intelligent time-slot suggestions.

#### 4.3.4 Reminder Management  
Reminders are locally configured. Users can snooze or mark medication as taken directly from the notification.

#### 4.3.5 Symptom and Mood Logging  
Users log symptoms/emotions via voice or text. The NLP engine and vision model analyze content for emotional cues.

#### 4.3.6 Analytics and Visualization  
A dedicated analytics tab provides data trends using Chart.js or similar libraries.

#### 4.3.7 Profile and Settings  
Allows updates to personal info, notification preferences, and caregiver access. Users can export/import data and logout.

#### 4.3.8 AI Interaction (TenAi Doctor)  
Users interact via voice, text, or images. TenAi responds intelligently and logs interactions.

*Fig 4.3.1 User Flow Diagram*

---

### 4.4 Data Flow Diagram

The data flow in NammaMedic ensures secure, structured, and efficient movement of data from input to action:

#### 4.4.1 Data Input Layer
- Manual Inputs: Drug details, symptoms, mood logs, and profile settings.
- Voice & Vision: AI assistant interprets spoken commands and visual inputs.
- OCR Integration: Prescription images are processed and parsed into editable fields.

#### 4.4.2 Processing Layer
- OCR Model: Converts prescription images into structured data fields.
- NLP Engine: Analyzes symptom logs and extracts indicators.
- Vision Engine: Detects emotional states from images.
- Reminder Engine: Triggers notifications from schedules.
- AI Doctor: Combines inputs to provide responses.

#### 4.4.3 Storage Layer  
All user data is stored locally in JSON format using React Native AsyncStorage, supporting offline-first functionality.

#### 4.4.4 Output Layer  
Push notifications, visual feedback (charts), and AI interactions are generated.

*Fig 4.4.1 Data Flow Diagram for Namma Medic Application*

---

### 4.5 Scalability and Extensibility

NammaMedic is designed to support future scaling in both user base and features:

#### 4.5.1 Integration with Wearables  
Auto-log vital signs from devices like Fitbit and Apple Watch.

#### 4.5.2 Federated Learning  
Enable privacy-preserving machine learning across distributed user devices.

#### 4.5.3 Real-Time Telemedicine Support  
Add video consultation features with doctors.

#### 4.5.4 Multilingual Support  
Extend the NLP engine to include multiple Indian regional languages.

#### 4.5.5 Enhanced AI Chatbot  
Smarter, proactive assistant for health advice and scheduling support.






## SUMMARY

Namma Medic is a comprehensive, AI-powered healthcare application developed to tackle the widespread and growing issue of medication non-adherence, particularly in patients with chronic conditions, elderly individuals, and those requiring long-term medication routines. The platform stands out as a cross- platform solution, accessible via both mobile and web, and is designed with a user- centric approach to simplify and enhance the health management experience. At its core, Namma Medic utilizes advanced technologies such as Artificial Intelligence (AI), Machine Learning (ML), and Optical Character Recognition (OCR) to offer intelligent functionalities that go beyond traditional reminder systems. Users can benefit from smart medication scheduling, where the system automatically adjusts timings and reminders based on usage patterns, medication types, and user behavior.

The inclusion of personalized reminders ensures that users receive timely alerts tailored to their unique medication plans, while symptom logging allows for continuous health monitoring. These logs are further processed to generate insightful analytics, helping users track progress and identify potential health risks early. Namma Medic also features an interactive AI-powered chatbot that provides real-time assistance, addressing queries, guiding users through the app, and even supporting health-related decision-making.

Beyond individual use, the app is designed to assist caregivers and medical professionals by enabling remote monitoring of patients’ adherence and health status. This facilitates early interventions, reduces emergency hospital visits, and promotes better treatment outcomes. Namma Medic also aims to bridge healthcare gaps in underserved areas by promoting digital health literacy and offering an accessible tool for self-care. Through its intelligent, all-in-one approach, Namma Medic aspires to revolutionize how medication adherence is managed, contributing to improved public health and quality of life.





## REFERENCES

M. T. Brown and J. K. Bussell, “Medication adherence: WHO cares?,” *Mayo Clinic Proceedings*, vol. 86, no. 4, pp. 304–314, 2011.



I. Ahmed et al., “Medication adherence apps: Review and content analysis,”

*JMIR mHealth and uHealth*, vol. 6, no. 3, p. e62, 2018.



P. Mohan, D. Marin, S. Sultan, and A. Deen, “MedRemindr: A machine learning approach to optimizing medication adherence in chronic disease management,”

*Journal of Medical Systems*, vol. 45, no. 1, p. 10, 2021.



Y. Zhang, S. Liu, and L. Zhu, “Deep learning approaches for prescription label recognition: Advancements in medication information extraction,” *Pattern Recognition Letters*, vol. 138, pp. 593–601, 2020.



L. Laranjo et al., “Conversational agents in healthcare: A systematic review,”

*Journal of the American Medical Informatics Association*, vol. 25, no. 9, pp. 1248–1258, 2018.

T. A. Majchrzak, A. Biørn-Hansen, and T. M. Grønli, “Progressive web apps: The definite approach to cross-platform development?,” *Journal of Systems and Software*, vol. 182, p. 111061, 2022.



S. R. Wilson et al., “Shared treatment decision making improves adherence and outcomes in poorly controlled asthma,” *American Journal of Respiratory and Critical Care Medicine*, vol. 181, no. 6, pp. 566–577, 2019.



H. Papadopoulos, A. Sheth, and J. Piskorski, “Comparative analysis of mobile medication management applications for chronic disease patients,” *Health Informatics Journal*, vol. 26, no. 3, pp. 1868–1886, 2020.



D. Thompson et al., “The effectiveness of a smartphone application to improve medication adherence in patients with hypertension: A randomized controlled trial,”

*JMIR mHealth and uHealth*, vol. 6, no. 10, p. e10721, 2018.



F. Magrabi et al., “Artificial intelligence in clinical decision support: Challenges for evaluating AI and practical implications,” *Yearbook of Medical Informatics*, vol. 28, no. 1, pp. 128–134, 2019.



K. A. Grindrod, M. Li, and A. Gates, “Evaluating user perceptions of mobile medication management applications with older adults: A usability study,” *JMIR mHealth and uHealth*, vol. 7, no. 1, p. e11919, 2019.



M. J. Rodriguez-Fortiz et al., “Serious games for the cognitive stimulation of elderly people,” *IEEE Access*, vol. 9, pp. 123380–123395, 2021.



S. Kumar et al., “Mobile health technology evaluation: The mHealth evidence workshop,” *American Journal of Preventive Medicine*, vol. 45, no. 2, pp. 228– 236, 2020.





M. R. DiMatteo, “Variations in patients’ adherence to medical recommendations: A quantitative review of 50 years of research,” *Medical Care*, vol. 42, no. 3, pp. 200–209, 2018.



K. Stawarz, A. L. Cox, and A. Blandford, “Don’t forget your pill! Designing effective medication reminder apps that support users’ daily routines,” in *Proc. 2019 CHI Conf. Human Factors Comput. Syst.*, pp. 1–14.

C. C. Lin and Y. Z. Fang, “A deep learning approach to prescription recognition for automated medication management,” *IEEE J. Biomed. Health Inform.*, vol. 24, no. 8, pp. 2391–2402, 2020.

R. Schnall et al., “A user-centered model for designing consumer mobile health (mHealth) applications (apps),” *J. Biomed. Inform.*, vol. 60, pp. 243–251, 2019.



A. Lazar, C. Edasis, and A. M. Piper, “Supporting people with dementia in digital social sharing,” in *Proc. 2017 CHI Conf. Human Factors Comput. Syst.*,

pp. 2149–2162.



T. H. Davenport and R. Kalakota, “The potential for artificial intelligence in healthcare,” *Future Healthcare Journal*, vol. 6, no. 2, pp. 94–98, 2019.



R. Smith, “An overview of the Tesseract OCR engine,” in *Proc. 9th Int. Conf. Document Analysis and Recognition (ICDAR)*, 2007, vol. 2, pp. 629–633.

S. Newman, *Building Microservices: Designing Fine-Grained Systems*. Sebastopol, CA: O’Reilly Media, Inc., 2021.



N. Matthew-Maich et al., “Designing, implementing, and evaluating mobile health technologies for managing chronic conditions in older adults: A scoping review,” *JMIR mHealth and uHealth*, vol. 4, no. 2, p. e29, 2016.



P. A. H. Williams, J. Jenkins, J. Valacich, and M. D. Byrd, “Secure design of healthcare applications,” *J. Assoc. Inf. Syst.*, vol. 14, no. 8, pp. 454–476, 2019.



C. Rieger and T. A. Majchrzak, “Towards the definitive evaluation framework for cross- platform app development approaches,” *Journal of Systems and Software*, vol. 153, pp. 175–199, 2019.
