# 🌊 Word Wave

## 📜 Description

Welcome to Word Wave! This is an Android-based chatting application developed using Java and XML in Android Studio, with Firebase handling the database management and ZegoCloud enabling audio and video calling functionality.

## 🛠️ Development Tools

Developed using:
- 📱 Android Studio
- ☕ Java
- 🖌️ XML
- 💾 Firebase
-    ![Audio/Video Call Icon](https://example.com/audio-video-icon.png)
ZegoCloud

## 🚀 Features

### 📋 Details of Word Wave

- **Authentication:**
  - **Sign Up:** Users can register using Google, email-password, or phone number with OTP.
  - **Sign In:** Secure sign-in process required for app access.
  - **Google Sign-In:** Integration with Google accounts for easy access.
  - **Email-Password:** Standard email and password registration.
  - **Phone Number with OTP:** Register and sign in using phone numbers with OTP verification.
  - **Forget Password:** Email-password users receive a reset link for forgotten passwords.

### 🔒 Authentication System

- **Individual Accounts:** Each user has a distinct account.
- **Sign Up Options:** Users can register using Google, phone number, or email and password.
  - **Profile Setup:** Requires profile photo, username, fullname, email, and phone number.
- **Sign In:** Necessary to access app functionalities.
  - **OTP Verification:** For phone number sign-up/sign-in.
  - **🔑 Forgot Password:** Email-password users receive a reset link.

### 🏠 Main Activity

Upon authentication, users access the main activity with three key fragments:

1. **👤 Profile Fragment**
   - Shows account details: profile photo, fullname, username, email, etc.
   - Options to log out and edit profile.

2. **💬 Chat Fragment**
   - Displays a list of contacts.
   - Each contact shows a profile photo, username, fullname, and icons for audio and video calls.
   - Clicking a contact opens a dialog box for chat or user info.
   - Clicking a list item navigates to the chat activity.

3. **📸 Photo Status Fragment**
   - Users can set and view photo statuses.
   - Displays statuses of contacts from the chat fragment list.
   - Viewing a status shows it full screen for 4 seconds.

### 🔍 Search User

- Search for users to initiate chat.
- Displays all users registered in Word Wave.

### 🗨️ Individual Chat

- Chat individually with contacts from the chat list or search results.
- The chat fragment only shows users with whom the user has previously chatted, while the search bar shows all users.
- The chat screen includes:
  - User's profile photo, username, and online status.
  - Audio and video calling buttons.
  - Previous messages with timestamps.
  - Options to view user info and make calls.

### 📇 User Info Activity

- Displays user's fullname, username, profile photo, phone number, email, etc.
- Options for audio/video calls and sharing user info via other platforms.

### 📌 Additional Information

1. **Firebase Services Used:**
   - Realtime Database
   - Firestore
   - Storage
   - Authentication
2. **ZegoCloud:** For audio and video calling functionality.
3. **🕒 Message History:** View all previous chats upon logging in.
4. **🔑 Unique Username:** Ensures each account has a distinct username.
5. **🗑️ Message Deletion:** Delete messages for yourself or for everyone.

## 📸 Screenshots

You can see screenshots of this app in the [screenshots](https://github.com/Raj-Pavara/WordWave/tree/main/screenshots) folder.

## 📦 APK File

You can find and easily download the APK file for this app in the 📁 [APK file](https://github.com/Raj-Pavara/WordWave/tree/main/APK%20file) folder.

## 💡 Feedback

We appreciate your feedback! If you have any suggestions or find any issues, please open an issue or reach out to us.

## 🔗 LinkedIn Profile

You can watch a demo video of the Word Wave app on my LinkedIn profile: [My LinkedIn Profile](https://www.linkedin.com/in/raj-pavara-6b65262aa?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

Feel free to connect with me on LinkedIn for more updates and discussions!

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Raj-Pavara/WordWave.git
