# CareVibe

CareVibe is a healthcare patient management application that allows patients to register, book, and manage their appointments with doctors. It features administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications.

## Live Demo

To see the website in action, check out this [demo](https://carevibe.vercel.app/)

## Tech Stack

- **Next.js**
- **Appwrite**
- **Typescript**
- **TailwindCSS**
- **ShadCN**
- **Twilio**
- **Sentry**

## Features

- **Patient Registration**: Users can sign up and create a personal profile.
- **Appointment Booking**: Patients can schedule appointments with doctors at their convenience and book multiple appointments if needed.
- **Admin Appointment Management**: Administrators can efficiently view and manage all scheduled appointments.
- **Admin Appointment Confirmation/Scheduling**: Admins can confirm and set appointment times to ensure they are properly scheduled.
- **Admin Appointment Cancellation**: Administrators have the authority to cancel any appointment as necessary.
- **SMS Notifications on Appointment Confirmation**: Patients receive SMS notifications confirming their appointment details.
- **File Upload with Appwrite Storage**: Users can securely upload and store files within the app using Appwrite storage services.
- **Performance Tracking with Sentry**: The application uses Sentry to monitor performance and detect errors.

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/carevibe.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd carevibe
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Set up environment variables:**
   Create a `.env.local` file in the root of the project and add the following environment variables:

   ```env
   NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
   PROJECT_ID=
   API_KEY=
   DATABASE_ID=
   PATIENT_COLLECTION_ID=
   APPOINTMENT_COLLECTION_ID=
   NEXT_PUBLIC_BUCKET_ID=
   NEXT_PUBLIC_ADMIN_PASSKEY=111111
   ```

5. **Start the development server:**
   ```bash
   npm run dev
   ```

## Usage

- **Patient Registration:** Users can sign up and create their profile.
- **Appointment Booking:** Patients can book new appointments with available doctors.
- **Admin Management:** Admins can manage, confirm, and cancel appointments.
- **SMS Notifications:** Patients receive SMS notifications on appointment confirmation.
- **File Uploads:** Users can securely upload files using Appwrite storage.

