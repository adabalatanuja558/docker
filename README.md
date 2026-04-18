# docker
# 🐳 Docker Learning & Documentation

This repository documents my **hands-on learning journey in Docker and containerization** as part of my DevOps preparation.

It includes structured notes, architecture explanations, Dockerfile concepts, and practical command usage.

---

## 📚 Repository Contents

### 📄 1. Docker Introduction.docx
- Basics of Docker  
- What is containerization  
- Why Docker is used  
- Real-world problem (Dev vs Prod issue)  
- Key concepts like images, containers, registry  

---

### 📄 2. docker class 2 architecture.docx
- Detailed Docker Architecture  
- Docker Client, Host, and Registry  
- Workflow explanation  
- How Docker components interact  

---

### 📄 3. Dockerfile COMPONENTS class 3.docx
- Dockerfile fundamentals  
- Instructions like:
  - FROM  
  - RUN  
  - CMD  
  - COPY  
  - EXPOSE  
- How to build custom images  

---

### 📄 4. README.md
- Summary of Docker concepts  
- Interview questions & answers  
- Basic commands  

---

## 🧠 Key Concepts Covered

- Containerization  
- Docker Architecture  
- Images vs Containers  
- Docker Registry  
- Dockerfile  
- Container lifecycle  

---

## ⚙️ Hands-on Practice

- Pulled images from Docker Hub  
- Created and managed containers  
- Used port mapping  
- Checked logs and debugging  
- Practiced real-time Docker commands  

---

## 💻 Important Docker Commands

```bash
docker pull nginx
docker run -d -p 8080:80 nginx
docker ps
docker ps -a
docker stop <container_id>
docker start <container_id>
docker logs <container_id>
docker exec -it <container_id> bash
