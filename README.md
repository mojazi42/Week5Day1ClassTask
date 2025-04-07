# Firebase Notifications & Analytics App (Kotlin)

This Android project demonstrates the integration of **Firebase Cloud Messaging (FCM)** and **Firebase Analytics** using **Kotlin + Jetpack Compose**. The app receives push notifications, logs key user interactions, and tracks custom analytics events in real-time.

---

## Features Implemented

### Firebase Cloud Messaging (Notifications) 
- Integrated **Firebase Cloud Messaging** into the Android project.
- Automatically **fetches and logs FCM token** on app startup.
- Used **Firebase Console** to send test notifications.
- Displays incoming notifications with **custom titles and body** using `NotificationCompat`.
- Supports notification tap actions and token updates.

### Firebase Analytics Integration 
- Integrated **Firebase Analytics** with the project.
- Tracked key events:
  - `app_open`: when the app launches
  - `notification_received`: when an FCM message is received
  - `notification_opened`: when a user taps on a notification
- Logged custom events like:
  - `button_tapped`: when the Greeting button is clicked
- Verified event tracking using **Firebase DebugView**.

---

## How to Run the Project

1. **Clone the repo**:
   ```bash
   https://github.com/mojazi42/Week5Day1ClassTask
   ```
   
![Screenshot (835)](https://github.com/user-attachments/assets/a01757ee-bf49-4fc8-a39e-6a9e071bbef6)
![Screenshot_20250407-184659_Settings](https://github.com/user-attachments/assets/73bf5005-5d6d-4f0d-935f-09caa1274b16)
