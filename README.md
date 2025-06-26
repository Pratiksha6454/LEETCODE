📘 LeetCode Tracker Project
This is a full-stack project that helps users track their LeetCode progress efficiently.

🚀 Getting Started
Follow these steps to run the project on your local machine:

1. 📦 Install Dependencies
Navigate to the frontend and backend folders and run:

bash
Copy
Edit
npm install
Do this in both the frontend and backend directories.

2. 🌐 Create Required Accounts
Make sure you have accounts set up on the following platforms:

MongoDB Atlas – for storing your data.

Cloudinary – for image uploads (if any).

Redis – for caching or session management.

3. 🔐 Set Up Environment Variables
Create a .env file in your backend directory and add the necessary keys:

env
Copy
Edit
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
REDIS_URL=your_redis_url
PORT=your_preferred_port (e.g., 5000)
Add frontend .env too if needed (e.g., API base URL).

4. 🖥️ Run the Project
Open two separate terminals:

Terminal 1 – Backend
bash
Copy
Edit
cd backend
npm start
Terminal 2 – Frontend
bash
Copy
Edit
cd frontend
npm start
The frontend will usually be available at: http://localhost:3000
The backend will usually run at: http://localhost:5000 (or your defined port)

✅ You're Ready!
You can now use your LeetCode Tracker project locally. Happy coding! 🚀
