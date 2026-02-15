Case Study: Hospital Management System

The Hospital Management System is a large-scale software system that allows:

Online patient registration
Appointment booking with doctors
Electronic Medical Record (EMR) management
Billing and payment processing
Laboratory and pharmacy management
Administrative control of staff and hospital operations

This system involves multiple stakeholders including patients, doctors, nurses, administrators, hospital management authorities, insurance providers, and payment gateway providers.

SDLC Models Compared
Waterfall Model

A sequential development approach where each phase must be completed before the next begins.
Suitable when requirements are fixed and clearly defined.

Incremental Development Model

The system is developed in multiple increments.
Each increment delivers functional components such as patient registration, appointment scheduling, billing, etc.
Suitable when requirements evolve gradually.

Spiral Model

Risk-driven model combining iterative development and risk analysis.
Suitable for large-scale and high-risk systems like hospital systems where data security and performance are critical.

Requirements Engineering Process

Two versions of requirements documents are included:

Initial Requirements

Initial draft
Basic functional and non-functional requirements
Basic patient registration and appointment system
Limited security and performance specifications

Revised Requirements

Revised after stakeholder validation
Added OTP-based login verification
Added inpatient (IPD) and outpatient (OPD) management
Included laboratory report upload feature
Added pharmacy inventory tracking
Improved performance benchmarks
Added role-based access control
Enhanced data encryption and security measures
Included insurance claim processing

This demonstrates requirement evolution and change management.

Branching and Merging Strategy

The following Git strategy was followed:

main branch → Final stable submission
requirements-draft branch → Initial version (v1)
requirements-revision branch → Updated version (v2)
report-development branch → Report writing and comparison sections

Workflow:

Created requirements_v1 in requirements-draft branch.
Merged into main after review.
Created requirements_v2 in requirements-revision branch.
Compared changes and updated documentation.
Final report merged into main branch.

This strategy ensures:

Version control
Traceability
Clear change tracking
Structured development process

Risk and Change Management Considerations

Key risks identified:

High patient load during emergencies
System downtime affecting hospital operations
Data security and privacy threats
Integration failure with laboratory and pharmacy systems
Policy changes in healthcare regulations

The Spiral Model was found to be most suitable for handling such risks due to its continuous risk assessment and iterative development.

Conclusion

After comparison:

Waterfall is suitable for stable hospital requirements.
Incremental model is suitable for phased module delivery (registration, billing, pharmacy, etc.).
Spiral model is most appropriate for large-scale, high-risk systems like Hospital Management System due to its risk-driven and flexible approach.

Author

Name: Aditya P Naik
Course: IS3332-1
Department: Information Science & Engineering
Institution: NMAMIT
Academic Year: 2025-2026
