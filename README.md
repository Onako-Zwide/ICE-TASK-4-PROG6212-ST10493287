# ICE-TASK-4-PROG6212-ST10493287

# Project Description

Contract Claim Data Manager is a C# .NET 8 console application developed for managing lecturer claim records. The application uses Entity Framework Core with SQLite to store claim data permanently. It supports adding, viewing, updating and deleting claims, exporting claim information to a text file, and executing a direct ADO.NET query.

# Features

The application provides the following features:

Add new lecturer claims.
View all stored claims.
Update the status of a claim.
Delete a claim after confirmation.
Validate hours worked between 1 and 160.
Validate that the hourly rate is greater than zero.
Calculate the total claim amount automatically.
Export claims to claim_summary.txt.
Read the exported text file and display its contents.
Count claim records using a direct ADO.NET SELECT COUNT(*) query.

# Validation

The application validates:

Hours worked must be between 1 and 160.
Hourly rate must be greater than zero.
Claim IDs must be valid positive numbers.

