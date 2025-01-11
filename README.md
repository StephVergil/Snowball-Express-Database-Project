# Snowball Express Database Project

This project involves creating and managing a database for Snowball Express, a company specializing in organizing ski vacations across popular destinations. The database organizes resorts, transportation, and pricing to cater to customer needs and streamline package customization.

---

### Objectives
- Create and manage a relational database to organize ski vacation details.
- Perform data entry, modification, and deletion to maintain up-to-date information.
- Establish relationships between tables for enhanced data organization.
- Generate queries, forms, and reports to analyze and present data effectively.

---

### Key Steps and Results

#### **1. Table Creation and Data Entry**
- **Table Creation**:  
  - Created a `Resorts` table with fields: Resort ID (primary key), Resort Name, Location, Price Per Person (PP), and Lodging Type.  
  - Adjusted field sizes and descriptions for clarity and consistency.

- **Data Entry**:  
  - Added records for resorts such as Steamboat Springs, Winterpark, and Park City.  
  - Imported additional data from the "Destinations to Add" database.  
  - Entered new deals manually:  
    - Deer Valley (Utah): $219 per person.  
    - Lake Tahoe (Nevada): $199 per person.

- **Data Modifications**:  
  - Corrected Squaw Valley's location from New Mexico to Nevada.  
  - Deleted the Aspen record for affordability concerns.

---

#### **2. Table Relationships**
- Established a one-to-many relationship between the `Resorts` table and the `Transportation` table.  
- Enforced referential integrity with cascading updates enabled.

---

#### **3. Queries**
- Created and saved multiple queries for data analysis:
  - **Without Lodging Type Query List**: Excluded Lodging Type field.
  - **Price Range by Location**: Sorted by location and price in ascending order.
  - **Price Low to High**: Organized data by price in ascending order.
  - **Affordable**: Displayed resorts costing less than $300.
  - **In My Dreams**: Displayed resorts costing more than $400.
  - **Gas Costs**: Combined `Resorts` and `Transportation` data to display resorts with gas costs under $275.

---

#### **4. Forms and Reports**
- **Resorts Form**: Created a simple form for data entry and viewing.
- **Resorts Report**: Generated a detailed report for the `Resorts` table.

---

### Recommendations
- Regularly update the database with new deals and remove outdated information.
- Use queries to analyze pricing trends and identify cost-effective packages.
- Leverage relationships and reports to streamline package creation and customer presentations.

---

### Tools Used
- **Microsoft Access**: For database creation, management, and analysis.
- **Relational Database Design**: To establish meaningful connections between tables.

---

### Project Resources
- **Project Link (Database)**: [Ski Locations START FILE](https://github.com/StephVergil/Snowball-Express-Database-Project/blob/main/Ski%20Locations%20%20START%20FILE-%20StephanieVergil.accdb)
- **Project Link (Instructions)**: [Snowball Express Database Instructions](https://github.com/StephVergil/Snowball-Express-Database-Project/blob/main/Snowball%20Express%20Database%20-%20INSTRUCTIONS%20-%20FALL%202023-1.docx.pdf)
- [Microsoft Access Documentation](https://support.microsoft.com/en-us/access)

---

### Conclusion
The Snowball Express Database project highlights the value of structured data management for organizing travel packages. By leveraging table relationships, queries, and reports, this project provides a comprehensive tool for customizing ski vacation offerings efficiently.

---

### Disclaimer
This project was conducted in a controlled academic environment. Unauthorized use or distribution of project assets may violate ethical guidelines and legal regulations.
