# Yoga-Website
# Yoga Website

A simple Yoga website showcasing classes, instructors, schedule, and other related information. This project is deployed using **Nginx** and can be automated with a **Jenkins pipeline**.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Manual Deployment](#manual-deployment)
  - [Deployment via Jenkins](#deployment-via-jenkins)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [License](#license)

---

## Project Overview

This Yoga website includes:  
- Home page with introduction to yoga  
- Class schedule  
- Instructor profiles  
- Contact information  
- Responsive design with HTML, CSS, and JavaScript  

---

## Prerequisites

Before deploying, make sure you have:  
- Ubuntu server (18.04+ recommended)  
- Nginx installed (`sudo apt install nginx -y`)  
- Git installed (`sudo apt install git -y`)  
- Jenkins installed (optional for automated CI/CD)  

---

## Installation

### Manual Deployment

1. **Clone the repository:**
```bash
git clone https://github.com/Sushantp875/yoga-website.git
cd yoga-website

2. **Deploy files to Nginx:**

sudo rm -rf /var/www/html/*
sudo cp -r * /var/www/html/

3. **Restart Nginx to apply changes:**

sudo systemctl restart nginx
