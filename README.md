# 🏋️‍♂️ Fit-Track – Fitness Progress Tracker

**Fit-Track** is a fitness-focused web application designed to help users calculate and monitor their **BMI (Body Mass Index)** while allowing them to get in touch via a contact form. This project primarily emphasizes the **frontend user experience** using **React.js**, with a minimal **Node.js backend** for handling contact messages via email.

---

## 🚀 Project Overview

Fit-Track offers:
- A clean, responsive frontend for fitness users
- BMI calculator based on user input (height & weight)
- Contact form where users can reach out with messages
- Node.js + Nodemailer backend to send user messages directly to the owner's email

---

## ✨ Features

- 🧮 **BMI Calculator** – Calculates user's BMI using height and weight
- 📝 **Contact Form** – Collects name, email, and message from the user
- 📧 **Email Integration** – Messages sent via the contact form are emailed to the owner using **Nodemailer**
- 🎨 **Modern UI** – Built with React and styled for a seamless user experience

---

## 🛠️ Tech Stack

- **Frontend**: React.js, HTML5, CSS3
- **Backend**: Node.js, Express.js, Nodemailer

---

## 🖼️ Screenshots

![screencapture-localhost-5173-2025-06-19-21_34_13](https://github.com/user-attachments/assets/01a296d3-04eb-4a4e-8048-0e41776ef2e5)

---

## 📂 Project Structure

- /client --> React frontend (BMI calculator + contact form)
- /server --> Node.js backend (handles contact form submission)
- package.json --> Project metadata and dependencies

---

## ⚙️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/dharmitaliya/Fit-Track.git
2. **Install dependencies**
   <br>
   - Backend:
      ```bash
      cd Backend
      npm install
   - Frontend:
     ```bash
     cd ../Frontend
     npm install
 
3. **Set up environment variables** <br>
Inside the Backend folder, create a .env file and add:
   ```bash
   PORT=4000
   
   FRONTEND_URL=http://localhost:5173
  
   SMTP_HOST=smtp.gmail.com

   SMTP_PORT=465

   SMTP_SERVICE=gmail

   SMTP_MAIL=(your gmail address where you want all mails from users)

   SMTP_PASSWORD=(you can get it from google->manage account->app passwords->generate new and paste here)

4. **Start the servers**<br>
   - Backend Server:
      ```bash
      npm run dev
   - Frontend :
     ```bash
     npm run dev

---

## 📧 Contact <br>
For any queries or suggestions, feel free to connect. <br>
Email: [dharm.italiya5151@gmail.com](dharm.italiya5151@gmail.com)  LinkedIn: [Dharm Italiya](https://www.linkedin.com/in/dharm-italiya/)

---

## 🙌 Thank you for visiting Fit-track!
