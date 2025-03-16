
---

# **FastAPI Hello World** 🌍  

A simple **FastAPI** project setup using **UV Package Manager**.  

## **Setup Instructions**  

### **1️⃣ Create and Open Project Folder**  
```bash
# On Desktop
mkdir FastAPI-HelloWorld  
cd FastAPI-HelloWorld  
```

### **2️⃣ Open in VS Code**  
```bash
code .
```

### **3️⃣ Initialize UV Environment**  
```bash
uv init --package helloworld  
cd helloworld  
```

### **4️⃣ Install Dependencies**  
```bash
uv add fastapi  
uv add uvicorn  
```

### **5️⃣ Run FastAPI App**  
```bash
uv run src.helloworld.main:app --reload  
```

## **Project Structure**  
```
FastAPI-HelloWorld/
│── src/
│   ├── helloworld/
│   │   ├── main.py  # FastAPI app entry point
│── pyproject.toml  # Project configuration
│── README.md  # Project documentation
│── .gitignore  # Git ignore file
```

## **Endpoints**  
| Method | Endpoint   | Description          |
|--------|-----------|----------------------|
| GET    | `/`       | Welcome message      |
| GET    | `/hello`  | Returns "Hello World" |

## **Contributing**  
Feel free to open issues or submit PRs! 🚀  

---
