# 📆 Product API - Spring Boot with MongoDB
A **Spring Boot REST API** for managing products using **MongoDB**.

### 🔗 Live API & Demo
- 🌐 [Product API](https://nixxlo-8080.bytexl.dev/api/products)
- 🎥 [Demo Video](https://drive.google.com/file/d/1Wv6kYSuUqjgx3g2jkb382MRzd1gRVTDb/view?usp=sharing)
- 📚 [GitHub Repository](https://github.com/yashdongre12/product.git)

## ✨ Features
- Uses **MongoDB**
- RESTful API for **CRUD operations**
- Built with **Spring Boot**

## ⚙️ Setup
### 1️⃣ Clone Repository
```sh
git clone https://github.com/yashdongre12/product.git
cd product
```
### 2️⃣ Configure MongoDB
Update `application.properties` with your MongoDB credentials:
```properties
spring.data.mongodb.host=bytexldb.com
spring.data.mongodb.port=5050
spring.data.mongodb.database=db_43asngdub
spring.data.mongodb.username=user_43asngdub
spring.data.mongodb.password=p43asngdub
spring.data.mongodb.authentication-database=admin
```
### 3️⃣ Run Application
```sh
mvn spring-boot:run
```

## 🛠️ API Endpoints
| Method  | Endpoint            | Description           |
|---------|--------------------|----------------------|
| **GET**    | `/api/products`     | Get all products    |
| **GET**    | `/api/products/{id}` | Get product by ID   |
| **POST**   | `/api/products`     | Add a product       |
| **PUT**    | `/api/products/{id}` | Update a product   |
| **DELETE** | `/api/products/{id}` | Delete a product   |

## 📚 Product Model
```json
{
  "id": "string",
  "name": "string",
  "price": "number"
}
```

## 💡 Contributing
Submit **issues** or **pull requests** to improve the project.

---
![Screenshot (32)](https://github.com/user-attachments/assets/dd07467c-e5b3-40f9-bc07-1c1f8c89ccce)
![Screenshot (33)](https://github.com/user-attachments/assets/d4436893-ca48-415e-a438-49e8f89a809f)

