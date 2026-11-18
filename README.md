MedConnect – Telemedicine & Appointment Booking Platform

MedConnect is a web platform that lets patients find verified doctors, book appointments, pay online and see a doctor by video. It also includes an AI-assisted symptom checker that points patients to the right kind of care.

This repository holds the business analysis and requirements documentation for the project. It was written as a capstone project for the SWD392 course at FPT University (Group 5, 4 members, 2026).

📄 Full document: SWD_Project_Team.pdf (109 pages)

My role

Phạm Quốc Tuấn – Team Leader & Business Analyst

Coordinated a 4-person team, tracked progress and kept BA, UI/UX, development and testing work consistent.
Ran the competitor analysis and defined the product's scope and feature list.
Wrote the Software Requirements Specification (SRS): use cases, business rules, non-functional requirements, application messages, ERD and screen flow.
Specified the AI-assisted symptom checker and the business rules that keep it safe to use.
The problem

Patients in Vietnam often struggle to find the right doctor, wait long to get an appointment, and have no simple way to see a doctor remotely. Existing platforms each solve only part of this. Some focus on booking but have no video consultation or medical records. Others offer consultation but are not built around Vietnamese clinics.

MedConnect brings the full patient journey into one platform: find a doctor → book → pay → consult by video → receive a prescription → follow up.

Competitor analysis

The document compares three existing platforms to find the market gaps:

Platform	Focus	Main weaknesses found
BookingCare	Clinic booking in Vietnam	No video consultation, limited medical records and prescriptions, no AI symptom checking
Doctor Anywhere	Regional telemedicine (SG, TH, VN, PH)	Weak Vietnamese hospital integration, higher cost, no booking at physical clinics
eDoctor	Family health, chat/video consultation	No hospital appointment integration, limited specialists, no AI symptom triage

The gap MedConnect targets: one platform that combines clinic booking, video consultation, e-prescriptions and AI symptom triage for the Vietnamese market, which the document sizes at about USD 1.2 billion by 2026.

Main features
ID	Feature
FE-01	Authentication & access control
FE-02	Role-based accounts & profiles (patient, doctor, admin)
FE-03	Doctor verification & credential approval
FE-04	Doctor search & filtering
FE-05	Doctor schedule & availability management
FE-06	Appointment booking, cancellation & rescheduling
FE-07	Online payment, billing & refunds
FE-08	Telemedicine video consultation
FE-09	Consultation summary & e-prescription
FE-10	Notifications & reminders
FE-11	Ratings, reviews & moderation
FE-12	AI-assisted support & recommendation
FE-13	Admin dashboard, KPIs & reports
AI-assisted symptom checker

A chatbot asks patients about their symptoms and suggests the right care pathway: self-care, GP visit, specialist or emergency. It then recommends suitable doctors on the platform.

To keep it responsible, the requirements state that AI screening and doctor recommendations are advisory only and must not replace a doctor's professional judgment (business rule BR-11).

What the document contains
Project introduction – background, problem statement, competitor analysis, vision, scope and limitations.
Software Requirements Specification
Actors, use case diagram, use case descriptions and specifications
Screen flow, screen descriptions and screen authorization
Entity Relationship Diagram (ERD)
Detailed functional requirements for FE-01 to FE-13
Non-functional requirements: usability, reliability, performance, security, scalability, maintainability
Business rules summary, application messages and glossary
Contact

Phạm Quốc Tuấn – tuanphamquocit@gmail.com · github.com/Tuan24455
