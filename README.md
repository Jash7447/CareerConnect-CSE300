# CareerConnect-CSE300# CareerConnect-CSE300

## Project Overview

CareerConnect is a job portal platform designed to connect job seekers with employment opportunities and employers with talented individuals. Whether you are looking for a new job or recruiting new talent, CareerConnect is your go-to platform.

## Features

- SignIn / SignUp
- Forget Password
- Post A Job
- View  All Jobs
- View Details of Any Job
- BookMark Jobs
- Track Your BookMark Jobs in DataTable View
- Track Your Applied Jobs in DataTable View 
- Track Your Posted Jobs and view Submitted Application 
- Accept and Reject Different Application 
- Status Updated for applied Job based on Job poster action 
- JWT validation on each Authorized Request 
#### ( Below Feature works only in Local Environment as Vercel Don't allow write operation in free plan so CV are unable to saved in production while you can use firebase , or aws s3 bucket to store , but works fine in local App ) 
- View or download Applicant CV's 

## Getting Started

These instructions will help you get a copy of CareerConnect up and running on your local machine for development and testing purposes.

### Prerequisites

To run CareerConnect, you'll need the following:

- Node.js: Make sure you have Node.js installed. You can download it [here](https://nodejs.org/).

### Tech

- Nextjs
- Tailwind css
- Redux toolkit
- Joi Validation
- MongoDB
- SWR hooks for fetching API


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

- `DB_URI` = Your mongoDB URL

- `JWT_SECREAT` = Your custom JWT_SECREAT key

- `NEXT_PUBLIC_API_BASE_URL` =  Base URL for localhost  => http://localhost:3000


### To get project

1. Clone the repository:

   ```bash
   git clone https://github.com/kathan07/CareerConnect-CSE300.git



## Installation

Install my-project with npm

```bash
  npm install
  npm run dev (for development server)
  npm run build (for Production)
  npm run preview (To View Production Server )
```