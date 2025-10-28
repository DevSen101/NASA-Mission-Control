# 🌍 NASA Mission Control  
> A complete **backend mission control system** that connects humanity to the stars — fetching real data from **SpaceX API** and **NASA’s Kepler dataset**, storing it securely in MongoDB, and powering future space analytics.  

---

## 🚀 Overview  

**NASA Mission Control** is a professional-grade backend project that integrates **real-world space mission data**.  
It demonstrates backend engineering excellence using **Node.js**, **Express**, **MongoDB**, and **external APIs**.  

The project identifies **habitable planets** from the NASA Kepler dataset (CSV file) and fetches **live launch data** from the SpaceX API — both stored and managed in MongoDB through Mongoose models.  

---

## 🌌 Features  

✅ Fetches **live SpaceX Launch Data** using REST API  
✅ Parses **NASA Kepler CSV Dataset** to identify habitable planets  
✅ Provides **REST API endpoints** for planets and launches  
✅ Handles **async operations**, **errors**, and **promises** efficiently  
✅ Uses **Mongoose ODM** for structured data modeling  
✅ Secured with **dotenv** environment configuration  
✅ Ready for **Dockerization**, **AWS deployment**, and **CI/CD pipeline**  

---

## ⚙️ Tech Stack  

| Layer | Technologies |
|-------|---------------|
| Backend | Node.js, Express.js |
| Database | MongoDB with Mongoose |
| External APIs | SpaceX API, Kepler CSV Dataset |
| Tools | Axios, Nodemon, Dotenv |
| DevOps (Planned) | Docker, AWS EC2, CI/CD (GitHub Actions) |

---

## 🧪 API Endpoints

| Method | Endpoint        | Description               |
| ------ | --------------- | ------------------------- |
| GET    | `/planets`      | Get all habitable planets |
| GET    | `/launches`     | Get all launches          |
| POST   | `/launches`     | Add a new launch          |
| DELETE | `/launches/:id` | Abort a specific launch   |

---

## 🖼️ Screenshots

**Dashboard**
<img width="1440" height="900" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/29725603-383c-4bbb-9992-76c0fd3fdf9e" />

**Upcoming Launches**
<img width="1440" height="900" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/27bc3318-529f-4eb6-a7eb-579dc3b7c37a" />

**History**
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/31349aa9-600b-48c6-bac8-8f279e2a6782" />

---

## 🧰 Future Enhancements

* 🐳 Docker containerization for easier deployment
* ☁️ AWS deployment (EC2 + S3 + CI/CD Pipeline)
* 📡 Realtime dashboard for upcoming launches
* 🔒 Advanced authentication and role-based access
* 📊 GraphQL integration for flexible data queries

---

## 👨‍💻 Developed By

**Dev Kumar Sen**
