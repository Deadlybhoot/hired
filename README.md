
# Hired a Full Stack Job Portal with React JS, Tailwind CSS, Supabase, Clerk, Shadcn UI Tutorial 🔥🔥

- Hired is a dynamic job portal platform designed to connect job seekers with their dream jobs and enable recruiters to post job openings within their companies. The platform offers a user-friendly interface, providing two distinct options for job seekers and recruiters upon visiting the site.

- Using Supabase, I've ensured the integrity of the data, allowing only recruiters to post, delete, or update job listings, while job seekers can apply to jobs, not recruiters.

![Screenshot (18)](https://github.com/user-attachments/assets/2c2a5729-193a-41e5-a53c-3913e788c00a)




## For Recruiters

- To begin, recruiters must sign up on the platform. Once authenticated, they are redirected to the job posting page. 


![Screenshot (39)](https://github.com/user-attachments/assets/18c1eed8-b321-4ec1-9edb-3be009f9c9d1)


- Here on this page recruiter can create new job. A dedicated text editor is available for recruiters to outline job requirements.The "My Jobs" section allows recruiters to track the status of all jobs.

![Screenshot (22)](https://github.com/user-attachments/assets/9027aadf-7780-491e-aec5-c7e4e89cf7b8)

- Under my jobs recruiter can see how many applicants have applied for particular job. 

![Screenshot (23)](https://github.com/user-attachments/assets/3689e078-4092-496c-8b51-7ce0b0e2dd44)


![Screenshot (24)](https://github.com/user-attachments/assets/1b483809-94ca-42c8-87a5-23f657b0c188)

- Recruiter can update the job status as open or closed. Recruiters can also review applications, notify applicants about interviews, hiring decisions, or rejections.

![Screenshot (31)](https://github.com/user-attachments/assets/a8485315-3f6b-46e0-a6e5-2bf31e7cf254)
## For Job Seekers

- Upon authentication, job seekers can view the latest job postings, search for specific roles by location or company, and save jobs for later consideration. Applying to jobs is straightforward, and users can upload their resumes for recruiters to review. 

![Screenshot (27)](https://github.com/user-attachments/assets/a55ebf01-c4ab-4089-a798-436ff3c340e2)


- The "My Jobs" section enables job seekers to track the status of their applications, whether they are applied, interviewing, hired, or rejected.

![Screenshot (28)](https://github.com/user-attachments/assets/b8cc4aba-987f-4cbf-a40a-f625d7e5559e)

![Screenshot (29)](https://github.com/user-attachments/assets/3f139ede-6cb3-48c3-9a38-17b68a8b7e86)

![Screenshot (30)](https://github.com/user-attachments/assets/ac2f40c8-128c-4987-bc77-687b8bb4a1e5)


## Challenges

- Integrating clerk with supabase
https://supabase.com/partners/integrations/clerk
## Future Enhancements

- Job Recommendations: Implement a machine learning model to suggest jobs to users based on their profile and application history.

- Employer Dashboard: Develop a comprehensive dashboard for employers to manage job postings and view analytics on their listings.

- Messaging System: Add a real-time chat feature to facilitate direct communication between employers and job seekers.
## Tech Stack

- React
- vite
- Tailwindcss
- Shadcn => UI Library
- Clerk => Authentication & Oraganization management
- supabase=> Database




## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
  npm run dev
```
    
## Setup Environment variable


Create a new file named `.env.local` in the root of your project and add the following content:

```env
VITE_SUPABASE_URL=
VITE_SUPABASE_ANON_KEY=
VITE_CLERK_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)



## Authors

Follow me Thank You 😊

- [@Deadlybhoot](https://www.github.com/Deadlybhoot)
- https://www.linkedin.com/in/akshay-satav-0610741a9
