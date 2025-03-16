# Job Portal

Job Portal is a web app which helps in streamlining the flow of job application process. It allows users to select there roles (applicant/recruiter), and create an account. In this web app, login session are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, ppending/accept/reject applications, and view resume. And, an applicant can view jobs, perform fuzzy search with various filters, apply for jobs with an CV, view applications. Hence, it is an all in one solution for a job application system.

- Install Node JS, MYsql in the machine.
- - Install dependencies in directory: `npm install`
- Start express server: `npm start`
- Server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.

## Dependencies:

dependencies": {
        "bcrypt": "^5.1.1",
        "cookie-parser": "^1.4.7",
        "dotenv": "^16.4.5",
        "ejs": "^3.1.10",
        "express": "^4.21.1",
        "express-session": "^1.18.1",
        "jsonwebtoken": "^9.0.2",
        "multer": "^1.4.5-lts.1",
        "mysql": "^2.18.1",
        "mysql2": "^3.11.3",
        "nodemon": "^3.1.7",
        "sequelize": "^6.37.5",
        "sequelize-cli": "^6.6.2"
        
# Machine Specifications

Details of the machine on which the webapp was tested:

- Operating System: Elementary OS 5.1 (Hera)
- Terminal: Bash
- Processor: Intel Core i7-8750H CPU @ 2.20 GHz 2.21 GHz
- RAM: 16 GB
