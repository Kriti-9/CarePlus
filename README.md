# A HealthCare Management System

Build a comprehensive healthcare patient management application with Next.js, TypeScript, TailwindCSS, Appwrite, and Twilio.

## 📋 Table of Contents

- 🤖 [Introduction](#introduction)
- ⚙️ [Tech Stack](#tech-stack)
- 🔋 [Features](#features)
- 🤸 [Quick Start](#quick-start)
- 🕸️ [Snippets](#snippets)
- 🔗 [Assets](#assets)

## 🤖 Introduction

A healthcare patient management application that enables patients to register, book, and manage their appointments with doctors. Includes administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.

## ⚙️ Tech Stack

- Next.js
- Appwrite
- TypeScript
- TailwindCSS
- ShadCN
- Twilio

## 🔋 Features

- **Register as a Patient**: Users can create and manage a personal profile.
- **Book a New Appointment**: Patients can schedule and manage appointments.
- **Admin Management**: Administrators can view, confirm, and cancel appointments.
- **SMS Notifications**: Patients receive SMS updates about appointment details.
- **Responsive Design**: Fully responsive for all devices.
- **File Upload**: Secure file storage using Appwrite.
- **Performance Tracking**: Monitored and tracked using Sentry.

## 🤸 Quick Start

### Prerequisites

Ensure the following are installed:

- Git
- Node.js
- npm

### Cloning the Repository

```bash
git clone https://github.com/Kriti-9/healthcare.git
cd healthcare
```

### Installation

Install dependencies:

```bash
npm install
```

### Set Up Environment Variables

Create a `.env.local` file in the root directory and add:

```
# APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace placeholder values with your Appwrite credentials.

### Running the Project

Start the development server:

```bash
npm run dev
```

Open `http://localhost:3000` in your browser to view the application.

## 🕸️ Snippets

- `tailwind.config.ts`
- `app/globals.css`
- `types/index.d.ts`
- `types/appwrite.types.ts`
- `lib/utils.ts`
- `lib/validation.ts`
- `constants/index.ts`

## 🔗 Assets

Public assets used in the project can be found in the `public` directory.
