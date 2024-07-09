# 🌊 Word Wave

## 📜 Description

Word Wave is an Android-based chatting application developed using Java and XML in Android Studio. It leverages Firebase for database management and ZegoCloud for audio and video calling functionality.

## 📋 Details of Word Wave

### 🔒 Authentication System

- **Individual Accounts:** Each user has a unique account.
- **Sign Up Options:** Users can sign up using Google, phone number, or email and password.
  - **Profile Information:** During account creation, users must set a profile photo, username, fullname, email, and phone number.
- **Sign In:** Users must sign in to use the functionalities of Word Wave.
  - **Phone Number:** Users can sign up using a specific phone number and can sign in using that number only.
  - **OTP:** For sign-in/sign-up using phone number, an OTP is required.
  - **🔑 Forgot Password:** For email-password sign-up, a password reset link is sent to the entered email if the user forgets their password.

### 🏠 Main Activity

After authentication, users are directed to the main activity, which contains three fragments:

1. **👤 Profile Fragment**
   - Displays account details like profile photo, fullname, username, email, etc.
   - Provides options to log out and edit profile.

2. **💬 Chat Fragment**
   - Lists persons with whom the user has messaged.
   - Each list item shows the user's profile photo, username, fullname, and icons for audio and video calls.
   - Tapping on a user's photo opens a dialog box with options to chat or view the user's information.
   - Tapping on a list item directs to the chat activity with that user.

3. **📸 Photo Status Fragment**
   - Users can set their status (only photos, not videos).
   - Displays the status updates of users from the chat fragment list.
   - Each status list shows the status and time of update.
   - Clicking on a status shows it in full screen for 4 seconds.

### 🔍 Search User

- Allows users to search for any user and initiate a chat.
- Search results display all users who have created accounts in Word Wave.

### 🗨️ Individual Chat

- Users can chat individually with any user from the chat fragment list or search results.
- The chat fragment only shows users with whom the user has previously chatted, while the search bar shows all users.
- The chat screen displays:
  - Profile photo of the user
  - Username
  - User status (online or last seen)
  - Audio and video calling buttons
  - Previous message list with timestamps
- Users can send messages, view user info, and make audio/video calls.

### 📇 User Info Activity

- Displays the user's fullname, username, profile photo, phone number, email, etc.
- Provides options to make audio/video calls and share the user's account info via various platforms.

### 📌 Additional Information

1. **Firebase Functionalities Used:**
   - Realtime Database
   - Firestore
   - Storage
   - Authentication
2. **ZegoCloud:** Implemented for audio and video calling functionality.
3. **🕒 Message History:** Users can see all previous chats upon logging in.
4. **🔑 Unique Username:** Each account has a unique username.
5. **🗑️ Message Deletion:** Users can delete messages for themselves or for everyone.

## 📂 Repository

- [Word Wave Repository](https://github.com/YourUsername/WordWave)

Feel free to explore the project and don't hesitate to reach out with any questions or feedback!
