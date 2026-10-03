# 🛒 Product Management REST API

A production-ready REST API built with Node.js and Express, integrated with a PostgreSQL relational database for complete product data lifecycle management (CRUD).

---

## 🚀 Tech Stack

- **Node.js**: Server-side JavaScript runtime environment
- **Express**: Minimalist web framework for API routing and middleware
- **PostgreSQL**: Enterprise-grade relational database for data persistence
- **node-postgres (`pg`)**: Official PostgreSQL client featuring connection pooling
- **Postman**: API testing, HTTP request execution, and endpoint verification
- **DBeaver**: Database GUI administration, querying, and schema inspection

---

## 📌 API Endpoints

| Method | Endpoint | Description | Success Status |
| :--- | :--- | :--- | :--- |
| **GET** | `/products` | Retrieves all registered products | `200 OK` |
| **POST** | `/products` | Inserts a new product into the database | `201 Created` |
| **PUT** | `/products/:id` | Updates an existing product by its ID | `200 OK` |
| **DELETE** | `/products/:id` | Deletes a product from the database by its ID | `200 OK` |

### Sample Payload (`POST /products`):

```json
{
  "name": "Headset Gamer 7.1",
  "price": 279.90
}
