# 🛍️ Ecommerce Control Microservice  
**Microservices project for e-commerce control** developed in **Java** with **Gradle** and **Docker** support.  

This project aims to create a solid foundation for an e-commerce system using a microservices architecture, following best development practices and prepared for scalability.

---

## 🚀 Technologies Used

- ☕ **Java 17+** — Main language
- 🛠️ **Gradle (Kotlin DSL)** — Modern build system
- 🐳 **Docker & Docker Compose** — Orchestration and containers
- 📦 **Spring Boot** *(coming soon)* — For rapid API development
- 🧩 **Microservices Architecture** — Foundation for distributed and modular systems

---

## 📂 Project Structure

```
Ecommerce_Control_Microservice_Gradle_Java/
├── Dockerfile # Main container configuration
├── docker-compose.yml # Service orchestration
├── build.gradle.kts # Gradle configuration (Kotlin DSL)
├── settings.gradle.kts # Gradle module configuration
├── gradlew # Gradle Wrapper for Linux/Mac
├── gradlew.bat # Gradle Wrapper for Windows
├── start-dev.sh # Script for local environment startup
└── src/ # Project source code
```

---

## ⚡ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MKawan/Ecommerce_Control_Microservice_Gradle_Java.git
cd Ecommerce_Control_Microservice_Gradle_Java
```

### 2️⃣ Build the Project
```bash
./gradlew clean build
```

### 3️⃣ Start Containers with Docker
```bash
docker-compose up --build
```

### 4️⃣ Run in Development Environment
```bash
./start-dev.sh
```

---

## 🔮 Next Steps

- Create modules for *User Service*, *Product Service*, and *Order Service*
- Integrate *Spring Boot* for REST APIs
- Set up a database (*PostgreSQL/MySQL*)
- Implement *Swagger/OpenAPI* for documentation
- Add automated tests (*JUnit & Mockito*)
- Configure *CI/CD* with *GitHub Actions*

---

## 🧠 Best Practices Applied

✅ Modular and scalable code  
✅ Containers for standardized environments  
✅ Gradle Wrapper for cross-system compatibility  
✅ Structure ready for future expansion  

---

## 📄 License

This project is licensed under the *MIT License*.  
Feel free to use, modify, and contribute! 😎

---

## 🤝 Contribution

Contributions are always welcome!  
Follow these steps:

1. Create a branch for your feature
   ```bash
   git checkout -b my-feature
   ```

2. Commit your changes
   ```bash
   git commit -m "feat: adds new feature"
   ```

3. Push to the remote repository
   ```bash
   git push origin my-feature
   ```

---

## 📬 Contact

**Author**: MKawan  
📧 **Email**: mateusoliveira.cursos@outlook.com  
🐙 **GitHub**: https://github.com/MKawan
