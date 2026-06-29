# Database Analysis

## Objective

Before implementing the database, the team will analyze the official Karnataka Police FIR Entity Relationship (ER) Diagram to understand how crime-related information is organized.

The goal is to understand:

- The purpose of each table.
- The relationships between tables.
- Which tables are required for the chatbot.
- Which tables are required for crime analytics.
- Which tables are required for machine learning models.

This analysis will guide the implementation of the database, backend APIs, and AI-powered conversational system.

# 1. CaseMaster

## Purpose

CaseMaster is the central table of the Karnataka Police FIR database.

Each record in this table represents a single criminal case (FIR) and serves as the primary reference for all investigation-related information.

Other tables such as complainants, victims, accused persons, investigation details, courts, and crime classifications are connected to CaseMaster.

Without CaseMaster, the remaining tables cannot be linked together into a complete investigation.

## Important Information Stored in CaseMaster

The CaseMaster table contains the primary details of every criminal case.

Examples of important information include:

- FIR Number
- Crime Number
- Registration Date
- Police Station
- Crime Category
- Crime Type
- District
- Case Status
- Brief Facts of the Case
- Geographic Location (if available)

These fields are expected to be frequently used by the chatbot while answering investigator queries.
