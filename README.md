# Job-Seeker-App
Job Seeker app is a simple web application that allows users to view and manage jobs and applay for them. It provides features for adding new jobs, viewing details of jobs and their comapnies, seraching and filter them. Also they can't do all of this if they don't have an account and are not loged in.

## Technologies Used

- Frontend: Angular
- Backend: NestJS w/ TypeORM
- Database: PostgreSQL

## How to start it

### Prerequisites

- Node.js 
- PostgreSQL

### Installation

1. First clone the repository
2. Install dependencies for the frontend:
cd /job-seeker-app , and then npm install
3. Install dependencies for the backend:
cd /job-seeker-api , and then npm install
4. Create a PostgreSQL database named `job-seeker-db` and create and check .env file.


### Usage 

( open two termialns, for better work)
1. Start the backend server: npm run start:dev
2. Start the frontend server: npm start
3. Open your web browser and visit front-end url to access Job-Seeker app.

## Features

- View a list of jobs and applied jobs in the jobs page
- View a details for every job and also thier comapny in another page
- Add new jobs with thier information and comapny informations
- Dynamic searching and filtering jobs
- Edditing jobs infromations
- Fully functional authentication and registration
- Profile(user) panel for loged in user informations 
