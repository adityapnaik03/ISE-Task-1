# Case Study: Hospital Management System

The Hospital Management System (HMS) is a large-scale software system that allows:

- Online patient registration
- Appointment booking and doctor scheduling
- Electronic Medical Record (EMR) management
- Billing and payment processing
- Laboratory test management and report upload
- Pharmacy inventory management
- Administrative control of staff, departments, and hospital operations

This system involves multiple stakeholders including patients, doctors, nurses, administrators, hospital authorities, insurance providers, and payment gateway providers.

---

# SDLC Models Compared

## Waterfall Model
A sequential development approach where each phase must be completed before the next begins.  
Suitable when requirements are fixed and clearly defined.

## Incremental Development Model
The system is developed in multiple increments.  
Each increment delivers functional components such as patient registration, billing, laboratory management, and pharmacy modules.  
Suitable when requirements evolve gradually.

## Spiral Model
Risk-driven model combining iterative development and risk analysis.  
Suitable for large-scale and high-risk systems like hospital management systems where data security and system reliability are critical.

---

# Requirements Engineering Process

Two versions of requirements documents are included:

## Initial Requirements

Initial draft  
Basic functional and non-functional requirements  
Included patient registration and appointment scheduling  
Limited security and performance specifications  

## Revised Requirements

Revised after validation  
Added OTP-based login verification  
Added Inpatient (IPD) and Outpatient (OPD) management  
Included laboratory and pharmacy integration  
Improved performance benchmarks  
Added scalability enhancements  
Implemented role-based access control  
Enhanced security and data encryption  
Included insurance claim processing  

This demonstrates requirement evolution and change management.

---

# Branching and Merging Strategy

The following Git strategy was followed:

- `main` branch → Final stable submission  
- `requirements-draft` branch → Initial version (v1)  
- `requirements-revision` branch → Updated version (v2)  
- `report-development` branch → Report writing and comparison sections  

## Workflow:

- Created `requirements_v1` in `requirements-draft` branch  
- Merged into `main` after review  
- Created `requirements_v2` in `requirements-revision` branch  
- Compared changes and updated documentation  
- Final report merged into `main` branch  

This strategy ensures:

- Version control  
- Traceability  
- Clear change tracking  
- Structured development process  

---

# Risk and Change Management Considerations

Key risks identified:

- High patient load during emergencies  
- System downtime affecting hospital operations  
- Payment gateway failure  
- Data security and privacy threats  
- Integration failure between modules (lab, pharmacy, billing)  
- Healthcare regulation changes  

The Spiral Model was found to be most suitable for handling such risks due to its risk-driven and iterative approach.

---

# Conclusion

After comparison:

- Waterfall is suitable for stable requirements.
- Incremental model is suitable for phased module delivery.
- Spiral model is most appropriate for large-scale, high-risk systems like Hospital Management System due to its risk-driven approach.

---

# Author

**Name:** Aditya P Naik  
**Course:** IS3332-1  
**Department:** Information Science & Engineering  
**Institution:** NMAMIT  
**Academic Year:** 2025-2026  
