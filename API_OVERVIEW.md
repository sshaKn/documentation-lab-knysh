# API приклади

GET /tutors
Відповідь:
Tutor tutor1 = {1, "Іван", "Математика", 250};

---

POST /booking
Запит:
Booking b = {tutor_id:1, date:"10.03", time:"15:00"};

Відповідь:
Status = SUCCESS;

---

GET /profile
Відповідь:
User u = {5, "Олександр", "a@email.com"};

---

Коди:
200 — OK
404 — Not found
500 — Server error
