# Basketball Apartment Complex Database

A database design project built for a final class project. It uses **basketball player names as dummy/fake data**, but the schema + relationships are meant to simulate a **real apartment complex management database** (tenants, leases, payments, amenities, maintenance, etc.).

This repo includes the **CSV datasets** you can import into a relational database, plus **.odg diagram files** used to design/communicate the schema (ERD, functional dependencies, architecture model).  [oai_citation:0‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)

---

## What’s in this project

### Dataset files (CSV / Excel)
You can use these to populate tables in your database:

- `ApartmentData.csv`  [oai_citation:1‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `TenantData.csv`  [oai_citation:2‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `LeaseData.csv` (and `LeaseData1.csv`)  [oai_citation:3‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `PaymentData.csv` (and `PaymentData1.csv`)  [oai_citation:4‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `AmenityData.csv`  [oai_citation:5‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `Used_AmenityData.csv`  [oai_citation:6‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `MaintenanceData.xlsx`  [oai_citation:7‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  

There are also `.xlsx` versions of some datasets (useful for viewing/editing).  [oai_citation:8‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)

### Diagrams / design artifacts (`.odg`)
These are the design visuals for the project:

- `ERDiagram.odg`  [oai_citation:9‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `FunctionalDependency.odg`  [oai_citation:10‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `3SchemaArchitectureModel.odg`  [oai_citation:11‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  

> Tip: `.odg` files open best with **LibreOffice Draw**.

### Docs / writeups
Supporting documentation and deliverables:

- `3SchemaArchitectureModel.docx`  [oai_citation:12‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `RelationalAlgebra.docx`  [oai_citation:13‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `HTMLPHP.docx` and `php.docx`  [oai_citation:14‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  

### Zips / submissions
Packaged project exports/submission files:

- `ApartmentDB.zip`  [oai_citation:15‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  
- `FinalProject.zip`  [oai_citation:16‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  

---

## Schema overview (high level)

This project models a simplified apartment complex system:

- **Apartments**: unit info and attributes
- **Tenants**: tenant profiles (dummy data uses basketball player names)
- **Leases**: connects tenants to apartments over time
- **Payments**: rent/payment records tied to a lease/tenant
- **Amenities**: list of available amenities
- **Used Amenities**: join table tracking which tenants/leases used which amenities
- **Maintenance**: maintenance records (provided as an Excel file)

Use the ERD (`ERDiagram.odg`) as the source of truth for keys + relationships.  [oai_citation:17‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)

---

## How to use

### Option A: Import the CSVs into a database (recommended)
1. Create tables in your DB (MySQL / PostgreSQL / SQL Server / SQLite)
2. Import CSV data into matching tables
3. Run your queries / reports

**Common import approaches**
- MySQL Workbench “Table Data Import Wizard”
- pgAdmin “Import/Export Data”
- SQLite: DB Browser for SQLite → Import → Table from CSV

> Make sure your table columns match the CSV headers and types (dates, numeric amounts, IDs, etc.).

### Option B: Use the provided zip exports
If your class/project used a specific DB tool/export, check:
- `ApartmentDB.zip`
- `FinalProject.zip`  [oai_citation:18‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  

These likely contain the packaged project materials as submitted.

---

## Opening the diagrams (`.odg`)
- Install LibreOffice
- Open LibreOffice Draw
- File → Open → select `ERDiagram.odg`, `FunctionalDependency.odg`, etc.  [oai_citation:19‡GitHub](https://github.com/jimmytran1/Basketball-Apartment-Complex-Database/)  

---

## Project notes
- The names are **synthetic** (basketball players) and are used only to make the dataset feel realistic.
- The goal of the project is **database design**: relationships, normalization, dependencies, and queryability.

---

## License
If you want, add a license (MIT is common for school projects). Otherwise, GitHub defaults to “no license,” meaning others shouldn’t reuse without permission.

---

## Author
Jimmy Tran
