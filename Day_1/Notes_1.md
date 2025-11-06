# 📅 Day 1 — IDC 21 Days of SQL Challenge  

Today I kicked off the **IDC 21 Days of SQL Challenge** by refreshing my SQL basics —  
a strong foundation for understanding data more deeply and writing cleaner queries.  

---

## 🧠 What I Learned Today  

- Retrieving data using the **SELECT** statement and defining tables with **FROM**  
- Avoiding `SELECT *` in production to improve query efficiency and readability  
- Exploring tables safely using the **LIMIT** clause  
- Viewing and understanding data structure effectively  
- Using **DISTINCT** to find unique records and avoid duplicates  
- Adding **comments** to explain logic clearly within SQL scripts  
- Understanding that SQL keywords are **case-insensitive**, though uppercase improves readability  


## 🧩 Practice Queries  

Here are the queries I wrote to complete **Day 1** tasks of the IDC SQL Challenge:  

1️⃣ **Retrieve all columns from the `patients` table**  
```sql
SELECT * FROM patients;
```

2️⃣ **Select only the patient_id, name, and age columns from the patients table**
```sql
SELECT patient_id, name, age FROM patients;
```

3️⃣ **Display the first 10 records from the services_weekly table**
```sql
SELECT * FROM services_weekly LIMIT 10;
```
