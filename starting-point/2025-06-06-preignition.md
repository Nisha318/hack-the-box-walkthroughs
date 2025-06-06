# Hack The Box Walkthrough – Directory Brute-Forcing & Web Enumeration

![image](https://github.com/user-attachments/assets/33b41bdd-d3c6-421e-91f2-dcf12a6781f4)



## Task 1  
**Question:** Directory Brute-forcing is a technique used to check a lot of paths on a web server to find hidden pages. Which is another name for this?  
(i) Local File Inclusion  
(ii) dir busting  
(iii) hash cracking  
**Answer:** `dir busting`

---

## Task 2  
**Question:** What switch do we use for Nmap's scan to specify that we want to perform version detection?  
**Answer:** `-sV`

---

## Task 3  
**Question:** What does Nmap report is the service identified as running on port 80/tcp?  
**Answer:** `http`

![image](https://github.com/user-attachments/assets/6cfd9d2c-ffa0-4513-96dc-91666107319d)

![image](https://github.com/user-attachments/assets/d1bd63ee-db63-4df6-a2f5-0d6dd5dc53e8)

---

## Task 4  
**Question:** What server name and version of service is running on port 80/tcp?  
**Answer:** `nginx 1.14.2`

---

## Task 5  
**Question:** What switch do we use to specify to Gobuster we want to perform dir busting specifically?  
**Answer:** `dir`

---

## Task 6  
**Question:** When using Gobuster to dir bust, what switch do we add to make sure it finds PHP pages?
**Answer:** '-x php'

---

## Task 7  
**Question:** What page is found during our dir busting activities?  
**Answer:** `admin.php`
![image](https://github.com/user-attachments/assets/af11215f-ef29-40af-a037-749d3c305ad0)

![image](https://github.com/user-attachments/assets/7b591478-fb30-47c5-b211-1fdc9b0aade7)

---

## Task 8  
**Question:** What is the HTTP status code reported by Gobuster for the discovered page?  
**Answer:** `200`

---
![image](https://github.com/user-attachments/assets/5573a7c9-efe3-46cf-b916-14683a02a888)


![image](https://github.com/user-attachments/assets/d5263045-9baa-406c-ae84-c821ba92c9c6)


## Final Submission  
- ✅ **Submit root flag:**  
`6483bee07c1c1d57f14e5b0717503c73`
