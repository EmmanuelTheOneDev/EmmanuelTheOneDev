<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=Emmanuel%20Oyewale%20Oyediran&fontSize=38&fontColor=ffffff&fontAlignY=38" alt="banner" />
</p>

<h3 align="center">Software Engineer · Java &amp; Python · Backend, Testing and Data Structures</h3>

<p align="center">
  📍 Lagos, Nigeria &nbsp;|&nbsp;
  ✉️ <a href="mailto:diranoye2020@gmail.com">diranoye2020@gmail.com</a> &nbsp;|&nbsp;
  💻 <a href="https://github.com/EmmanuelTheOneDev">GitHub</a> &nbsp;|&nbsp;
  🔗 <a href="https://www.linkedin.com/in/emmanuel-oyediran/">LinkedIn</a> &nbsp;|&nbsp;
  🐦 <a href="https://twitter.com/sega_dudu">X</a> &nbsp;|&nbsp;
  📄 <a href="https://github.com/EmmanuelTheOneDev/EmmanuelTheOneDev/blob/main/Emmanuel_Oyewale_CV.pdf">Download CV</a>
</p>

---

## Professional Summary

Software engineer in training, building backend applications in **Java** and **Python**. My habit is to write the test that proves a bug exists before I fix it, and I keep my repositories public so my commit history shows how I work. I came to software from five years in marketing and business development, so I think about the person using the product as well as the code behind it.

Currently moving from console applications and layered architecture into **Spring Boot**, **databases** and **REST APIs**. I also work with data: writing **SQL** queries and turning the results into insights with **Power BI**.

---

## Technical Skills

| | |
|---|---|
| **Languages** | Java, Python, JavaScript, SQL, HTML5/CSS3 |
| **Backend** | Spring Boot (REST controllers, services, repositories, DTOs, global exception handling), layered architecture |
| **Databases** | MongoDB ([MealPlanner](https://github.com/EmmanuelTheOneDev/MealPlanner)), MySQL ([practice repo](https://github.com/EmmanuelTheOneDev/MySQL)) |
| **Data Analysis** | SQL queries in MySQL ([MySQL repo](https://github.com/EmmanuelTheOneDev/MySQL)), interpreting query results, Power BI (dashboards and reports, learning) |
| **Testing** | JUnit 5, pytest, unittest, test-driven development, edge-case and failure-path tests |
| **Fundamentals** | OOP, enums, exceptions, Big O, hand-built ArrayList, LinkedList, Stack, Queue, Set and Map |
| **Tools** | Git, GitHub, IntelliJ IDEA, VS Code, Maven |

[![Skills](https://skillicons.dev/icons?i=java,spring,python,js,html,css,mysql,mongodb,git,github,idea,vscode)](https://skillicons.dev)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## Projects

### 🎫 Traffic Ticketing System — [`Ticketing_Traffic_App`](https://github.com/EmmanuelTheOneDev/Ticketing_Traffic_App)
`Java` · `JUnit 5` · `Layered architecture`

- Models officers, offences, vehicles, drivers, tickets, payments and challenges across repositories, services, DTOs and mappers.
- Validates every input (ticket number, location, offender, vehicle, active officer, active offence) *before* calculating a fee or saving, and applies escalating fines to repeat offenders.
- **350 tests, all passing.**

### 🏦 Multi-Bank Account and ATM System — [`Accounts_V2`](https://github.com/EmmanuelTheOneDev/Accounts_V2)
`Java` · `JUnit 5` · `NUBAN validation`

- Banks, accounts, ATM flows and inter-bank transfers, with account numbers checked using the NUBAN checksum.
- **Bug found and fixed:** a transfer to a non-existent account used to take the money from the sender first. The receiver is now validated before any withdrawal, and tests assert that balances are unchanged on every failure path (ghost receiver, wrong password, insufficient balance, negative amount, wrong-bank sender).

### 🍽️ Meal Planner — [`MealPlanner`](https://github.com/EmmanuelTheOneDev/MealPlanner)
`Python` · `pytest` · `MongoDB`

- Service, repository and DTO layers over a MongoDB repository, with custom exceptions and a daily calorie summary.

### 🧩 Data Structures From Scratch — [`My-Projects`](https://github.com/EmmanuelTheOneDev/My-Projects)
`Java` · `JUnit 5`

- Also see [`My-Python-Projects`](https://github.com/EmmanuelTheOneDev/My-Python-Projects) for my Python work.
- Implemented my own Stack, Queue, LinkedList, ArrayList, Set and Map (including hash-based indexing and collision handling), plus LeetCode-style problems.

### 📅 Schedulo *(private, in progress)*
`Java` · `Spring Boot`

- Authentication module with registration and login, DTOs, custom exceptions, a global exception handler and service tests.

### 🪝 Desk Hanger *(in progress)*

- Currently being built. Details and repository link to be added.

---

## Engineering Log: Mistakes I Found and Fixed

I keep a record of the bugs I've hit, because that is where most of my learning has come from.

| Bug | Cause | Fix |
|---|---|---|
| Money lost in a transfer to a missing account | Withdraw ran before the receiver was validated | Validate everything first, then act; tests check balances on failure |
| `ConcurrentModificationException` | Removing from a list inside a for-each loop | Use an iterator or `removeIf` |
| Duplicate IDs after deleting a record | ID was `list.size() + 1` | Use a counter that never goes down |
| Negative array index in my own Map | `hashCode() % length` can be negative | Use `Math.floorMod` |

---

## Currently Working On

- Connecting databases to Spring Boot applications
- Data analysis: SQL queries and Power BI reports
- Securing Schedulo with password hashing (BCrypt)
- JavaScript and the DOM, to connect front-end pages to my APIs
- Smart contracts with Solidity (just starting)

---

## Education

**Software Engineering Training — SemiColon Africa**, Lagos, Nigeria · 2026 – Present
Project-based training in Java, Python, JavaScript, data structures, testing and software architecture.

---

## Let's Connect

I'm open to internship, graduate and junior backend roles (Java, Spring Boot, Python).

<p align="center">
  <a href="mailto:diranoye2020@gmail.com">Email</a> ·
  <a href="https://github.com/EmmanuelTheOneDev">GitHub</a> ·
  <a href="https://github.com/EmmanuelTheOneDev/EmmanuelTheOneDev/blob/main/Emmanuel_Oyewale_CV.pdf">CV</a> ·
  <a href="https://www.linkedin.com/in/emmanuel-oyediran/">LinkedIn</a> ·
  <a href="https://twitter.com/sega_dudu">X</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" alt="footer" />
</p>
