🚀 Employee Dashboard (Angular)

A modern Angular standalone application showcasing a clean employee dashboard architecture using standalone components, routing, services, and unit testing.
Designed with current Angular best practices, the project is lightweight, maintainable, and production-ready.

✨ Key Features

✅ Standalone Angular architecture (no NgModules)
📊 Employee dashboard with total employee count
📋 Employee list view
🔁 Shared service layer for employee data
🧭 Client-side routing
🧪 Unit testing with Angular TestBed
🎨 Clean and consistent UI layout
🛠️ Tech Stack

Angular (Standalone Components)

TypeScript
Angular Router
CSS
Vitest / Angular Testing Utilities

📁 Project Structure


<img width="290" height="216" alt="image" src="https://github.com/user-attachments/assets/607b3989-488f-42fd-b86f-400e4a52a712" />


🚀 Getting Started
1️⃣ Install dependencies
npm install
2️⃣ Run the application
ng serve

Open in browser:
http://localhost:4200
🧪 Running Unit Tests
ng test

✅ Current Test Coverage
Employee service business logic
Application bootstrap with routing support

All tests are fully compatible with standalone components and router-based architecture.

🧠 Testing Strategy
🎯 Focuses on business logic and application bootstrapping
🧱 Avoids brittle UI-specific tests
🔌 Uses provideRouter() for routing-aware tests
⚡ Keeps the test suite fast, stable, and maintainable

This mirrors real-world Angular team practices.

📌 Design Decisions

Standalone components for simplified dependency management
Service layer to centralize employee data
Routing configured at application level
Unit tests written where they add real value

🔮 Possible Enhancements

🌐 REST API integration using HttpClient
✏️ Employee CRUD operations
🔐 Authentication & authorization
🎨 UI enhancements with a component library
🧪 Additional component-level unit tests

👤 Author
Developed as part of a professional Angular assignment, demonstrating practical frontend architecture, modern Angular patterns, and effective unit testing.


