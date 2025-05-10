# MindConnect - Mental Health Platform
MindConnect is a full-stack platform designed to help individuals with mental health challenges by offering anonymous access to features such as free counseling, journaling for personal reflection, and literary resources on mental well-being.

## Features
- Anonymous access to counseling (via text messages)
- Journaling for personal reflection
- Literary resources on mental well-being
- Real-time chat feature
- Analytics and tracking (via Sentry)

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/ShivaniAgarwal01/MindConnect.git

 2.Inside the backend/ directory, create a file named .env and add the following line:
   ```bash
   DATABASE_URL="postgresql://<username>:<password>@localhost:5432/<your_database>?schema=public"
   MONGO_URI=mongodb://localhost:27017/your-database
   JWT_SECRET=your_secret_key_here 
   ACCESS_TOKEN_SECRET=your_access_token_secret_here
   REFRESH_TOKEN_SECRET=your_refresh_token_secret_here  

   npx prisma generate
   npx prisma migrate dev --name init
   npm run dev
