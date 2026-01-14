#📦 CITK Campus Lost & Found

A centralized, web-based Lost & Found platform designed for
Central Institute of Technology, Kokrajhar (CITK).

🧩 Overview

CITK Campus Lost & Found is a lightweight web application that helps students and staff report, track, and recover lost items on campus.

Instead of scattered WhatsApp messages or notice boards, this platform provides one trusted system with image-based reporting, automatic matching, and admin verification.

🚩 Problem Statement

Lost items on campus are usually reported through informal methods such as:

WhatsApp groups

Physical notice boards

Word of mouth

These approaches are:

Unorganized

Easy to miss

Impossible to track or verify

As a result, many items are never returned to their owners.

💡 Proposed Solution

This project introduces a centralized Lost & Found web platform where:

Users can report lost or found items with images

All reports are stored in one place

Possible matches are automatically identified

Admin can verify and mark items as returned

This improves recovery speed, transparency, and trust.

✨ Features

🧭 Centralized campus-specific platform

📸 Image-based reporting of items

📝 Lost item reporting with description and location

✅ Found item reporting with image and location

📋 Organized listing of all items

🔍 Automatic matching of lost and found items

🛠 Admin panel for verification and status update

🔄 Status lifecycle: Open → Returned

📱 Mobile-friendly and responsive UI

📈 Scalable for multi-campus use

🛠 Tech Stack
Frontend

HTML

CSS

JavaScript

Backend (Google Technologies)

Firebase Firestore – Cloud database

Google Cloud Platform (via Firebase)

Image Handling

Cloud-based image hosting service

🏗 Architecture Overview

Web Browser (User / Admin)

Frontend (HTML, CSS, JavaScript)

Firebase Firestore (Database)

Matching Logic

Admin Panel for verification

This modular architecture ensures scalability and maintainability.

🔄 Process Flow

User reports a lost or found item

Item details and image are stored in the database

Matching logic checks for possible matches

Matches are displayed to users

Admin verifies and marks item as returned

Status updates are reflected system-wide

🚀 Future Enhancements

🔐 User authentication and role-based access

🤖 AI-based matching for higher accuracy

🔔 Email / in-app notifications

🧾 Claim verification workflow

📊 Analytics dashboard

🌐 Deployment on Firebase Hosting
