# ai-slot-scheduler
# Q_Slot — Virtual Queue Management System for Public Distribution

**Q_Slot** is a web-based automatic virtual queue token generation system that uses **Deep Q-Learning** and **SMS Notifications** to modernize ration distribution under the Public Distribution System (PDS). It replaces physical queues with smart slot allocation and notifications.

---

## 📌 Modules

**1️⃣ Disperse Slot Web Application**
- Flask-based web app to manage slot creation and token management.

**2️⃣ Time Slot Generator**
- Uses Deep Q-Learning to generate optimal slots and distribute tokens.

**3️⃣ Web Admin / Government Regulator**
- Admin dashboard for managing shops, ration cards, area details, and stock.

**4️⃣ Ration Shop Admin**
- Handles shop-level operations: stock updates, token scheduling, billing.

**5️⃣ Consumer**
- Books slots online, tracks queue status, requests rescheduling, and receives SMS updates.

**6️⃣ Automatic Notification System**
- Sends OTPs and SMS notifications for slot allocation, rescheduling, and collection reminders.

---

## ⚙️ Tech Stack

| Layer      | Technologies                          |
|------------|---------------------------------------|
| Backend    | Python 3.7+, Flask                    |
| Frontend   | HTML, CSS, Bootstrap                  |
| Database   | MySQL 5                               |
| Server     | WampServer                            |
| Packages   | TensorFlow, Pandas, scikit-learn      |

---

## 🚀 How to Run

1. **Clone the repository**
   
   git clone https://github.com/yourusername/q-slot-virtual-queue.git

2. **Install dependencies**

   pip install -r requirements.txt

3. **Configure the Database**

   Create a MySQL database
   Import tables and sample data if available.
   Update DB credentials in your Python code.

4. **Run the App**
      python main.py
   Open your browser:
      http://localhost:5000

   
## Future Enhancements
1.Integrate online payments for ration orders.

2.Develop a dedicated mobile app for consumers.

3.Add real-time analytics dashboards for administrators.

4.Multi-language support for wider reach.




