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
## 🖼️ Imagens

<img width="1347" height="649" alt="Captura de tela de 2025-08-28 18-17-54" src="https://github.com/user-attachments/assets/0e00a0aa-fbc4-47f2-b370-2af54b3c086e" />

<img width="1347" height="649" alt="Captura de tela de 2025-08-28 18-17-59" src="https://github.com/user-attachments/assets/d721e62c-b6af-4aec-8670-99eb57b801e7" />

<img width="1347" height="649" alt="Captura de tela de 2025-08-28 18-18-04" src="https://github.com/user-attachments/assets/0b354319-28e0-45d8-a82a-61d7e5a6e191" />

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
