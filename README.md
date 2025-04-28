
# Firebase Project Setup Guide (Backend Integration)

Follow this step-by-step guide to set up your Firebase project with Authentication, Firestore, and Realtime Database. This guide is tailored for backend development using Python.

---

## Table of Contents

1. [Create a Firebase Project](#step-1-create-a-firebase-project)
2. [Set Up Firebase Features](#step-2-set-up-build-features)
   - [Authentication Setup](#step-21-authentication-setup)
   - [Firestore Database Setup](#step-22-firestore-database-setup)
   - [Realtime Database Setup](#step-23-realtime-database-setup)
3. [Register Your App](#step-3-register-your-app)
4. [Generate Firebase Admin SDK Credentials](#step-4-generate-firebase-admin-sdk-credentials)

---

## Step 1: Create a Firebase Project

1. **Go to Firebase Console:**
   - Open your browser and navigate to the [Firebase Console](https://console.firebase.google.com/).

2. **Create New Project:**
   - Click on **Go to Console** (top-right corner).
   - Then click **Get Started with a Firebase Project**.

3. **Enter Project Name:**
   - Enter a unique name for your project, e.g., `Music App`.

4. **Finalize Project Creation:**
   - A unique project identifier will be automatically generated.
   - Click **Continue** through the prompts and then click **Create Project**.
   - Wait a few seconds while Firebase creates your project.

5. **Open Dashboard:**
   - Once the project is created, click **Continue** to open your Firebase project dashboard.

---

## Step 2: Set Up Build Features

Now, let’s configure Authentication, Firestore, and Realtime Database.

### Step 2.1: Authentication Setup

1. **Go to Authentication:**
   - From the left-hand menu, click on **Authentication** under the **Build** section.

2. **Enable Email/Password Sign-in:**
   - Click **Get Started**.
   - Under the **Sign-in method** tab, select **Email/Password**.
   - Enable **Email/Password** and click **Save**.

3. **Authentication is Now Configured**.

### Step 2.2: Firestore Database Setup

1. **Go to Firestore Database:**
   - From the left-hand menu, select **Firestore Database** under **Build**.

2. **Create Database:**
   - Click **Create Database**.
   - Choose the default location for your database and click **Next**.
   - Select **Start in test mode** and click **Enable**.

3. **Firestore Database is Now Configured**.

### Step 2.3: Realtime Database Setup

1. **Go to Realtime Database:**
   - Select **Realtime Database** from the **Build** section on the left.

2. **Create Database:**
   - Click **Create Database**.
   - Choose the default location and click **Next**.
   - Select **Start in test mode** and click **Enable**.

3. **Realtime Database is Now Configured**.

---

## Step 3: Register Your App

1. **Go to Project Settings:**
   - Click the **Settings** icon next to **Project Overview** in the Firebase Console.

2. **Navigate to "Your Apps" Section:**
   - Scroll down to the **Your Apps** section.

3. **Register Web App:**
   - Click the **Code icon (</>)** to register a new **Web app**.
   - Enter an **App nickname** of your choice.
   - Click **Register app**.

4. **Skip Firebase SDK Setup:**
   - Skip the **Firebase SDK setup** for now (since this guide is for backend integration).
   - Click **Continue to Console**.

   Your Firebase app is now registered.

---

## Step 4: Generate Firebase Admin SDK Credentials

1. **Go to Service Accounts:**
   - In **Project Settings**, navigate to the **Service Accounts** tab.

2. **Choose Backend Language (Python):**
   - Choose **Python** as your backend language.

3. **Generate New Private Key:**
   - Click **Generate new private key**.
   - Confirm by clicking **Generate Key**.

4. **Download the Credentials File:**
   - A **.json** file will be downloaded to your local machine.
   - **Store this file securely** as it contains sensitive credentials.

   > **Important:** Do **not** share this file with anyone.

---

## Conclusion

You have successfully set up your Firebase project with Authentication, Firestore, and Realtime Database! Now you're ready to integrate these services into your backend code using the Firebase Admin SDK.

---

### Next Steps:

- Install the Firebase Admin SDK for Python.
- Start integrating Firebase services into your backend code.

---
