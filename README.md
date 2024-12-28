## 📚 Introduction

SahandEstate is a full-stack real estate platform designed to facilitate seamless property listings, user management, and interactive features for both buyers and sellers. Built with the latest web technologies, this project offers a smooth and intuitive user experience for registering, signing in, updating profiles, listing properties, and browsing available real estate offers. 
The platform leverages a modern tech stack including React, Node.js, MongoDB, and Firebase for authentication and file storage. With integrated payment processing via Stripe, users can securely purchase and manage their listings. Additionally, the platform features an admin dashboard for managing user activities and property listings, making it a comprehensive solution for real estate transactions.
---

## ⚙️ Tech Used

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)  
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)  
![Stripe](https://img.shields.io/badge/Stripe-6772E5?style=for-the-badge&logo=stripe&logoColor=white)  
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

---

## 🔋 Features

User Registration & Profile Management
Seamless user authentication and account management system powered by Firebase, allowing users to create, update, and manage their personal profiles.

Property Listings Management
Users can effortlessly browse, add, edit, and delete property listings. Property details include high-quality images, price, location, description, and amenities.

Integrated Search & Filters
Advanced search functionality with filters based on property type, price range, location, and more, providing users with a tailored property discovery experience.

Real-Time Data Updates
Live property updates, including price changes, availability, and listing status. Users can view real-time changes to listings and transactions.

Payment Processing with Stripe
Secure and efficient payment gateway integration with Stripe, enabling users to easily make payments for property purchases or services offered on the platform.

Admin Dashboard
A robust admin panel for managing user accounts, property listings, and monitoring transactions. Admins can approve, reject, or edit listings and view user activity in real-time.

Responsive Design
Fully responsive, mobile-first design using Tailwind CSS, ensuring an optimal viewing experience across a wide range of devices, from smartphones to desktops.

Interactive Map View
Visual property location display with an integrated map for users to easily explore properties in specific areas or neighborhoods.

User Reviews & Ratings
Allows users to leave reviews and ratings for properties, enhancing trust and providing feedback for other potential buyers or renters.

File Uploads with Firebase
Simple and secure file upload system for users to add property images, floor plans, and other documents related to their listings using Firebase Storage.

Notifications & Alerts
Real-time email and in-app notifications to inform users about listing status updates, new messages, or changes in the property they are interested in.

Advanced Analytics
Track user behavior and property performance with detailed analytics on views, interactions, and purchases, helping sellers optimize their listings.

Secure User Authentication
Utilizes Firebase Authentication for robust security, ensuring a secure sign-in and user verification process.

Scalable Infrastructure
Built with scalability in mind, the platform is designed to handle growing user bases and increasing traffic, powered by Node.js and MongoDB.

---

## ⚙️ Planned Optimizations

- **Improve Performance**: I would optimize API responses by implementing pagination and lazy loading for large product lists to reduce page load times.

- **Enhance User Experience**: I would implement advanced search functionality, such as filters by size, color, and price range, to create a more intuitive shopping experience.

- **SEO Optimization**: I would focus on improving the app's SEO by adding meta tags, structured data, and enhancing page crawlability to attract more organic traffic.

- **Mobile Responsiveness**: I would refine the mobile view, adjusting UI components to ensure better usability across different screen sizes.

- **User Reviews and Ratings**: I would add a feature that allows customers to leave reviews and rate products, helping future buyers make more informed decisions.

- **Admin Dashboard Enhancements**: I would implement data visualization tools on the admin dashboard to help track sales, traffic, and customer trends more effectively.

- **Security Enhancements**: I would add two-factor authentication (2FA) during login to improve user security.

- **Automated Testing**: I would implement unit and integration tests for key features to ensure reliability and make the app easier to maintain.

## 📚 Lessons Learned


I improved my ability to create responsive layouts, ensuring the application adapts well to different screen sizes and devices, providing users with a seamless experience on mobile and desktop.

I refined my ability to implement and manage e-commerce functionalities such as product management, cart operations, and Stripe payment integration, ensuring a seamless shopping experience for users.

I enhanced my ability to integrate third-party services like Cloudinary for image uploads, optimizing the platform's functionality and enabling users to upload images effortlessly.




### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
