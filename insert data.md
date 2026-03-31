# 🚔 Crime Management System – Sample Insert Data

This file contains all SQL `INSERT` queries in one place.  
Each table includes **10 records** for testing.

---

## 📌 SQL Insert Statements

```sql
-- 🧑‍⚖️ Criminal Table
INSERT INTO Criminal (Name, DOB, Crime_Type, Arrest_Date) VALUES
('Ravi', '1990-05-12', 'Theft', '2023-01-10'),
('Amit', '1988-03-22', 'Robbery', '2023-02-15'),
('John', '1992-07-18', 'Fraud', '2023-03-12'),
('Ali', '1985-09-10', 'Murder', '2023-04-05'),
('Sara', '1995-12-01', 'Cyber Crime', '2023-05-20'),
('Neha', '1993-06-14', 'Kidnapping', '2023-06-18'),
('Rahul', '1991-11-11', 'Drugs', '2023-07-25'),
('David', '1987-08-08', 'Smuggling', '2023-08-30'),
('Priya', '1996-02-02', 'Assault', '2023-09-10'),
('Karan', '1994-04-04', 'Theft', '2023-10-12');

-- 🧍 Victim Table
INSERT INTO Victim (Name, DOB, Address, Contact_Number) VALUES
('Ankit', '2000-01-01', 'Delhi', '9000000001'),
('Pooja', '1999-02-02', 'Mumbai', '9000000002'),
('Raj', '1998-03-03', 'Pune', '9000000003'),
('Simran', '2001-04-04', 'Delhi', '9000000004'),
('Arjun', '1997-05-05', 'Chennai', '9000000005'),
('Meena', '1996-06-06', 'Jaipur', '9000000006'),
('Rohit', '1995-07-07', 'Bhopal', '9000000007'),
('Sneha', '1994-08-08', 'Kolkata', '9000000008'),
('Vikas', '1993-09-09', 'Noida', '9000000009'),
('Kajal', '1992-10-10', 'Delhi', '9000000010');

-- 📁 Crime Case Table
INSERT INTO Crime_Case (Case_Type, Case_Status, Crime_Location, Filed_Date) VALUES
('Theft', 'Open', 'Delhi', '2023-01-01'),
('Robbery', 'Closed', 'Mumbai', '2023-02-01'),
('Fraud', 'Open', 'Pune', '2023-03-01'),
('Murder', 'Under Trial', 'Lucknow', '2023-04-01'),
('Cyber Crime', 'Open', 'Delhi', '2023-05-01'),
('Kidnapping', 'Closed', 'Jaipur', '2023-06-01'),
('Drugs', 'Open', 'Goa', '2023-07-01'),
('Smuggling', 'Closed', 'Kolkata', '2023-08-01'),
('Assault', 'Open', 'Patna', '2023-09-01'),
('Theft', 'Under Trial', 'Chandigarh', '2023-10-01');

-- 👮 Police Officer Table
INSERT INTO Police_Officer (Name, Officer_Rank, Contact_Number, Station_ID) VALUES
('Officer1', 'Inspector', '8000000001', 101),
('Officer2', 'SI', '8000000002', 102),
('Officer3', 'Constable', '8000000003', 103),
('Officer4', 'Inspector', '8000000004', 104),
('Officer5', 'SI', '8000000005', 105),
('Officer6', 'Constable', '8000000006', 106),
('Officer7', 'Inspector', '8000000007', 107),
('Officer8', 'SI', '8000000008', 108),
('Officer9', 'Constable', '8000000009', 109),
('Officer10', 'Inspector', '8000000010', 110);

-- 🔍 Evidence Table
INSERT INTO Evidence (Case_ID, Evidence_Type, Location_Found, Collected_Date) VALUES
(1, 'Fingerprint', 'Delhi', '2023-01-02'),
(2, 'Weapon', 'Mumbai', '2023-02-02'),
(3, 'Document', 'Pune', '2023-03-02'),
(4, 'DNA', 'Lucknow', '2023-04-02'),
(5, 'Laptop', 'Delhi', '2023-05-02'),
(6, 'Phone', 'Jaipur', '2023-06-02'),
(7, 'Drugs', 'Goa', '2023-07-02'),
(8, 'Cash', 'Kolkata', '2023-08-02'),
(9, 'Knife', 'Patna', '2023-09-02'),
(10, 'Clothes', 'Chandigarh', '2023-10-02');
