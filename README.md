# API Testing – Urban.Grocers

![QA](https://img.shields.io/badge/Testes-API-blue)
![Tool](https://img.shields.io/badge/Postman-Test%20Execution-orange)
![Documentation](https://img.shields.io/badge/apiDoc-Reference-informational)
![Bug Tracking](https://img.shields.io/badge/Jira-Bug%20Reports-orange)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/celia-bruno)

---

## 📌 Project Overview

This project was developed during API testing studies within the **Urban.Grocers** application.  
The goal was to test newly added endpoints related to product kits and delivery cost estimation via **Order and Go**.  
All testing was supported by the API documentation (**apiDoc**) and executed using **Postman**.

---

## 🎯 Project Goals

Validate two new features from the Urban.Grocers API:

1. **Add products to a kit** (`POST /api/v1/kits/{id}/products`);
2. **Check availability and cost of delivery via Order and Go** (`POST /order-and-go/v1/delivery`).

---

## 🔧 Technologies and Tools

- **Postman** — request execution  
- **apiDoc** — API reference  
- **Google Sheets** — test checklist  
- **Jira** — bug tracking  

---

## ▶️ How to Run

1. Open **Postman**.  
2. Import the request collection or configure endpoints manually according to **apiDoc**.  
3. Set up parameters and payloads based on the values defined in the checklist.  
4. Execute the requests, validate the responses, and compare them with the acceptance criteria.  
5. Report any bugs in **Jira**, following best practices (steps, expected result, actual result, priority).

---

## 🧾 Results

- Test checklist covering both positive and negative scenarios;  
- Requests executed in **Postman** according to acceptance criteria;  
- Bugs reported in **Jira**;  
- Evidence consolidated in Google Sheets;

---

## 📚 What I Learned

- How to interpret API requirements and translate them into test cases;  
- How to create and organize a structured test checklist;  
- How to use Postman to send requests and validate responses;  
- How to report bugs clearly in Jira;

---

## 💡 Future Improvements

- Automate API tests using tools like **Newman** or **RestAssured**;

---

## 📂 Project Files

- ✅ [Test Checklist – Google Sheets](https://docs.google.com/spreadsheets/d/1to5l7gcZbPaLRpjes2cyLjXu4T6rHYGv/edit?usp=sharing&ouid=117698170295509867083&rtpof=true&sd=true)  
- 🐞 [Bug Reports – Jira](https://celiadepaivabruno.atlassian.net/jira/software/c/projects/S4/issues?jql=project%20%3D%20%22S4%22%20ORDER%20BY%20created%20DESC)

---
