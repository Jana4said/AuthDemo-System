# AuthDemo System (COMP 2406)

A **Deno-based authentication and session management system** built to securely manage users, hashed passwords, and active sessions.  
This project demonstrates how to handle session creation, expiration, and analysis using database-backed logic.

---

## Features
- Implements **user login** and **session tracking**
- Uses `crypto.randomUUID()` to generate unique session IDs  
- Hashes and verifies passwords for secure authentication  
- Automatically **expires inactive sessions**
- Stores filenames and submission contents in the database  
- Provides an **analysis page** showing total submissions and empty answers  
- Returns structured **HTTP responses** for user errors and login validation  

---

## Core Concepts
- Secure authentication flow (Login → Session → Expiration)
- **Password hashing and verification**
- Managing active user sessions in memory and database
- **Error handling** for invalid credentials and expired sessions
- Database schema design for user and submission data
- Data analysis generation in Deno  

---

##  File Overview
| File | Description |
|------|--------------|
| `Comp2406-assign4-janasaid.txt` | Implementation notes, session management logic, and analysis explanation |

---

## Technologies Used
- **Deno Runtime (JavaScript)**
- **SQLite Database**
- **Crypto API**
- **HTTP Routing**
- **Hashing and Sessions**

---
**Gana Said**  
Bachelor of Computer Science (AI Stream) – Carleton University  
📧 [janasaid@cmail.carleton.ca](mailto:janasaid@cmail.carleton.ca)

---

## How It Works
1. Users log in with credentials.  
2. Server hashes passwords and validates against stored data.  
3. A unique session ID is created using `crypto.randomUUID()`.  
4. Session is tracked and expires after inactivity.  
5. Admin pages display total submissions and analysis results.

---
 *This project showcases authentication, session management, and secure server-side programming in Deno.*
