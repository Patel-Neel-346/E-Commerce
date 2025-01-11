﻿# E-Commerce

SetUp the Project 
1) Backend
   1.1) cd server // go to server folder terminal
   1.2) npm i // install node modules and extra package
   1.3) create .env file
   1.4) set .env variables
   1.5) here .env variables
      PORT=port Number //8000
      MONGODB_URL="MongoDB atlas Cluster Url"

      CLOUDINARY_API_KEY='your Cloudinary_api_key'
      CLOUDINARY_SECRET_KEY="Your Cloudinary Secret Key" // you can find this in Cloudinary website by creating Account in Cloudinary
      CLOUDINARY_NAME="Your Cloud Name in Cliudinary"


      JWT_SECRET="JWT Secret" // you can set Whatever you want like SpiderMan Something like that or you can set your Name here
   
      ADMIN_EMAIL="admin@gmail.com" // this is admin Email for Admin Site
      ADMIN_PASSWORD="123456789" // its password
      
      STRIPE_SECRET="Stripe Secret" // this is Stripe Secert Key You can Find in stripe in test mode for Payment 
      
      RAZORPAY_ID="Razorpay Id" // you can find it in razorPay website
      RAZORPAY_SECRET="RazorPay_secret Key" // this is also avaliable in razorpay website
   
   1.6)last step run backend
       npm run dev

2) Frontend
   2.1) cd frontend // go to server folder terminal
   2.2) npm i // install node modules and extra package
   2.3) create .env file
   2.4) set .env variables
   2.5) here .env variables
     VITE_BACKEND_URL='Your Backend Url' // like if your server is ruuning on 8000 so eg.'http://localhost:8000'

     VITE_RAZORPAY_ID="RazorPayId" //same is in Server .env file just copy from server's RazorPay_id .env variable

   
   2.6)last step run frontend
       npm run dev

  3)Admin
   3.1) cd admin // go to server folder terminal
   3.2) npm i // install node modules and extra package
   3.3) create .env file
   3.4) set .env variables
   3.5) here .env variables
     VITE_BACKEND_URL='Your Backend Url'  // like if your server is ruuning on 8000 so eg.'http://localhost:8000'
     VITE_ADMIN_EMAIL="admin@gmail.com" // this is admin Email for Admin Site
     VITE_ADMIN_PASSWORD="123456789" // its password

   
   3.6)last step run admin
       npm run dev


  Live Preview For Frontend Site
  http://forever-frontend-gilt.vercel.app

  Live Preview For Admin Site
  http://forever-admin-taupe.vercel.app

