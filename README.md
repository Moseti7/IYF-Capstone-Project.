# IYF-Capstone-Project.
Teaching and examination management platform designed for secondary school and private centers.
#PURPOSE OF THE PROJECT
It is to provide a centralized digital platform for secondary schools and private tuitioncenters to manage onl;ine teaching and examination efficiently.
#Problem it solves
Many secondary schools and private tuition centers rely on multiple disconnected tools such as WhatsApp, Zoom, Google Meet, Google Forms, and manual record books to manage teaching and examinations. This creates several challenges:
Poor organization of class links and learning materials
Difficulty tracking student attendance and performance
Manual recording and calculation of exam results
Time-consuming exam preparation and report writing
Lack of a centralized system for managing online learning
Teachers often spend excessive time handling administrative tasks instead of focusing on actual teaching. Students also struggle to keep track of class schedules, exam links, and academic progress.
Tech Stack
React
React is used to build the frontend user interface of the application. It handles:
User dashboards (Teacher, Student, Admin)
Class scheduling pages
Exam management interface
Performance analytics display
Navigation and responsive layout
React ensures the platform is fast, interactive, and responsive across devices.
Supabase
Supabase is used as the backend service for:
User authentication (Admin, Teacher, Student login)
Database management (students, classes, exams, results, sessions)
Secure data storage
Role-based access control
Supabase allows the system to securely store and manage all academic data in real time.
Hugging Face
Hugging Face is integrated to provide AI-powered academic assistance, including:
Generating exam questions (MCQs and theory questions)
Creating marking schemes
Writing automated student report comments
Summarizing lesson content
Providing performance-based feedback suggestions
 #Capabilities of the App
EduLink AI provides the following capabilities for secondary schools and private tuition centers:
 User Authentication & Role Management
Secure login and registration
Role-based access (Admin, Teacher, Student)
Protected dashboards for each user type
 Online Class Management
Create and schedule virtual classes
Add Zoom or Google Meet links
View upcoming and past sessions
Centralized access to all class meetings
 Learning Material Management
Upload and share notes, PDFs, and resources
Attach Google Drive links
Organize materials by subject or class
 Online Examination Management
Add exams with Google Forms links
Set deadlines for assessments
Record and manage student marks
Automatically calculate totals, averages, and grades
 Academic Performance Tracking
View individual student performance
Monitor class performance analytics
Identify top-performing and struggling students
Generate academic summaries
 AI-Powered Academic Support
Generate exam questions (MCQs & theory)
Create marking schemes
Write automated report card comments
Summarize lesson content
Suggest revision recommendations for weak areas
 Dashboard & Analytics
Real-time overview of academic activities
Visual performance indicators
Easy navigation between teaching and examination modules
This makes your project look:
✔ Structured
✔ Professional
✔ Complete
#Installation & Setup Steps
Follow the steps below to run EduLink AI locally:
1️⃣ Clone the Repository
Bash
Copy code
git clone https://github.com/https://github.com/Moseti7/iyf-capstone-project.git
cd iyf-capstone-project
2️⃣ Install Dependencies
Make sure you have Node.js (v18 or later) installed.
Then run:
Bash
Copy code
npm install
This will install all required project dependencies.
3️⃣ Set Up Environment Variables
Create a .env file in the root of the project and add the following:
Environment
Copy code
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_HUGGINGFACE_API_KEY=your_huggingface_api_key
Replace the values with your actual credentials from:
Supabase dashboard
Hugging Face account
4 Run the Development Server
Start the project locally:
Bash
Copy code
npm run dev
The app will run at:
Copy code

http://localhost:5173
5️⃣ Build for Production (Optional)
To create a production build:
Bash
Copy code
npm run build
