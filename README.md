# Applying Filters to SQL Queries

## Project Overview
In this project, I used SQL to analyze login attempt data — a key skill in cybersecurity for detecting unusual access patterns. I applied commands like `SELECT`, `FROM`, `WHERE`, `ORDER BY`, and `NOT` to:

- Retrieve all login attempts from a database, sorted by date and time to track user activity over time.
- Filter out employees not in the 'Information Technology' department to narrow the focus during security reviews.

I also learned some other commands that I’m sure will be useful in my day-to-day work as a cybersecurity professional. This hands-on practice helped me strengthen my ability to query and analyze data for potential security insights and incident investigation.

## Skills Practiced
- Writing SQL queries for filtering and sorting data  
- Using logic operators (e.g., `NOT`, `ORDER BY`)  
- Analyzing logs and user activity  

## Example Commands
```sql
SELECT * 
FROM log_in_attempts 
ORDER BY login_date, login_time;

SELECT * 
FROM employees 
WHERE NOT department LIKE 'Information Technology';
```

## Tools Used
- MariaDB SQL
- Command-line interface

---

## Contact
- 📍 Dublin, Ireland  
- 📧 vinicius99ie@gmail.com  
- 🔗 [LinkedIn](https://linkedin.com/in/viniciusalprado)
