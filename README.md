Project Title: Hayroo – E-Commerce Web App
Developer: Abin Binu
Intern at Blackbucks

Project Overview
Hayroo is a full-stack e-commerce platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It supports product browsing, cart management, order placement, and payment via Braintree. The project is responsive, scalable, and ready for deployment.

Setup Instructions
System Requirements:

Node.js, NPM

MongoDB Atlas account

Braintree credentials

Environment Variables (server/.env):

ini
Copy
Edit
BRAINTREE_MERCHANT_ID=your_id  
BRAINTREE_PUBLIC_KEY=your_key  
BRAINTREE_PRIVATE_KEY=your_key  
DATABASE=your_mongo_atlas_uri  
Installation:

bash
Copy
Edit
cd client && npm install  
cd ../server && npm install  
Run Locally:

pgsql
Copy
Edit
From server/: npm run start:dev  
From client/: npm start  
Open: http://localhost:3000/  
Deployment
Backend: Deploy server/ to Render using render-deploy-backend branch.

Frontend: Deploy client/ to Vercel or Netlify.

Use MongoDB Atlas URI in .env instead of local DB path.

Demo Video:https://www.youtube.com/watch?v=lXk14qt2D28&ab_channel=Hasan
