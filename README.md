<div align="center">
  <br />
    <a href="https://youtu.be/lEflo_sc82g?feature=shared" target="_blank">
      <img src="https://github.com/adrianhajdin/healthcare/assets/151519281/a7dd73b6-93de-484d-84e0-e7f4e299167b" alt="Project Banner">
    </a>
  <br />
  
  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  </div>

  <br />
 <p>Welcome Screen </p><br />
   <img src="https://github.com/user-attachments/assets/7f35c87e-02ec-4e5c-81b7-a40731fdaf90" alt="Welcome Screen">
  
  <br /> 

<br />
 <p>Patient Registration </p><br />
   <img src="https://github.com/user-attachments/assets/0b60b500-fea5-44cb-962c-432bd883cf2a" alt="Patient Registration">
 
  <br /> 
<br /> 
 
 <p>Patient Registration 2nd part</p><br />
   <img src="https://github.com/user-attachments/assets/aa77e153-6c51-4e34-84b4-85ae7d74ea79" alt="Patient Registration continued">
  
  <br /> 
  <br />
 
 <p>Admin dashboard </p>  <br /> 
   <img src="https://github.com/user-attachments/assets/9c505804-daee-496c-91f8-7503c24baa5b" alt="Admin dashboard">
 
  <br />
</div>

## <a name="introduction">🤖 Introduction</a>

A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors, featuring administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.


## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Appwrite
- Typescript
- TailwindCSS
- ShadCN
- Twilio

## <a name="features">🔋 Features</a>

👉 **Register as a Patient**: Users can sign up and create a personal profile as a patient.

👉 **Book a New Appointment with Doctor**: Patients can schedule appointments with doctors at their convenience and can book multiple appointments.

👉 **Manage Appointments on Admin Side**: Administrators can efficiently view and handle all scheduled appointments.

👉 **Confirm/Schedule Appointment from Admin Side**: Admins can confirm and set appointment times to ensure they are properly scheduled.

👉 **Cancel Appointment from Admin Side**: Administrators have the ability to cancel any appointment as needed.

👉 **Send SMS on Appointment Confirmation**: Patients receive SMS notifications to confirm their appointment details.

👉 **Complete Responsiveness**: The application works seamlessly on all device types and screen sizes.

👉 **File Upload Using Appwrite Storage**: Users can upload and store files securely within the app using Appwrite storage services.

👉 **Manage and Track Application Performance Using Sentry**: The application uses Sentry to monitor and track its performance and detect any errors.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>

## 💡 What I Learned

I gained valuable experience in multiple areas of modern web development.

##### **Next.js Development**

- Optimized Images
- API Routes
- Server-Side Rendering (SSR) and Static Site Generation (SSG)
- File-based routing system (dynamic routes)
- Data Fetching Methods
- SEO Optimization
- Deployment

##### **Tailwind CSS**

- Utility-First CSS Approach
- Responsive Design
- Customization and Theming
- Advanced Layout Techniques
- Pseudo-Classes and States

##### **Appwrite Backend Services**

- User Authentication
- Database Integration
- File Storage
- Real-Time Data

##### **Twilio SMS Integration**

- Sending SMS Notifications
- API Interaction
- Error Handling

##### **Version Control with Git**

- Committing changes and managing branches.
- Collaborating and tracking progress over time.
- Maintained clear documentation and code comments.
