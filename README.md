# 🏨 Hotel Room Booking API

This project is a simple Hotel Room Booking system built using FastAPI.
The main idea of this project is to manage hotel rooms, bookings, and basic hotel operations like check-in and check-out through API endpoints.

It was developed as part of a learning project to understand how real-world backend systems work using FastAPI.

---

## 🚀 Features

* View all rooms with availability status
* Get details of a specific room
* Add, update, and delete rooms
* Create bookings with validation
* Apply meal plans and calculate total cost
* Early checkout with discount
* Check-in and check-out system
* Search, filter, and sort rooms
* Pagination support
* Combined browsing (search + sort + pagination)

---

## 🛠️ Technologies Used

* Python
* FastAPI
* Uvicorn
* Pydantic

---

## 📂 Project Structure

* `main.py` → contains all API logic
* No database is used (data is stored in memory for simplicity)

---

## ▶️ How to Run the Project

1. Create a virtual environment:

   ```
   python -m venv venv
   ```

2. Activate it:

   * Windows:

     ```
     venv\Scripts\activate
     ```
   * Mac/Linux:

     ```
     source venv/bin/activate
     ```

3. Install dependencies:

   ```
   pip install fastapi uvicorn
   ```

4. Run the server:

   ```
   uvicorn main:app --reload
   ```

5. Open Swagger UI:

   ```
   http://127.0.0.1:8000/docs
   ```

---

## 📌 Important Concepts Used

* Path parameters
* Query parameters
* Request body validation using Pydantic
* Helper functions for clean code
* CRUD operations
* Route ordering in FastAPI
* Filtering, sorting, and pagination

---

## ⚠️ Notes

* This project does not use a database, so all data will reset when the server restarts.
* Route order is very important in FastAPI. Fixed routes should always be written above dynamic routes.

---

## 💡 What I Learned

While building this project, I understood how APIs are structured and how different features like filtering, sorting, and pagination are implemented in real applications.
I also learned how to handle validation and avoid common mistakes like route conflicts.

---

## 🙌 Conclusion

This project helped me get a clear understanding of backend development using FastAPI.
It can be further improved by adding a database, authentication, and a frontend interface.

---

Thank you!
