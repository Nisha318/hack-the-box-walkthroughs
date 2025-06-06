# Hack The Box Walkthrough – Redis Enumeration


![image](https://github.com/user-attachments/assets/25577386-9aaa-43ae-989f-9d268e4a368d)

## Task 1  
**Question:** Which TCP port is open on the machine?  
**Answer:** `6379`

![image](https://github.com/user-attachments/assets/fecdf8f7-e049-40cd-a4c9-da6fe2786f74)


---

## Task 2  
**Question:** Which service is running on the port that is open on the machine?  
**Answer:** `redis`

---

## Task 3  
**Question:** What type of database is Redis? Choose from the following options:  
(i) In-memory Database  
(ii) Traditional Database  
**Answer:** `In-memory Database`

---

## Task 4  
**Question:** Which command-line utility is used to interact with the Redis server?  
**Answer:** `redis-cli`

---

## Task 5  
**Question:** Which flag is used with the Redis command-line utility to specify the hostname?  
**Answer:** `-h`
![image](https://github.com/user-attachments/assets/390d22c9-90ed-4a00-92f1-b056b3634d08)

---

## Task 6  
**Question:** Once connected to a Redis server, which command is used to obtain the information and statistics about the Redis server?  
**Answer:** `info`
![image](https://github.com/user-attachments/assets/162fdec0-f72d-4026-92de-735db42cf49f)

---

## Task 7  
**Question:** What is the version of the Redis server being used on the target machine?  
**Answer:** `5.0.7`
![image](https://github.com/user-attachments/assets/b4231bd5-1fa0-41e5-a761-8e5d81bda5c4)

---

## Task 8  
**Question:** Which command is used to select the desired database in Redis?  
**Answer:** `select`
![image](https://github.com/user-attachments/assets/56ecc58b-2a3c-43a8-b885-9fbf2f409ba5)

---

## Task 9  
**Question:** How many keys are present inside the database with index 0?  
**Answer:** `4`

---

## Task 10  
**Question:** Which command is used to obtain all the keys in a database?  
**Answer:** `keys *`
![image](https://github.com/user-attachments/assets/a32cc729-fd55-4977-9e40-6068c6f4a420)

---

## Final Submission  
- ✅ **Submit root flag:**  
`03e1d2b376c37ab3f5319922053953eb`
