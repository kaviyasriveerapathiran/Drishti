# Database Design

## Reference

The Drishti platform follows the official Karnataka Police FIR Entity Relationship (ER) Diagram provided as part of the Datathon resources.

Instead of designing a custom database schema, Drishti uses the official database structure to ensure compatibility with the provided datasets and to support realistic crime investigation workflows.

The database is centered around the **CaseMaster** table, which acts as the primary entity connecting FIRs, complainants, victims, accused persons, police officers, courts, crime classifications, and investigation records.

## Core Modules

The official database can be divided into the following modules:

1. Case Management
2. People (Complainants, Victims, Accused)
3. Crime Classification
4. Investigation
5. Police Administration
6. Geography
7. Legal Information

Each module will be documented in the following sections.
