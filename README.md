
#  BTRE Real Estate — Powered by Django
A fully functional real estate listing website built with Django. This project allows users to browse property listings, contact agents, and manage listings through an admin dashboard.



## 🚀 What It Does

BTRE is a practical real estate web app that allows:

🔍 Browsing property listings with images, price, and details.

🧭 Filtering listings by city, state, bedrooms, price, etc.

📄 Viewing detailed property pages with descriptions and realtor info.

📩 Contacting realtors directly from the listing page.

🧑‍💼 Agent dashboard to manage their own listings.

🔐 Secure login system for realtors.

💡 Admin panel for full control over listings, agents, and leads.

## ⚙️ Tech Stack

| Tech           | Description                                      |
| -------------- | ------------------------------------------------ |
| 🐍 Python      | Backend programming language.                    |
| 🌐 Django      | High-level web framework for backend and ORM.    |
| 🗂️ SQLite     | Lightweight relational database for development. |
| 🎨 HTML5       | Structure of the web pages.                      |
| 💅 CSS3        | Styling for layout and appearance.               |
| 🎯 Bootstrap   | Responsive and modern UI framework.              |
| 💬 JavaScript  | Interactivity and client-side logic.             |
| 🔒 Django Auth | Handles user login, logout, and authentication.  |


## 🗂️ Project Structure

```text
BTRE/
├── btre/                 # Main Django project folder
│   ├── settings.py       # Project settings
│   ├── urls.py           # Root URLs
│   └── wsgi.py
├── contacts/             # App for contact form and messages
│   ├── models.py
│   ├── views.py
│   └── admin.py
├── listings/             # App for property listings
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── realtors/             # App for realtor profiles
│   ├── models.py
│   └── views.py
├── media/                # Folder for media uploads
├── templates/            # Shared HTML templates
├── manage.py             # Django CLI
└── requirements.txt      # Dependencies
```



## ✨ Key Features
- 📸 Image uploads for property listings.

- 📬 Realtor contact form with lead saving.

- 📂 Admin panel to manage listings and users.

- 📈 Dynamic search filters by multiple criteria.

- 💼 Realtor login with dashboard access.

- 🔄 Pagination of listings for better UX.


## 🧩 How It Works

🛠 Django Admin: Used to manage listings, realtors, and inquiries.

🏡 Listings: Pulled from the database and rendered dynamically.

🔍 Search: Uses GET parameters to filter results by fields.

📤 Contact Form: Submits leads to the database and notifies the realtor.

🔐 Authentication: Built-in Django auth handles sessions and permissions.


## 💾 Installation & Setup bash Copy Edit

`git clone https://github.com/yourusername/BTRE-RealEstate.git`

`cd BTRE-RealEstate`

`pip install -r requirements.txt`

`python manage.py migrate`

`python manage.py runserver`

## 🧠 Learning Outcomes
- Learned to structure a full Django project.

- Integrated templates, static files, and media upload support.

- Practiced Django’s ORM, model relationships, and admin customization.

- Understood how to handle user authentication and dashboard systems.

- Built reusable components using template inheritance and includes.


## 🙌 Authors
Developed with ❤️ by **Mohamed Rasith** and team
Feel free to connect on LinkedIn or check out our GitHub profiles.
## 📜 License
For educational purposes only.
