# student-database-sql-analysis
# 📊 Student Database – SQL Analysis Project  

## 📌 Overview  
This project demonstrates how to perform **SQL data analysis** using a sample `student` dataset in the `dummy` database.  
The database records students' **names, marks, and departments**, and the project showcases how to query, analyze, and organize this data.  

The SQL tasks include:  
- Filtering and sorting records  
- Performing aggregation and grouping  
- Using subqueries for advanced analysis  
- Creating reusable **views**  
- Demonstrating **joins** with another table  
- Adding **indexes** for performance optimization  

---

## 📂 Database Schema  

**Database:** `dummy`  
**Table:** `student`  

### Table Structure  
| Column        | Data Type      | Description                     |
|---------------|----------------|---------------------------------|
| student_name  | VARCHAR(200)   | Name of the student             |
| mark          | INT            | Marks scored by the student     |
| department    | VARCHAR(200)   | Student’s department of study   |

### Sample Data  
| student_name | mark | department |
|--------------|------|------------|
| haridharani  | 24   | BCA        |
| madhu        | 56   | BCA        |
| jayasrii     | 36   | BCA        |
| shanmu       | 27   | CE         |
| lavanya      | 16   | MD         |
| shalini      | 17   | AGRI       |

---

## ⚡ Core SQL Queries  

### 1. Display all student records  
```sql
SELECT * FROM student;
