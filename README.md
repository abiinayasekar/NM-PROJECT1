📝 Blogging Platform

A simple Blogging Platform built using Node.js, Express.js, and MongoDB, with optional frontend support using React or HTML-CSS. This platform allows users to create, edit, and publish blog posts, while admins can manage users and moderate content.
__________________________________________________________________________________________________________________________________________________

🚀 Features
> Admin

* Manage users (add, edit, delete, block)

* Approve or delete posts

* Moderate comments

> User

* Register and log in

* Create, edit, and delete blog posts

* Comment on other posts

* Like and share posts

> System

* Real-time updates for posts and comments

* Optional email notifications for new followers or comments
  _________________________________________________________________________________________________________________________________________________

🛠️ Tech Stack

* Backend: Node.js, Express.js

* Database: MongoDB

* Frontend (optional): React / HTML, CSS, Bootstrap or Tailwind CSS

* Other Tools: Nodemailer (email notifications), JWT (authentication), Postman (API testing)
__________________________________________________________________________________________________________________________________________________

⚡ API Endpoints
_________________________________________________________________________________________________________________________________________________
🔐 Auth APIs

* POST /api/auth/register → Register a new user

* POST /api/auth/login → Login and get JWT token

📰 Post APIs

* POST /api/posts → Create a new post

* PUT /api/posts/:id → Edit a post

* DELETE /api/posts/:id → Delete a post

* GET /api/posts → Get all posts

* GET /api/posts/:id → Get a single post

💬 Comment APIs

* POST /api/posts/:id/comments → Add a comment

* DELETE /api/comments/:id → Delete a comment

👥 User APIs

* GET /api/users/:id → Get user profile

* PUT /api/users/:id → Update user profile

* DELETE /api/users/:id → Delete user

🛠️ Installation & Setup
_________________________________________________________________________________________________________________________________________________
1.Clone the repo

git clone https://github.com/abiinayasekar/NM-PROJECT1.git

cd Blogging-Platform

2.Install dependencies

cd backend
npm install
__________________________________________________________________________________________________________________________________________________

Setup environment variables

Create a .env file inside backend/ with the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email@example.com   # (for email notifications)
EMAIL_PASS=your_password
_________________________________________________________________________________________________________________________________________________
Run the server

npm start
__________________________________________________________________________________________________________________________________________________
✅ Testing

Use Postman or Thunder Client to test the API endpoints.
