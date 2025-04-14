# 🛒 E-Commerce

## 🚀 Set Up the Project

### 1️⃣ Backend
1. **Navigate to the server folder**  
    ```bash
    cd server
    ```
2. **Install dependencies**  
    ```bash
    npm i
    ```
3. **Create a `.env` file**  
4. **Set up environment variables**  
    Here are the required `.env` variables:
    ```env
    PORT=8000 # Port number
    MONGODB_URL="MongoDB Atlas Cluster URL"

    CLOUDINARY_API_KEY="Your Cloudinary API Key"
    CLOUDINARY_SECRET_KEY="Your Cloudinary Secret Key" # Found on the Cloudinary website
    CLOUDINARY_NAME="Your Cloudinary Name"

    JWT_SECRET="Your JWT Secret" # Example: SpiderMan or your name

    ADMIN_EMAIL="admin@gmail.com" # Admin email for the admin site
    ADMIN_PASSWORD="123456789" # Admin password

    STRIPE_SECRET="Your Stripe Secret Key" # Found in Stripe (test mode for payments)

    RAZORPAY_ID="Your Razorpay ID" # Found on the Razorpay website
    RAZORPAY_SECRET="Your Razorpay Secret Key" # Found on the Razorpay website
    ```
5. **Run the backend**  
    ```bash
    npm run dev
    ```

---

### 2️⃣ Frontend
1. **Navigate to the frontend folder**  
    ```bash
    cd frontend
    ```
2. **Install dependencies**  
    ```bash
    npm i
    ```
3. **Create a `.env` file**  
4. **Set up environment variables**  
    Here are the required `.env` variables:
    ```env
    VITE_BACKEND_URL="Your Backend URL" # Example: http://localhost:8000

    VITE_RAZORPAY_ID="Your Razorpay ID" # Same as the server's Razorpay ID
    ```
5. **Run the frontend**  
    ```bash
    npm run dev
    ```

---

### 3️⃣ Admin
1. **Navigate to the admin folder**  
    ```bash
    cd admin
    ```
2. **Install dependencies**  
    ```bash
    npm i
    ```
3. **Create a `.env` file**  
4. **Set up environment variables**  
    Here are the required `.env` variables:
    ```env
    VITE_BACKEND_URL="Your Backend URL" # Example: http://localhost:8000
    VITE_ADMIN_EMAIL="admin@gmail.com" # Admin email for the admin site
    VITE_ADMIN_PASSWORD="123456789" # Admin password
    ```
5. **Run the admin**  
    ```bash
    npm run dev
    ```

---

## 🌐 Live Previews
- **Frontend Site**: [Live Preview](http://forever-frontend-gilt.vercel.app)  
- **Admin Site**: [Live Preview](http://forever-admin-taupe.vercel.app)

🎉 You're all set! Enjoy building your E-Commerce project!
