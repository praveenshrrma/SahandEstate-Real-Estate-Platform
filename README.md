## 📚 Introduction
Stitch & Sole Co. is a full-stack e-commerce web application using React, Node.js, and Stripe for payment processing, offering features such as secure user authentication, product management, cart functionality, and dynamic checkout. The platform includes an admin dashboard for product analytics and a seamless shopping experience with responsive design powered by Tailwind CSS. 

-   🗄️ MongoDB & Redis Integration
-   💳 Stripe Payment Setup
-   🔐 Robust Authentication System
-   🔑 JWT with Refresh/Access Tokens
-   📝 User Signup & Login
-   🛒 E-Commerce Core
-   📦 Product & Category Management
-   🛍️ Shopping Cart Functionality
-   💰 Checkout with Stripe
-   🏷️ Coupon Code System
-   👑 Admin Dashboard
-   📊 Sales Analytics
-   🎨 Design with Tailwind
-   🛒 Cart & Checkout Process
-   🔒 Security
-   🛡️ Data Protection
-   🚀Caching with Redis
-   ⌛ And a lot more...

---

## ⚙️ Tech Used

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)  
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)  
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=react&logoColor=white)  
![ShadCN](https://img.shields.io/badge/ShadCN-00B9F1?style=for-the-badge&logo=shadcn&logoColor=white)  
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)  
![Zod](https://img.shields.io/badge/Zod-2F3B49?style=for-the-badge&logo=zod&logoColor=white)  
![Uploadthing](https://img.shields.io/badge/Uploadthing-FF5858?style=for-the-badge&logo=uploadthing&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)  
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)  
![Auth0](https://img.shields.io/badge/Auth0-000000?style=for-the-badge&logo=auth0&logoColor=white)  
![Stripe](https://img.shields.io/badge/Stripe-6772E5?style=for-the-badge&logo=stripe&logoColor=white)  
![Render](https://img.shields.io/badge/Render-22A7F0?style=for-the-badge&logo=render&logoColor=white)  

---

## 🔋 Features

1. **Seamless User Authentication & Authorization**  
   Integrated with **Auth0**, the platform ensures secure user sign-up, login, and role-based access control, providing a highly secure and scalable authentication system.

2. **Real-time Product Management Dashboard**  
   A fully-featured admin dashboard that allows admins to manage products (add, update, delete), view analytics, and feature products, enhancing the platform's flexibility and usability.

3. **Stripe Payment Integration**  
   Secure and efficient payment processing using **Stripe**, enabling seamless transactions with features like coupon codes and gift card support for a superior customer experience.

4. **Responsive UI Built with Tailwind CSS**  
   The front-end is designed using **Tailwind CSS**, ensuring a highly responsive and visually appealing user interface that works seamlessly across all devices.

5. **Product Filtering and Pagination**  
   Implementing advanced **filtering**, **sorting**, and **pagination** for products, allowing users to easily browse through categories, find featured products, and make informed purchases.

6. **Real-time Order Status Tracking**  
   A dynamic order tracking system that updates users on the status of their orders in real-time, providing transparency and improving customer satisfaction.

7. **Scalable Cloud Deployment on Render**  
   The entire application is deployed on **Render**, a powerful cloud platform, ensuring fast, reliable, and scalable hosting for both front-end and back-end components.

8. **Gift Card and Coupon System**  
   Integrated **gift card** and **coupon** features, offering users discounts and promotions, adding an extra layer of engagement and value to the customer experience.

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
