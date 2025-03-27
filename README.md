# Quick Response

## Overview
The **Emergency Service App** is a Flutter-based mobile application designed to provide rapid assistance during emergencies. It consists of two separate apps:
1. **User App** – Allows users to request emergency services.
2. **Service Provider App** – Enables responders to receive and manage emergency requests.

## Features
### User App
- 📍 **Real-time Location Sharing** – Uses Google Maps API to pinpoint user locations.
- 🚨 **Emergency Request** – Users can request help with a single tap.
- 📡 **Live Tracking** – Track responders in real-time.


### Service Provider App
- 🚑 **Receive Emergency Requests** – View user requests and navigate to their locations.
- ✅ **Request Management** – Accept, decline, or mark requests as resolved.


## Tech Stack
- **Flutter** – Cross-platform mobile development.
- **Firebase** – Authentication, Firestore for data storage, and Cloud Messaging for notifications.
- **Google Maps API** – Real-time location tracking and navigation.


## Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/dev778g-me/Rapid-Response.git
   
   ```
2. **Setup Firebase**
   - Create a Firebase project and configure Firestore.
   - Add `google-services.json` (Android) and `GoogleService-Info.plist` (iOS).
3. **Enable Maps API**
   - Go to Google Cloud Console and enable **Maps SDK for Android/iOS**.
   - Add API key to `AndroidManifest.xml` and `Info.plist`.
4. **Install Dependencies**
   ```bash
   flutter pub get
   ```
5. **Run the App**
   ```bash
   flutter run
   ```

## Contributing
Feel free to fork and contribute by submitting a pull request.

## License
This project is licensed under the MIT License.

