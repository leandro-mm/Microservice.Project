# .Net Core MVC API with MongoDB and RabbitMQ

## 📌 Project Objective
The goal of this project is to **create two .NET MVC API** that:  
- Connects to a **MongoDB** database.  
- Sends messages to a **RabbitMQ** message broker.  

This project demonstrates integration between an API, a NoSQL database, and a message queue to enable scalable and decoupled communication between services.  

---

## ⚙️ Requirements to Run the Project
Before running the project, make sure you have the following installed:

- [✅ .NET SDK 8.0.400](https://dotnet.microsoft.com/en-us/download)  
- [✅ Docker Desktop for Windows](https://www.docker.com/products/docker-desktop/)  
- [✅ Visual Studio Code](https://code.visualstudio.com/)  

---

## 🚀 Getting Started
1. Clone the Play.Inventory repositorie:
```bash
   git clone https://github.com/leandro-mm/Play.Inventory.git
```
2. Clone the Play.Catalog repositorie:
```bash
    git clone https://github.com/leandro-mm/Play.Catalog.git
```
3. Clone the Play.Common repositorie:
```bash
    git clone https://github.com/leandro-mm/Play.Common.git
```
## Create the NuGet Package
build Play.Common project and then generate the NuGet Package
1. Navigate to Play.Common\src\Play.Common
2. Run the command   
```bash
    dotnet pack -o ..\..\..\packages\
```
3. 
