# RS School ShortTrack Hiring Management System

The RS School ShortTrack Hiring Management System is a tool manage the hiring process for RS School Graduates (junior frontend and junior full-stack developers). It provides a structured workflow for candidates, HR specialists, mentors, and admins.
This system enhances transparency and efficiency in the hiring process, helping RS School coordinators streamline operations and reduce administrative workload.

## Key Features
Candidate Portal:
Candidates can submit their applications, specifying skills, location, and work preferences.
Candidates can view their application status.

HR/TA Dashboard:
HR specialists can track application progress, verify eligibility, and manage interview results.
HR specialists can filter candidates by skills, location, and employment readiness.

Mentor/Intervier Dashboard:
Mentors validate technical skills such as Angular, React, and Node.js.

Admin Dashboard:
Admins oversee the entire hiring process, ensuring smooth operations and managing system settings.

Interview & Eligibility Tracking:
Systematic storage of General Interview (GI) and Technical Interview (TI) results, eligibility checks, and recruiter notes.

## RS School ShortTrack Hiring Management System – Candidate Application Process

### **Step 1: Candidate Application Submission**  
- The candidate submits an application, providing:  
  - **Personal details** (Name, Location, Contact Info)  
  - **Work preferences** (Relocation, Office/Hybrid)  
  - **Technical skills** (e.g., React, Angular, Node.js)  
  - **Resume (CV) & GitHub profile**  
  - **English proficiency level**  
  - **Legal work status and documents**  
  - **Salary expectations & availability**  

### **Step 2: Application Review (Admin Decision)**  
- The **admin sees**:  
  - The **candidate’s submitted data**  
  - Additional details from the **RS APP platform** (Courses, Certifications, Badges like Gratitude)  

- **Admin Actions**:  
  - **Decides whether to proceed with the application** or reject it (with a comment to the candidate)  
  - **Assigns a mentor** (or multiple mentors) responsible for **Technical Skill Validation**  
  - **Can validate the candidate’s claimed skills** based on RS APP data  
  - **Leaves comments for HR & mentors** to provide additional context  

### **Step 3: Application Validation**  
_(Includes Technical & General Evaluation)_  

Once the admin approves the application, the validation phase begins. The following steps can happen **in any order or simultaneously**:  

#### **General Interview (GI) – HR Review**  
- HR evaluates:  
  - Candidate’s **motivation**, **communication skills**, and **cultural fit**  
  - Salary expectations and availability  
  - Preferred work format (Office/Hybrid)  

#### **Technical Interview (TI) – Mentor Review (if required)**  
- If needed, mentors conduct a **Technical Interview**, assessing:  
  - Problem-solving and coding skills  
  - System design and technical reasoning

- Mentors assess the candidate’s technical skills:  
  - **Verified** – Skill is confirmed through past projects or screening  
  - **Not Verified** – Further assessment is needed  

### **Step 4: Decision & Feedback**  
After all evaluations, **admins make the final decision**:  

- **Accepted → Short List**  
  - The candidate is added to the **short list**.  
  - This means that when a suitable **EPAM project opens**, the candidate will be invited for an interview.  

- **Rejected**  
  - The candidate is informed and receives feedback.  

- **Needs Improvement**  
  - The candidate is advised to improve their skills **independently** or **with mentor support**.  

### **Step 5: Hiring & EPAM Onboarding**  
- If a **shortlisted candidate successfully passes an interview for an EPAM project**, the **admin or HR updates the status to "Hired"** in the system.  

## Candidate Fields in the System:
- First Name and Last Name
- Candidate’s City
- Cities the candidate is willing to relocate to, if necessary
- Email
- Telegram
- Document validity date (for legal employment)
- Document type
- Name of the responsible recruiter (name only)
- English proficiency level
- Results of the Eligibility Check
- Time until the candidate is ready to start working after signing the offer
- Salary expectations
- Work readiness (Office / Hybrid)
- Link to CV
- Candidate’s GitHub profile
- GI Results (General Interview) – includes evaluation, interview link, and comment
- TI Results (Technical Interview) – includes evaluation, interview link, and comment
- Skills (with mentor verification):
    - Angular (Verified / Not Verified, responsible mentor)
    - React (Verified / Not Verified,  responsible mentor)
    - Node.js (Verified / Not Verified, responsible mentor)
    - Other technologies (e.g., React Native, Verified / Not Verified, responsible mentor)
- Comments Candidate
- Comments Admin 
- Comments Mentor 
- Comments HR

## Authentication and Access Control
### GitHub OAuth:
Use GitHub for authentication. 

### Role-Based Access Control (RBAC):
Define roles (candidate, HR, mentor, administrator) to ensure that each user can access only the data relevant to their role. 





