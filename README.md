# 🌌 Solar System Explorer

An interactive, multi-page website showcasing the Solar System — hosted on an **Amazon EC2** instance using **Apache web server**.

![Solar System](https://upload.wikimedia.org/wikipedia/commons/4/4c/Solar_sys8.jpg)

---

## 🚀 Overview

This project features an educational and visually rich interface to explore our solar system. Each celestial body (Sun and planets) has its own page with real images and facts.

- 🌍 Built with: **HTML**, **CSS**, **JavaScript**
- ☁️ Hosted on: **Amazon EC2 (Free Tier)** with **Apache HTTP Server**
- 🔒 Accessed via SSH using PEM key
- 🛰️ Backup created with **AMI** for safe image of server state

---

## 🌠 Features

- 💫 Home page with clickable planets
- ☀️ Individual pages for:
  - Sun
  - Mercury
  - Venus
  - Earth
  - Mars
  - Jupiter
  - Saturn
  - Uranus
  - Neptune
- 📸 Real space images from NASA/Wikipedia/CDN
- 🧾 Planet descriptions with scientific info
- 🌐 Public access via EC2 public IP or domain

---

## 🛠️ Technologies Used

| Category    | Tools Used                    |
|------------|-------------------------------|
| Frontend   | HTML5, CSS3, JavaScript       |
| Hosting    | Amazon EC2 (Ubuntu), Apache2  |
| Access     | SSH (PEM key)                 |
| Image Mgmt | `curl`, `wget`                |
| Backup     | AMI (Amazon Machine Image)    |

---

## 📷 Example Screenshots

![Example](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Solar_sys8.jpg/1024px-Solar_sys8.jpg)

---

## 🧠 What I Learned

- Hosting a static website on EC2 using Apache
- Configuring EC2 security groups (port 80 for HTTP)
- Using Linux commands (`scp`, `chmod`, `curl`, `file`)
- Troubleshooting image MIME issues
- Creating and restoring from AMI
- Domain/IP-based deployment

---

## 🔗 Live Demo (if available)

> http://YOUR_EC2_PUBLIC_IP  
> *(Or replace with domain if you have one)*

---

## 🧾 License

This project is for learning purposes and open to public use.

---

