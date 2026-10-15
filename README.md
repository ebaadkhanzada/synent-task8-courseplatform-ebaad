# synent-task8-courseplatform-ebaad
---

### README.md for Task 8: Online Course Platform (Full Stack)

```markdown
# Synent Task 8: Online Course Platform (Full Stack MERN)

## Objective
To develop a full-stack e-learning management platform (LMS) where users can register, view courses, enroll using Razorpay payment integration (Test Mode), and access learning modules, while administrators can manage course content.

## Steps Performed
1. Constructed a RESTful backend using Node.js and Express.js, supported by Mongoose schemas for Users and Courses.
2. Implemented JWT (JSON Web Token) authentication and authorization middleware for secure login and route protection.
3. Integrated the Razorpay Payment API to generate payment orders on the server and verify HMAC SHA256 signatures upon checkout completion.
4. Developed an interactive frontend dashboard supporting course filtering, video modal viewing, and enrollment state updates.
5. Handled error states, loading spinners, and local fallback configurations for client testing environments.

## Tools Used
- **Frontend Stack:** HTML5/CSS3/JavaScript (React / Vanilla JS)
- **Backend Stack:** Node.js, Express.js
- **Database:** MongoDB, Mongoose ODM
- **Authentication & Security:** JSON Web Tokens (JWT), Crypto
- **Payment Gateway:** Razorpay SDK (Test Mode)
- **Development Tools:** Postman, VS Code, Git, GitHub

## Outcome in Brief
An end-to-end full-stack e-learning application supporting secure candidate registration, course catalog management, checkout flow, and progress tracking.

---

## Getting Started

### 1. Backend Setup
```bash
cd backend
npm install
npm start
