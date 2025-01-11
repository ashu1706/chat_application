![](https://github.com/ashu1706/Roomly/blob/main/Screenshot%202024-12-24%20150637.png)

# Roomly

Roomly is a Django-based web application that allows users to create and join chat rooms for real-time communication. The platform is designed to be intuitive, user-friendly, and highly scalable, making it ideal for personal and community discussions.

---

## 🚀 Features

- **Create Chat Rooms**: Users can create chat rooms with unique names.
- **Join Chat Rooms**: Easily join existing chat rooms by entering the room name.
- **Real-Time Messaging**: Engage in live conversations with participants in the room.
- **User Authentication**: Secure sign-up and login functionality to manage users.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Scalable Architecture**: Built with Django, making it scalable for future enhancements.

---

## 🛠️ Tech Stack

- **Backend**: [Django](https://www.djangoproject.com/) (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite
- **WebSocket**: Django Channels (for real-time messaging)

---

## 🎯 Prerequisites

Ensure you have the following installed:

- Python (3.8 or later)
- pip (Python package manager)
- Git

---

## 📦 Installation

Follow these steps to set up Roomly on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/ashu1706/Roomly.git
   cd Roomly
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Apply migrations:
   ```bash
   python manage.py migrate
5. Run the development server:
   ```bash
   python manage.py runserver
6. Open your browser and navigate to:
   ```bash
   http://127.0.0.1:8000/
