Case Study: Hospital Management System

The Hospital Management System is a large-scale software system that allows:

• Online patient registration
• Appointment booking with doctors
• Electronic Medical Record (EMR) management
• Billing and payment processing
• Laboratory management and report generation
• Pharmacy inventory and medicine management
• Administrative control of staff and hospital operations

This system involves multiple stakeholders including:

• Patients
• Doctors
• Nurses
• Hospital Administrators
• Hospital Management Authorities
• Insurance Providers
• Payment Gateway Providers

SDLC Models Compared
Waterfall Model

• Sequential development approach
• Each phase must be completed before moving to the next
• Suitable when requirements are fixed and clearly defined
• Less flexible to requirement changes

Incremental Development Model

• System developed in multiple increments
• Each increment delivers functional modules (registration, billing, pharmacy, etc.)
• Allows partial system deployment
• Suitable when requirements evolve gradually

Spiral Model

• Risk-driven and iterative model
• Combines development with continuous risk analysis
• Suitable for large-scale and high-risk healthcare systems
• Supports requirement changes and security enhancements

Requirements Engineering Process

Two versions of requirements documents are included:

Initial Requirements

• Initial draft prepared
• Basic functional requirements defined
• Basic non-functional requirements specified
• Included patient registration and appointment scheduling
• Limited security and performance specifications

Revised Requirements

• Revised after stakeholder validation
• Added OTP-based login verification
• Added Inpatient (IPD) and Outpatient (OPD) management
• Included laboratory report upload feature
• Added pharmacy inventory tracking
• Implemented role-based access control
• Improved performance benchmarks
• Enhanced encryption and data security
• Included insurance claim processing

This demonstrates:

• Requirement evolution
• Stakeholder feedback incorporation
• Change management process

Branching and Merging Strategy

The following Git strategy was followed:

• main branch → Final stable submission
• requirements-draft branch → Initial version (v1)
• requirements-revision branch → Updated version (v2)
• report-development branch → Report writing and comparison

Workflow

• Created requirements_v1 in requirements-draft branch
• Reviewed and merged into main branch
• Created requirements_v2 in requirements-revision branch
• Compared changes and updated documentation
• Final report merged into main branch

This strategy ensures:

• Proper version control
• Requirement traceability
• Clear change tracking
• Structured development workflow

Risk and Change Management Considerations

Key risks identified:

• High patient load during emergencies
• System downtime affecting hospital operations
• Data security and privacy threats
• Integration failure with laboratory and pharmacy systems
• Healthcare regulation changes
• Insurance processing delays

Risk mitigation approach:

• Load balancing for high traffic
• Regular database backups
• Strong encryption mechanisms
• Compliance with healthcare data standards
• Continuous monitoring and testing

The Spiral Model was found to be most suitable because:

• It supports continuous risk analysis
• It allows iterative improvement
• It adapts to regulatory and operational changes

Conclusion

After comparison:

• Waterfall model is suitable for stable and fixed requirements
• Incremental model is suitable for phased module delivery
• Spiral model is most appropriate for large-scale, high-risk systems like Hospital Management System

Author

Name: Aditya P Naik
Course: IS3332-1
Department: Information Science & Engineering
Institution: NMAMIT
Academic Year: 2025-2026
