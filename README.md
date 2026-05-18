# 🛴 Urban Scooter — Full-Cycle QA Testing

Comprehensive quality assurance project covering web UI, mobile app, and API testing for the Urban Scooter scooter rental platform.

---

## 🎯 Project Overview

Urban Scooter is a scooter rental platform with two components: a **web application** for customers to place and track orders, and a **mobile app** for couriers to manage deliveries. This project validates both components across all layers — UI, form validation, mobile flows, and backend API endpoints.

---

## 🐞 Key Findings — 33 Bugs Documented

| Layer | Test Type | Bugs Found |
|-------|-----------|-----------|
| Web UI | Order status screen checklist (35 checks) | 2 |
| Web UI | Form field validation (9 fields) | 10 |
| Mobile App | Courier app test cases (14 cases) | 9 |
| API | Endpoint validation (6 endpoints) | 10 |
| **Total** | | **33** |

All bugs were documented in **Jira** with reproduction steps, expected vs. actual results, and severity level.

---

## 🛠️ Tech Stack

![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

- **Jira** — bug tracking and reporting
- **Postman** — API endpoint testing
- **Android Studio** — mobile app testing via emulator (Android 9.0)
- **Google Sheets** — test checklists, validation tables, and test cases
- **Chrome DevTools** — web UI inspection

---

## 📋 Testing Scope

### Task 1 — Theory & SQL
Theoretical QA questions covering: test design techniques, HTTP protocols, client-server architecture, databases, mobile testing, and SQL queries.

### Task 2 — Web Application Testing
**Order Status Screen — Checklist (35 items)**
- Validated all order status states, transitions, and UI elements
- Tested order cancellation flow
- Verified delayed order behavior
- **2 bugs found** (SCRUM-22, SCRUM-23)

**Form Field Validation — 9 fields tested:**
First name, Last name, Address, Metro station, Phone, Delivery date, Rental period, Color, Comment
- Applied equivalence partitioning and boundary value analysis
- **10 bugs found** (SCRUM-24 through SCRUM-33)

### Task 3 — Mobile App Testing (Android)
**14 test cases** executed on Android Studio emulator (Android 9.0):
- Login / logout flows
- Order list and card interactions
- Accept / complete order flows
- Offline behavior
- Screen orientation

**9 bugs found** (SCRUM-1 through SCRUM-9)

### Task 4 — API Testing
**6 endpoints** tested via Postman:

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/v1/courier/login` | POST | Courier login |
| `/api/v1/orders` | POST | Create order |
| `/api/v1/orders/track` | GET | Get order status |
| `/api/v1/orders/accept/:id` | PUT | Accept order |
| `/api/v1/orders/cancel` | PUT | Cancel order |
| `/api/v1/orders/finish/:id` | PUT | Complete order |

**10 bugs found** (SCRUM-10 through SCRUM-19)

---

## 📁 Project Documentation

Full test documentation available here:

📊 **[View Test Documentation (Google Sheets)](https://docs.google.com/spreadsheets/d/1xl7CKNx_CTVRO3g8MCcTt2gfmxxCV2BoObYl5FoEXSo/edit?usp=sharing)**

Includes:
- ✅ Task 1 — Theory & SQL answers
- ✅ Task 2 — Order status checklist + results
- ✅ Task 2 — Form field validation table
- ✅ Task 3 — Mobile test cases + results
- ✅ Task 4 — API testing checklist + results

---

## 📊 Impact

Identified and documented **33 critical bugs** across all layers of the application — including missing form validations, broken mobile UI flows, and API endpoints returning incorrect status codes. Every bug was reported with clear reproduction steps and severity level, enabling the development team to prioritize fixes before user-facing deployment.

---

## 👩‍💻 Author

**Marjorie Valencia** — QA Engineer  
📧 valenciar.marjorie@gmail.com  
💼 [linkedin.com/in/marjorievalencia](https://linkedin.com/in/marjorievalencia)  
🌐 [Portfolio](https://boulder-fuschia-da7.notion.site/Portafolio-QA-Marjorie-Valencia-3526e1d78b6c8042a234ecf1b73cd49e)
