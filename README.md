# 🏨 The Wild Oasis Dashboard Project 🌿

## 📌 Project Overview

The **Wild Oasis** is a **full-featured hotel management dashboard** designed to optimize hotel operations. Built as part of **Jonas Schmedtmann's React course**, this project provides an intuitive interface for managing **cabins, bookings, guest profiles, and financial insights**. 

With **real-time data updates, user authentication, and an elegant UI**, this dashboard ensures seamless hotel management.

---

## 🚀 Technologies Used

### 🎨 **Frontend**
- ⚛ **React.js** – UI development.
- ⚡ **Vite** – Modern build tool for fast development.
- 💅 **Styled Components** – Component-based styling.
- 🛤 **React Router** – Enables navigation between pages.
- ✅ **React Hook Form** – Simplifies form handling.

### 🔄 **State Management & Data Fetching**
- 🔥 **React Query** – Fetches and manages server-state data.
- 🌍 **Context API** – Manages global state efficiently.

### 🗄 **Backend & Database**
- 🛡 **Supabase** – Provides authentication, real-time database, and cloud storage.

### 📊 **Additional Libraries & Tools**
- 📉 **Recharts** – Data visualization (charts and graphs).
- 🎨 **React Icons** – Beautiful icons for UI.
- 🛠 **Zod** – Schema validation for form inputs.
- 📢 **React Toastify** – Displays toast notifications.
- 🎭 **Framer Motion** – Smooth UI animations.
- 🌗 **Dark Mode Support** – Custom theme toggling.

---

## 🎯 Key Features

### 🔐 **User Authentication**
✔️ Secure login using **Supabase**.  
✔️ Role-based access for hotel staff.  

### 🏨 **Cabin Management**
✔️ Add, update, or delete cabin details.  
✔️ Store **images, pricing**, and descriptions.  

### 📅 **Booking System**
✔️ View, create, edit, and delete bookings.  
✔️ **Check-in & check-out** guests.  
✔️ **Filter & sort** bookings by status.  

### 📊 **Dashboard Analytics**
✔️ Displays real-time hotel statistics:
   - 📆 **Total bookings & revenue**  
   - 📈 **Occupancy rates**  
   - 🔍 **Recent activity logs**  
✔️ Uses **Recharts** for data visualization.  

### 📋 **Guest Profiles**
✔️ Manage **guest information** and booking history.  
✔️ Store contact details and preferences.  

### 🌍 **Global Search & Filters**
✔️ Quickly find **cabins, guests, bookings**.  
✔️ Advanced **sorting & filtering** options.  

### 🎨 **Dark Mode**
✔️ Light & Dark theme toggle.  
✔️ Saves preference in **local storage**.  

---

## ⚙️ Setup Instruction

### 1️⃣ **Clone the Repository**
git clone https://github.com/SaraReda8/The-Wild-Oasis-Dashboard-.git
### 2️⃣ Navigate to the Project Directory
cd The-Wild-Oasis
### 3️⃣ Install Dependencies
npm install 
### 4️⃣ Set Up Environment Variables
Create a .env file and configure the necessary environment variables:
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
### 5️⃣ Run the Development Server
npm run dev
