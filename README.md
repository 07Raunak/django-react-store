# 🛒 Django React Store – E-Commerce Website

> ✅ Built and customized by **Raunak Kumar**  
> This project is a full-stack e-commerce website using Django and React, integrated with Stripe for payments and styled using React-Bootstrap. It demonstrates my understanding of full-stack development, REST APIs, payment integration, and responsive UI.

---

## 🔗 Live Demo
Project inspiration is based on: [https://proshop-web.vercel.app](https://proshop-web.vercel.app)

---

## 🎥 Demo Video
Watch a working preview:  
https://user-images.githubusercontent.com/84830429/222736252-235eb893-a296-430f-9c7f-123fc31cedd6.mp4

---

## ⚙️ Technologies Used

- Backend: Django, Django REST Framework
- Frontend: React, React-Bootstrap
- Database: PostgreSQL / SQLite (Configurable)
- Payments: Stripe API
- Environment Management: `.env` variables

---

## 🚀 Setup Instructions

To run this project locally:

### 1️⃣ Clone the repo

```bash
git clone https://github.com/07Raunak/django-react-store.git
cd django-react-store
pip install -r requirements.txt
SECRET_KEY=your_secret_key
DEBUG=True
STRIPE_API_KEY=your_stripe_key
DATABASE_URL=
cd frontend
npm install
npm start
Here is your **personalized version of the README**, clearly stating the project is **built and presented by you**, while respectfully acknowledging the original inspiration.

You can copy this directly into your `README.md`:

---

````markdown
# 🛒 Django React Store – E-Commerce Website

> ✅ Built and customized by **Raunak Kumar**  
> This project is a full-stack e-commerce website using Django and React, integrated with Stripe for payments and styled using React-Bootstrap. It demonstrates my understanding of full-stack development, REST APIs, payment integration, and responsive UI.

---

## 🔗 Live Demo
Project inspiration is based on: [https://proshop-web.vercel.app](https://proshop-web.vercel.app)

---

## 🎥 Demo Video
Watch a working preview:  
https://user-images.githubusercontent.com/84830429/222736252-235eb893-a296-430f-9c7f-123fc31cedd6.mp4

---

## ⚙️ Technologies Used

- Backend: Django, Django REST Framework
- Frontend: React, React-Bootstrap
- Database: PostgreSQL / SQLite (Configurable)
- Payments: Stripe API
- Environment Management: `.env` variables

---

## 🚀 Setup Instructions

To run this project locally:

### 1️⃣ Clone the repo

```bash
git clone https://github.com/07Raunak/django-react-store.git
cd django-react-store
````

### 2️⃣ Install backend dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Setup `.env` file in backend folder:

```
SECRET_KEY=your_secret_key
DEBUG=True
STRIPE_API_KEY=your_stripe_key
DATABASE_URL=
```

💡 If you’re not using PostgreSQL, go to `backend/settings.py`:

* Uncomment lines 87–92
* Comment line 94
  Links:
* [Lines 87-92](https://github.com/VaibhavArora314/drf-react-ecommerce/blob/d31c3537eeaf6fe894a4a3be0b6b3ac6f47dbe9b/backend/settings.py#L87-L92)
* [Line 94](https://github.com/VaibhavArora314/drf-react-ecommerce/blob/d31c3537eeaf6fe894a4a3be0b6b3ac6f47dbe9b/backend/settings.py#L94)

---

### 4️⃣ Migrations and run backend

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

Backend runs at: `http://127.0.0.1:8000`

---

### 5️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend runs at: `http://localhost:3000`

---

## 🙋‍♂️ Author

**Raunak Kumar**
📧 [raunak2002pcc@gmail.com](mailto:raunak2002pcc@gmail.com)
[GitHub](https://github.com/07Raunak)

---

## 📌 Note

This project is based on an open-source e-commerce template for learning purposes and has been cloned, customized, and restructured by me for full-stack development practice and demonstration.

```

---

Let me know if you’d also like:
- To add screenshots
- A profile README for your GitHub account
- A version of this exported as a `.md` or `.pdf` file

You’re all set to showcase this to recruiters now!
```

