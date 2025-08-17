🏷️ BestBid – Online Auction System

BestBid is a virtual bidding platform where sellers can list products for auction and buyers can participate in real-time bidding. Built with the MERN stack, it ensures secure transactions, user-friendly interfaces, and scalable performance.

🚀 Features

🔑 User Authentication – Secure login and registration for buyers and sellers.

📦 Product Listing – Sellers can add, edit, and manage items for auction.

⏱️ Real-time Bidding – Buyers can place bids and track auctions dynamically.

💳 Payment Integration – Secure checkout using Stripe API.

🖼️ Image Storage – Product images hosted on Cloudinary.

📊 Dashboard – Role-based dashboards for sellers, buyers, and admins.

📱 Responsive UI – Built with React.js + Bootstrap 5 for smooth experience on all devices.

🛠️ Tech Stack

Frontend: React.js, Bootstrap 5
Backend: Node.js, Express.js
Database: MongoDB
Payments: Stripe
Storage: Cloudinary

📸 Screenshots (Optional)

(Add some UI screenshots here for better presentation)

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/itznihal/ONLINE-AUCTION.git
cd ONLINE-AUCTION


Install dependencies

npm install
cd client && npm install


Create a .env file with:

MONGO_URI=your_mongodb_connection_string
STRIPE_SECRET_KEY=your_stripe_key
CLOUDINARY_URL=your_cloudinary_config


Run the backend

npm start


Run the frontend

cd client  
npm start
