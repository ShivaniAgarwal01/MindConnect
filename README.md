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

   Replace the placeholders:
   <username> → your PostgreSQL username (commonly postgres)
   <password> → your PostgreSQL password
   <your_database> → the name of your database (e.g., mindconnect)
