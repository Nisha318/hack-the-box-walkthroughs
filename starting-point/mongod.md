# Hack The Box Walkthrough – MongoDB Enumeration

![image](https://github.com/user-attachments/assets/2b901d58-7720-40d1-aff1-6301012f5b59)

## Task 1  
**Question:** How many TCP ports are open on the machine?  
**Answer:** `2`
![image](https://github.com/user-attachments/assets/d8b8be81-6834-4757-9f16-90896f7b0f09)

---

## Task 2  
**Question:** Which service is running on port 27017 of the remote host?  
**Answer:** `MongoDB 3.6.8`
![image](https://github.com/user-attachments/assets/1e5a55c9-b7c8-4984-bce4-3adcb7396584)

---

## Task 3  
**Question:** What type of database is MongoDB? (Choose: SQL or NoSQL)  
**Answer:** `NoSQL`

---

## Task 4  
**Question:** What is the command name for the Mongo shell that is installed with the `mongodb-clients` package?  
**Answer:** `mongosh`

![image](https://github.com/user-attachments/assets/7378867e-dada-4668-b58c-5373fad0924f)

![image](https://github.com/user-attachments/assets/866aa59c-bc93-46df-97f9-5cdb13b018e2)

![image](https://github.com/user-attachments/assets/5d7dc9f5-ffcd-4271-af8c-4dc341973c29)


![image](https://github.com/user-attachments/assets/c5c4b0a7-4ff1-4f1b-a974-69c9080a682d)

---

## Task 5  
**Question:** What is the command used for listing all the databases present on the MongoDB server?  
**Answer:** `show dbs`

![image](https://github.com/user-attachments/assets/1df1ce1f-c967-4a46-9e4c-06a19556fafc)

---

## Task 6  
**Question:** What is the command used for listing out the collections in a database?  
**Answer:** `show collections`

![image](https://github.com/user-attachments/assets/74647880-da1e-482e-814b-4f98e130ce0b)


---

## Task 7  
**Question:** What is the command used for dumping the content of all the documents within the collection named `flag` in a format that is easy to read?  
**Answer:** `db.flag.find().pretty()`

![image](https://github.com/user-attachments/assets/7305f14e-f9e9-49f6-9ac2-067992249c75)


---

## Final Submission  
- ✅ **Submit root flag:**  
`1b6e6fb359e7c40241b6d431427ba6ea`
