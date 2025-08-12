Bike Mileage — Lean Expo RN Project
===================================
Quick setup (Windows):

1) Double-click build-apk.bat
   - If you're not logged in to Expo, it will prompt you to login (one time).
   - It will install dependencies and start an EAS APK build.

2) At the end, EAS prints a URL.
   Open it to download the .apk.

Manual steps (if you prefer CLI):
  npm install
  npm install -g eas-cli
  eas build:configure
  eas build -p android --profile preview

App usage:
  - Open Bike Mileage, go to Settings:
      Petrol Price (₹/L) and Bike Mileage (km/L)
  - Then Add Refill: enter amount paid (₹). The app calculates km and adds to total.
