# Project Setup and Usage

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/Darkhunt16/Job_Board.git
   cd Job_Board
   ```

2. **Create the Env**

 Create a `config.env` file in the backend folder and add your environment variables:
 ```sh
 PORT =4000

 MONGO_URI= Your Database URL

 FRONTEND_URL=Enter the frontend URL(http://localhost:5173)

 JWT_SECRET_KEY= Anything Random

 JWT_EXPIRES=3d

 COOKIE_EXPIRES=3

 SMTP_HOST=smtp.gmail.com

 SMTP_PORT=465

 SMTP_SERVICE=gmail

 SMTP_MAIL= Enter a Working Gmail

 SMTP_PASSWORD=

 CLOUDINARY_CLOUD_NAME= Enter your cloudinary cloud name

 CLOUDINARY_API_KEY= Enter your cloudinary api key

 CLOUDINARY_API_SECRET= Enter your cloudinary secret key


```
3. **Installing dependencies and Running the Frontend and Backend:**
   
   For Backend
   ```sh
   cd backend
   npm install
   npm run dev
   ```

   For Frontend
   ```sh
   cd frontend
   npm install
   npm run dev
   ```



The server will start at `http://localhost:5173` by default.

Deployed Link: (https://job-board-vercel-deployed.vercel.app)