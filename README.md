# Snowball Express Database Project

## **Overview**
This project involves designing and managing a relational database for Snowball Express, a company specializing in organizing ski vacations across popular destinations. By utilizing structured data organization, this project enhances operational efficiency, supports informed decision-making, and streamlines package customization to improve customer satisfaction and business outcomes.

---

## **Objectives**
- **Develop a Relational Database**: Build a well-structured database to store and manage ski vacation details efficiently.
- **Perform Data Management**: Ensure the accuracy and relevance of information through data entry, updates, and modifications.
- **Establish Table Relationships**: Create meaningful links between data tables to facilitate structured organization and analysis.
- **Generate Insights**: Leverage queries, forms, and reports for comprehensive data analysis and effective presentation.

---

## **Key Steps and Results**

### **1. Table Creation and Data Entry**
- **Importance**: Tables form the foundation of the database by organizing data into manageable units. Properly designed tables prevent data redundancy and maintain consistency.

- **Steps and Outcomes**:
  - **Table Creation**:
    - Designed the `Resorts` table with key fields: Resort ID (primary key), Resort Name, Location, Price Per Person (PP), and Lodging Type.
    - Standardized data types, field sizes, and descriptions for clarity and consistency.
  - **Data Entry**:
    - Input records for prominent resorts, including Steamboat Springs, Winterpark, and Park City.
    - Imported supplementary data from the "Destinations to Add" database to expand offerings.
    - Manually entered new deals, such as:
      - Deer Valley (Utah): $219 per person.
      - Lake Tahoe (Nevada): $199 per person.
  - **Data Modifications**:
    - Corrected location errors (e.g., Squaw Valley from New Mexico to Nevada).
    - Removed Aspen due to pricing concerns, ensuring affordability-focused offerings.

---

### **2. Table Relationships**
- **Importance**: Establishing relationships between tables ensures data integrity, eliminates duplication, and enables advanced analysis through relational queries.

- **Steps and Outcomes**:
  - Created a one-to-many relationship between the `Resorts` and `Transportation` tables.
  - Enforced referential integrity with cascading updates, ensuring consistency across related records.

---

### **3. Queries**
- **Importance**: Queries extract valuable insights by filtering, sorting, and analyzing data based on specific criteria. They enable better decision-making and tailored reporting.

- **Steps and Outcomes**:
  - Developed multiple queries for detailed analysis:
    - **Without Lodging Type Query**: Simplified view excluding lodging information.
    - **Price Range by Location**: Sorted resorts by location and price in ascending order.
    - **Price Low to High**: Ranked resorts from the most affordable to the most expensive.
    - **Affordable**: Filtered resorts costing less than $300.
    - **In My Dreams**: Highlighted high-end resorts costing over $400.
    - **Gas Costs**: Integrated `Resorts` and `Transportation` data to find gas-inclusive options under $275.

---

### **4. Forms and Reports**
- **Importance**: Forms streamline data entry, while reports summarize and present key insights, enhancing user accessibility and communication.

- **Steps and Outcomes**:
  - **Resorts Form**:
    - Created a user-friendly interface for adding, viewing, and editing resort details.
  - **Resorts Report**:
    - Generated a comprehensive report summarizing resort data for analysis and presentation.

---

## **Recommendations**
- **Regular Updates**: Continuously update the database with new deals and remove outdated information to maintain accuracy.
- **Trend Analysis**: Use queries to analyze pricing and customer preferences for strategic planning.
- **Enhanced Reporting**: Generate detailed reports to support customer engagement and business presentations.

---

## **Tools Used**
- **Microsoft Access**: Facilitated database creation, management, and querying.
- **Relational Database Design Principles**: Ensured logical and efficient data organization for streamlined operations.

---

## **Project Resources**
- **Database File**: [Ski Locations START FILE](https://github.com/StephVergil/Snowball-Express-Database-Project/blob/main/Ski%20Locations%20%20START%20FILE-%20StephanieVergil.accdb)
- **Instructions Document**: [Snowball Express Database Instructions](https://github.com/StephVergil/Snowball-Express-Database-Project/blob/main/Snowball%20Express%20Database%20-%20INSTRUCTIONS%20-%20FALL%202023-1.docx.pdf)
- [Microsoft Access Documentation](https://support.microsoft.com/en-us/access)
- [Database Design Best Practices](https://learn.microsoft.com/en-us/sql/relational-databases/database-design-basics)
- [Relational Database Concepts](https://www.oracle.com/database/what-is-a-relational-database/)
- [Access Query Design Guide](https://support.microsoft.com/en-us/access-query-design)

---

## **Conclusion**
The Snowball Express Database project underscores the significance of effective data management in organizing and optimizing travel packages. By leveraging structured table relationships, insightful queries, and professional reports, this project provides a robust tool for customizing ski vacations while enhancing operational efficiency.

---

## **Disclaimer**
This project was conducted in a controlled academic environment. Unauthorized use or distribution of project assets may violate ethical guidelines and legal regulations.
