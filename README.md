# Digital Skill Connection

**Tagline:** Connecting Skills to Opportunities

**Student Name:** NTWAZANGABO Fabrice  
**Student ID:** 29264 
**Course:** INSY 8311 – Database Development with PL/SQL  
**Instructor:** Eric Maniraguha  
**Academic Year:** 2026–2027 (Semester I)

---

## 1. Problem Statement

Rwanda has many skilled workers in trades such as plumbing, electrical installation, mechanics, cleaning, and tailoring. However, most of them work in the informal sector. Customers struggle to find trusted and verified workers, while skilled workers find it difficult to get regular customers and fair payment. Current solutions (social media groups and personal contacts) lack verification, rating systems, secure payments, and proper record-keeping. This leads to mistrust, underemployment, and lost income opportunities.

## 2. Project Objectives

**Main Objective:**  
To develop a digital marketplace that connects customers with verified skilled workers in Rwanda using an Oracle database and PL/SQL.

**Specific Objectives:**
- To design and implement a normalized database for managing customers, workers, job requests, payments, and ratings.
- To develop PL/SQL procedures, functions, packages, and triggers that automate business processes.
- To implement a secure payment and commission system.
- To create a rating and complaint management system that builds trust.
- To develop an interactive analytics dashboard as the innovation component.

## 3. Data Source

The project will primarily use the **Home Service Customer Satisfaction** dataset from Kaggle (approximately 300,000 records). This dataset contains service types, technician performance, response times, and customer ratings. Additional sample data representing Rwandan districts and local service categories will be created for testing.

**Dataset Link:** https://www.kaggle.com/datasets/mohamed444ashraf/rating-predicition

## 4. Planned Tables

- Customers  
- Workers  
- Skills / Service_Categories  
- Job_Requests  
- Payments_Transactions  
- Ratings_Reviews  
- Complaints  
- Administrators  

All tables will be designed in **Third Normal Form (3NF)**.

## 5. Planned PL/SQL Features

- **Procedures:** Register worker, submit job request, process payment, calculate commission  
- **Functions:** Calculate average worker rating, check worker availability  
- **Cursors:** Process multiple pending jobs and update ratings  
- **Packages:** `pkg_booking`, `pkg_payment`, `pkg_rating`, `pkg_admin`  
- **Triggers:** Auto-update worker rating, prevent booking of inactive workers, audit logging  
- **Exception Handling:** Proper management of failed payments and invalid operations  

## 6. Innovation

An interactive **Analytics Dashboard** will be developed using **Power BI** (or Oracle APEX). The dashboard will connect directly to the Oracle database and display key performance indicators such as:

- Number of completed jobs by skill category  
- Average worker ratings  
- Platform commission earned  
- Top-performing workers  
- Pending complaints  

## 7. Repository Structure
DigitalSkillConnection/

├── docs/
│   ├── research/
│   │   └── research_log.md
│   ├── proposal/
│   └── presentation/
├── data/
└── README.md

## 8. References

Ashraf, M. (2026). *Home Service Customer Satisfaction* [Dataset]. Kaggle.  
National Institute of Statistics of Rwanda. (2025). *Labour Force Survey Annual Report 2024*.  
Rani, U., & Furrer, M. (2021). Digital labour platforms and new forms of flexible work in developing countries. *Competition & Change*, 25(2), 212–236.  
United Nations Development Programme. (2026). *Youth Employment Brief: Analysis of Skills Matching with Private Sector Needs*.  
World Bank. (2026). *Rwanda’s Skills Training Delivers Jobs and Opportunity for Youth*.
