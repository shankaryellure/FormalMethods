# Traffic Collision Avoidance System (TCAS)

This project focuses on the design and validation of a Traffic Collision Avoidance System (TCAS), a safety-critical system essential for preventing mid-air collisions by monitoring airspace, identifying risks, and providing pilots with advisories.

## Project Overview

The TCAS project was executed in three phases:

1. **Requirements and UML Class Design**:
   - Developed a UML class diagram to represent the main components such as Aircraft, Pilot, Transponder, and TCAS itself.
   - Defined their attributes, behaviors, and interactions for a clear system overview.

2. **Formal Specification Using OCL**:
   - Enhanced the UML model with Object Constraint Language (OCL) to specify rules and constraints.
   - Added invariants, preconditions, and postconditions to ensure logical consistency.

3. **Validation and Testing**:
   - Validated the TCAS model using the Unified Specification Environment (USE) tool.
   - Created object diagrams to simulate real-world scenarios and fixed errors like constraint violations and association mismatches.

## Key Features

- **Real-time Monitoring**: Tracks aircraft altitude, bearing, and proximity.
- **Advisory Generation**: Issues Traffic Advisories (TAs) and Resolution Advisories (RAs) to pilots.
- **Error-Free Validation**: Ensures compliance with defined constraints using UML, OCL, and USE tools.

## Tools Used

- **UML (Unified Modeling Language)**: To design and communicate system architecture.
- **OCL (Object Constraint Language)**: For specifying detailed system constraints.
- **USE Tool**: For testing and validating the model's logical consistency.

## Results

- A fully validated TCAS model that meets all system requirements.
- Identified and resolved critical issues during validation, ensuring robustness and reliability.

## Future Enhancements

- **Incorporating Machine Learning**: To predict collision risks and enhance advisory accuracy.
- **Real-time Data Integration**: Adding real-world airspace changes such as weather, restricted zones, and traffic conditions.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/shankaryellure/FormalMethods.git
