URL Shortener with Analytics

This is a simple URL shortener project built using the MERN (MongoDB, Express, React, Node.js) stack. The project allows users to generate short URLs and track their usage analytics.

Features

Shorten long URLs to unique short URLs.

Track total clicks and visit history for each short URL.

Retrieve analytics data for each shortened URL.

Full-stack implementation with React frontend and Express/Node.js backend.

Uses MongoDB for storing URLs and visit history.

Tech Stack

Frontend: React.js, Axios

Backend: Node.js, Express.js, MongoDB, Mongoose

Database: MongoDB (Atlas or Local)

Other Tools: shortid (for generating unique short URLs), CORS, dotenv

Installation

Prerequisites

Ensure you have the following installed:

Node.js

MongoDB (Local or Atlas)

Clone the Repository

Backend Setup

Navigate to the backend folder and install dependencies:

Create a .env file in the backend folder and add your MongoDB URI:

Start the backend server:

Frontend Setup

Navigate to the frontend folder and install dependencies:

Start the React frontend:

API Endpoints

Shorten a URL

POST /url

Request Body:

Response:

Get Analytics for a Short URL

GET /url/analytics/:shortId

Response:

Redirect to Original URL

GET /:shortId

Redirects to the original long URL.

Deployment

You can deploy the frontend on Vercel and the backend on a cloud platform like Render or Railway.

Deploy Backend to Railway

Install the Railway CLI and login:

Deploy the backend:

Deploy Frontend to Vercel

Install Vercel CLI and login:

Deploy the frontend:

Contributing

Feel free to open issues and pull requests for improvements.

![image](https://github.com/user-attachments/assets/19053fb2-6dab-4977-88c4-047b9309c919)
![image](https://github.com/user-attachments/assets/ec070c66-8e83-4638-948f-52565f8dcdca)

