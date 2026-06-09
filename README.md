# HR Management System (Angular)

A full-featured HR / Employee Management System built using Angular.  
This project demonstrates real-world frontend architecture with modular design, routing, reactive forms, and service-based API communication.

---

## 🚀 Features

- Employee Dashboard
- Add / Edit / Delete Employees
- Reactive Forms with Validation
- Angular Routing & Navigation
- Service-based Architecture
- Mock API Integration (db.json / REST API)
- Modular folder structure
- Responsive UI design

---

## 🛠️ Tech Stack

- Angular 21+
- TypeScript
- HTML5
- CSS3
- JSON Server (mock backend)

---

## 📁 Project Structure

HR Management System
│
└── src/
    │
    ├── app/
    │   │
    │   ├── core/
    │   │
    │   ├── features/
    │   │   ├── dashboard/
    │   │   ├── employee-list/
    │   │   └── leave-list/
    │   │
    │   ├── services/
    │   │   └── employee.service.ts
    │   │
    │   ├── app.routes.ts
    │   └── app.config.ts
    │
    ├── assets/
    │
    └── styles.css


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/hr-management-system.git
cd hr-management-system
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
ng serve
```

Open in browser:
```bash
http://localhost:4200
```

📦 Build for Production
```bash
ng build
```

Output will be generated in:
```bash
dist/
```

## API Setup (if using db.json)

If using JSON Server:
```dash
npx json-server db.json
```

### 🎯 Learning Outcomes
- Angular component architecture
- Service-based API communication
- Routing and lazy loading basics
- Reactive form handling
- Scalable folder structure design

### ⭐ Future Improvements
- JWT Authentication
- Role-based access control
- Advanced analytics dashboard
- Pagination & filtering
- Deployment on cloud

## 📌 Note

This project is created for learning and portfolio purposes and demonstrates frontend development skills using Angular.
