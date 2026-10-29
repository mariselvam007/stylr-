# CutConnect - Smart Salon Booking App ✂️

A professional, real-time salon booking application built with Flutter and Firebase.

## Features 🚀

### For Customers 💇‍♂️
- **Authentication**: Secure login/registration.
- **Location-Based Search**: Find nearest salons sorted by distance.
- **Real-Time Booking**: View available slots and book appointments.
- **Service Selection**: Choose from various services (Haircut, Facial, etc.).
- **Live Chat**: Chat with barbers for queries.
- **Reviews**: Rate and review barbers after service.
- **Booking History**: Track past and upcoming appointments.

### For Barbers 💈
- **Shop Management**: Toggle Shop Open/Closed status.
- **Booking Dashboard**: Accept/Reject booking requests.
- **Earnings Insight**: View daily/weekly earnings.
- **Service Management**: (Configurable via Firestore).

## Tech Stack 🛠️
- **Frontend**: Flutter (Riverpod, Material 3)
- **Backend**: Firebase (Auth, Firestore, Storage)
- **Maps/Location**: Geolocator, URL Launcher
- **Charts**: FL Chart

## Setup Instructions 📱

1.  **Firebase Configuration**:
    -   Create a project in [Firebase Console](https://console.firebase.google.com/).
    -   Enable **Authentication** (Email/Password).
    -   Enable **Firestore Database**.
    -   Run `flutterfire configure` in your terminal to generate `firebase_options.dart`.
    -   Uncomment the Firebase initialization code in `lib/main.dart`:
        ```dart
        // await Firebase.initializeApp(
        //   options: DefaultFirebaseOptions.currentPlatform,
        // );
        ```

2.  **Dependencies**:
    ```bash
    flutter pub get
    ```

3.  **Run the App**:
    ```bash
    flutter run
    ```

## Folder Structure 📂
- `lib/models`: Data models (User, Service, Booking).
- `lib/screens`: UI Screens for Auth, Customer, and Barber.
- `lib/services`: Firebase and Logic services.
- `lib/providers`: Riverpod state management.
- `lib/widgets`: Reusable UI components.
- `lib/themes`: App theming and colors.

## License
MIT
