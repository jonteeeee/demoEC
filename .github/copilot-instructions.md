# Copilot Instructions

## 🎯 Goal
- Learn Django basics (Model / View / Template)
- Understand Python syntax and structure
- Write simple and readable code

---

## 🧱 Architecture

- Use feature-based apps (products / accounts / orders)
- Each app should act as an independent mini-MVC

### Model (Fat Model)
- Put business logic in models.py
- Models should contain behavior, not just data

### View
- Keep views thin（viewは薄く）
- Handle request and response only
- Delegate logic to models

### Template
- Organize templates per app
- Use: templates/{app_name}/

---

## 🚫 Constraints

- Do NOT put business logic in views.py
- Do NOT create service layer（今回は禁止）
- Avoid unnecessary abstraction
- Do NOT introduce complex design patterns

---

## 🧠 Coding Style

- Use single if statements not use 'else' or 'elif' until necessary（elseは極力禁止）
- Use minimum nested if statements until necessary
- Use minimum loops until necessary
- Prefer early return（早期return）
- Keep nesting shallow（ネストを浅く）
- Prioritize readability over cleverness


---

## 🔐 Authentication

- Use Django default User model
- Use email as username
- Do NOT create custom User model

---

## 🤖 Copilot Guidance

- Prefer Django standard patterns
- Generate simple and clear code
- Avoid over-engineering
- Focus on readability and maintainability

---

## 📌 Notes

This project is for learning purposes.
Prioritize simplicity and clarity over scalability.