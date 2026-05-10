**Prescripto — Doctor Appointment Booking App**

A full-stack web application that simplifies the process of booking doctor appointments. Built with the **MERN stack**, Prescripto provides dedicated dashboards for **Patients**, **Doctors**, and **Admins**, with secure authentication, profile management, and integrated online payments.

---

**Live Demo**

| Panel   | URL |
|---------|-----|
| Frontend (Patient) | [Link](https://prescripto-frontend-iota-ten.vercel.app/) |

---

**Features**

**1.Patient**
- Register, log in, and browse available doctors by specialization
- Book appointments with a preferred date and time
- Pay online via **Stripe** or **Razorpay**, or choose cash payment
- View, cancel, or manage upcoming and past appointments
- Edit profile — name, email, address, gender, date of birth, and profile picture

**2.Doctor**
- Secure doctor login with a personal dashboard
- View and manage scheduled appointments
- Track earnings and appointment history
- Update availability and profile information

**3.Admin**
- Add, edit, or remove doctors from the platform
- Monitor all appointments across all doctors
- Manage the overall platform and user data from a centralized dashboard

---

**4.Tech Stack**

| Layer      | Technology |
|------------|------------|
| Frontend   | React.js, Tailwind CSS |
| Backend    | Node.js, Express.js |
| Database   | MongoDB (Mongoose) |
| Auth       | JWT (JSON Web Tokens) |
| Payments   | Stripe, Razorpay |
| File Upload| Cloudinary |
| Deployment | Vercel |

---

## 📁 Project Structure

Prescripto/
├── frontend/      
├── admin/          
├── backend/         
└── .gitignore





**Getting Started**
**1.Prerequisites**
- Node.js ≥ 18
- MongoDB (local or Atlas)
- Cloudinary account
- Stripe and/or Razorpay API keys

**2.Clone the repository**

```bash
git clone https://github.com/Suhas-S2004/Prescripto.git
cd Prescripto
```

**3.Set up the Backend**

```bash
cd backend
npm install
```

**Create a `.env` file in the `backend/` folder:**

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret

ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
```

Start the backend server:

```bash
cd ../backend
npm run server
```

**4.Set up the Frontend**

```bash
cd ../frontend
npm install
npm run dev
```

**5.Set up the Admin Panel**

```bash
cd ../admin
npm install 
npm run dev
```

---

**Role-Based Access**
| Role    | Access                              |
|---------|-------------------------------------|
| Patient | Book appointments, manage profile   |
| Doctor  | View schedule, manage appointments  |
| Admin   | Full platform control               |

---
