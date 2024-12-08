# 🏉 Athlete Connect  

![Athlete Connect Banner](athlete.png)  

**Athlete Connect** is a comprehensive web application designed for organizing and managing Rugby festivals. From hosting events and managing teams to scheduling matches and enabling user voting, Athlete Connect simplifies the administrative and engagement processes for sports festivals.  

---

## 🌟 Features  

- **Event Hosting:** Create and manage Rugby events effortlessly.  
- **Team Management:** Add, edit, and organize teams for tournaments.  
- **Match Scheduling:** Schedule matches with an intuitive interface.  
- **User Voting:** Engage the audience through interactive voting systems.  
- **Responsive Design:** Seamlessly accessible on all devices.  

---

## 🛠️ Tech Stack  

| Technology       | Purpose                    |  
|-------------------|----------------------------|  
| **Django**        | Backend Framework          |  
| **Django REST Framework** | API Development       |  
| **HTML, CSS, JavaScript** | Frontend Development   |  
| **PostgreSQL**    | Database Management        |  
| **Chart.js**      | Data Visualization         |  
| **Stripe**        | Secure Payments            |  

---

## 🚀 Installation  

### **Prerequisites**  
- Python 3.8+  
- Django 4.0+  
- PostgreSQL  

### **Steps**  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-username/athlete-connect.git  
   cd athlete-connect  
   ```  

2. **Set Up a Virtual Environment**  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`  
   ```  

3. **Install Dependencies**  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Configure Environment Variables**  
   Create a `.env` file in the root directory and add the following:  
   ```plaintext  
   SECRET_KEY=your_secret_key  
   DEBUG=True  
   DATABASE_URL=postgres://username:password@localhost:5432/athlete_connect  
   ```  

5. **Apply Migrations**  
   ```bash  
   python manage.py migrate  
   ```  

6. **Run the Server**  
   ```bash  
   python manage.py runserver  
   ```  

7. **Access the Application**  
   Open your browser and navigate to [http://localhost:8000](http://localhost:8000).  

---

## 🧪 Testing  

Run tests to ensure everything is functioning as expected:  
```bash  
python manage.py test  
```  

---

## 🎨 UI/UX Design  

The platform follows modern design principles to ensure:  
- Intuitive navigation  
- Mobile-first responsive layouts  
- Interactive user interfaces  

---

## 📖 Documentation  

Comprehensive API documentation is available via Swagger at:  
`http://localhost:8000/api/docs`  

---

## 🌍 Live Demo  

Explore the live application at [athleteconnect.co.za](https://athleteconnect.co.za).  

---

## 📜 License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  
