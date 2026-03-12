"# HMS" 
# 🏨 HMS – Hotel Management System

A powerful and modular API-based Hotel Management System built using **Django** and **Django REST Framework**, designed for integration with modern frontend frameworks like React. HMS manages hotel operations including room bookings, restaurant orders, laundry services, CRM, accounting, marketing, and more.

---

## 🚀 Features

- 🔐 **JWT Authentication** with simple login/logout
- 🎚️ **Role-Based Permissions** (assign model-level access via UI)
- 🏨 **Hotel & Room Management** (categories, bookings, check-in/out)
- 🍽️ **Restaurant & Menu Ordering System**
- 🧺 **Laundry Services** with pickup/delivery tracking
- 👥 **CRM Module** – customer data and interaction tracking
- 📝 **CMS** – manage website content and banners
- 📬 **Communication** – feedback, messages, and notifications
- 💳 **Billing & Accounting** – invoices, transactions, reports
- 📣 **Marketing Module** – campaigns, promotions
- ⭐ **Review System** – hotel/restaurant/service feedback
- ⚙️ **Fully API-Based** for smooth frontend/backend separation

---

## 🧱 Project Structure

HMS/
├── hotel/ # Hotel, room, booking, roomservicerequest                                                               
├── restaurant/ # Menu, orders                                                              
├── laundry/ # Laundry orders                                                               
├── crm/ # Customer data                                                                
├── cms/ # Banners, testimonials, meta tags                                                             
├── billing/ # Invoice and payments                                                             
├── accounting/ # Financial tracking                                                                
├── marketing/ # Campaigns and promotions                                                               
├── communication/ # Messages, notifications, feedback                                                              
├── reviews/ # Customer reviews                                                             
├── permissions/ # Roles and model-level permission API                                                             
├── accounts/ # Custom user model and auth                                                              
├── manage.py                                                               
└── requirements.txt                                                                


---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/akshmat243/HMS.git
cd HMS


python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py shell
from MBP.utils import populate_app_models
populate_app_models()   # populate the database with some data
python manage.py runserver



| Module        | Description                          |
| ------------- | ------------------------------------ |
| Hotel         | Hotels, rooms, categories, bookings  |
| Restaurant    | Menus, orders                        |
| Laundry       | Laundry requests, statuses           |
| CRM           | Customer info, history               |
| CMS           | Banners, meta tags, testimonials     |
| Billing       | Invoices and payments                |
| Accounting    | Transactions, ledgers                |
| Marketing     | Campaigns, promotions                |
| Communication | Feedback, notifications, messages    |
| Reviews       | Hotel, restaurant, service reviews   |
| Permissions   | Roles and model-level permission API |


📄 License
This project is licensed under the MIT License

👨‍💻 Author
Developed by Badal Kumawat
