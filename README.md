# HaziriPro MVP (Flutter + Firebase)

Features included:
- Mobile OTP login using Firebase Auth
- Data saved per logged-in user in Firestore
- Add multiple sites
- Add workers per site with salary and designation
- Monthly attendance calendar: Present, Absent, Half Day
- Salary summary based on attendance
- Logout keeps data safe in the same mobile account

## Setup
1. Install Flutter and Android Studio.
2. Create Firebase project.
3. Enable Authentication > Phone.
4. Create Firestore Database.
5. Run:
   ```bash
   dart pub global activate flutterfire_cli
   flutterfire configure
   flutter pub get
   flutter run
   ```

## Build APK
```bash
flutter build apk --release
```
APK location:
```text
build/app/outputs/flutter-apk/app-release.apk
```
