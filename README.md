# AuroDigital_DigiLocker

##Key feature:

##Digilocker web page
![Digilocker welcome](https://github.com/user-attachments/assets/01504079-5a91-4ace-a5ad-9690b6bee7b1)

##Password verification
![Password verification](https://github.com/user-attachments/assets/7411287f-dcd3-4b7d-a124-710bcb2beb2f)

##Check for existing username
![Existing username](https://github.com/user-attachments/assets/7928da5d-63f1-46b7-8686-d82dbcead866)

##Integrated javascript for password verification
![Integrated javascript](https://github.com/user-attachments/assets/244b894e-259a-4743-8623-c2d8a6f57256)

##Signup successful
![signup successful](https://github.com/user-attachments/assets/16916152-a53f-4643-80e2-6c08b846a6dc)

##Login successful
![Login successful](https://github.com/user-attachments/assets/3bed8442-c3c1-4feb-a817-118a0d907fd9)

##Upload Document functionality
![upload resume](https://github.com/user-attachments/assets/8e76d4d9-4cb1-43fb-8afc-b39890a3fc1b)



DigiLocker  is a web application that allows users to **securely upload, view, share, and verify documents**. It includes **user authentication** and provides a user-friendly interface for managing personal documents.It also provides sharing of documents using  qr code and links.

---

## **Features**  

### **User Authentication**  
- Sign Up, Login, and Logout functionality for secure access.  

### **Document Management**  
- Upload documents securely.  
- View and verify uploaded documents.  
- Generate **QR codes** for easy document sharing.  
- Open documents in a new tab for **viewing without downloading**.  

### **Responsive Design**  
- Optimized for both **desktop and mobile devices**.  

---

## **Technologies Used**  
- **Database used:** SQLite (default for Django projects)
- **Frontend Technologies:** HTML, CSS, Bootstrap, JavaScript    
- **Backend Technologies:** Django, Django REST Framework,Django password validation,qrcode.js

---

## **Installation and Setup**  

### **1. Clone the Repository**  
```sh
git clone https://github.com/ak4721269/AuroDigital_DigiLocker.git
cd DigiLocker_Auro_digital
```

### **2. Set Up a Virtual Environment**  
```sh
python3 -m venv env
source env/bin/activate  # For Linux/Mac
env\Scripts\activate     # For Windows
```

### **3. Install Dependencies**  
```sh
pip install -r requirements.txt
```

### **4. Apply Migrations**  
```sh
python manage.py makemigrations
python manage.py migrate
```

### **5. Run the Development Server**  
```sh
python manage.py runserver
```

- Open your browser and go to: **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**  

---

## **Usage**  

### **1. Sign Up & Login**  
- Navigate to **`/signup/`** to create an account.  
- Use **`/login/`** to access your account.  

### **2. Upload Documents**  
- Go to the **Upload Document** page.  
- Enter a **title** and select a **file** to upload.  

### **3. View & Manage Documents**  
- Access the **View Documents** page to see a list of uploaded documents.  
- Click **View** to open a document in a new tab.  
- Click **Verify** to mark a document as **verified**.  
- Click **Share** to generate a **QR code** for sharing the document link.  

### **4. Logout**  
- Use the **Logout** button to securely end the session.  


