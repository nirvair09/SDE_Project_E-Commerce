##Shopee-ECommerce-MERN 

This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) e-commerce website with a range of features, providing a seamless shopping experience. The project implements a beautiful and intuitive user interface with various functionalities for both customers and shoppers.

Features Customer Features:

User authentication and authorization View products and search functionality Wishlist to save preferred items Shopping cart with the ability to add, update, and remove items Multiple shipping addresses Secure Stripe payment integration Order history and status tracking User profile management and updates Real-time chat using Socket.IO for communication with shoppers Email verification using SMTP (Gmail) Shopper Features:

Add new products to the inventory Update product details, including availability and pricing View sales and payments history Real-time chat with customers using Socket.IO Technology Stack Frontend:

React.js React Router for navigation Beautiful UI/UX design Backend:

Node.js with Express.js MongoDB for database management Stripe for secure payment processing Socket.IO for real-time communication Getting Started Clone the repository:

Sample .env
env Copy code PORT=8000 DB_URL=mongodb+srv://your_username:your_password@your_cluster_url/eshop JWT_SECRET_KEY=your_jwt_secret_key JWT_EXPIRES=7d ACTIVATION_SECRET=your_activation_secret SMTP_SERVICE=gmail SMTP_HOST=smtp.gmail.com SMTP_PORT=587 SMTP_PASSWORD=your_smtp_password SMTP_MAIL=your_email@gmail.com STRIPE_API_KEY=your_stripe_api_key STRIPE_SECRET_KEY=your_stripe_secret_key CLOUDINARY_NAME=your_cloudinary_name CLOUDINARY_API_KEY=your_cloudinary_api_key CLOUDINARY_API_SECRET=your_cloudinary_api_secret Replace the placeholders (your_username, your_password, etc.) with your actual credentials. Do not share this file with anyone or commit it to version control.

Socket.IO Environment Variables Navigate to the socket directory (or your Socket.IO implementation directory):

