# employee-attrition-performance-eda-visualization

### Here are the questions I tried to answer:
- **Is there discremination based on sex, ethnicity, etc. when hiring/promoting employee.**
- **How does the rating work**
- **When an employ can expect to be promoted.**

### The main outputs are:
- **There is an issue with the varibale EmployeeID, some employee were rated years before being hired.**
- **There is no discrimination between woman and man, or between different ethnic (exepeted maybe toward Latinos in CA)**
- **The parameters influenceing promotion are:**
    - **salary**, 
    - **distance from home**,
    - **age**,
    - **and year with the company and manager.**
- **When an employ can expect to be promoted. It is difficult to answer tis question due to the issue with EmployeeID, and because only the last promotion is repported.**

[1: Load and clean the data](#1)

[2: Exploratory Data Analysis](#2)
- [2.1: Who are the employees?](#2)
- [2.2: When are performed the performance reviews?](#2.2)
- [2.3: What think the emloyees of their reviews?](#2.3)
- [2.4: What are the factors influncing the performance](#2.4)
    - [2.4.1: Model selection](#2.4.1)
    - [2.4.2 : Feature importance](#2.4.2)
- [2.5: Who is promoted?](#2.5)
    - [2.5.1: Sankey Diagram](#2.5)
