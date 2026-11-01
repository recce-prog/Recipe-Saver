MacroCraft Android - Recipe Studio & Macro Saver 🍳

A modern, mobile-native Android web application to build, customize, scale, and save your recipes with YAZIO-style macro ingredient calculations.

Option 1: Quick Install on Phone (PWA via GitHub Pages)

This is the easiest way to install and use the app on your Android phone without needing Android Studio.

Upload to GitHub:

Create a repository on GitHub (e.g. macrocraft-recipes).

Upload index.html and manifest.json.

Enable GitHub Pages:

Go to your repository Settings -> Pages.

Under Branch, select main (or master) and /root, then click Save.

Install on Phone:

Open your GitHub Pages link in Chrome on your Android device.

Tap the 3 dots (Menu) in the top right -> select "Add to Home Screen" or "Install app".

MacroCraft will now launch like a full native app directly from your app drawer!

Option 2: Build Native .apk for Android (Capacitor & Android Studio)

If you want a true offline .apk file to install on your phone:

Prerequisites:

Node.js installed on your computer.

Android Studio installed.

Build Steps:

# 1. Install dependencies
npm install

# 2. Build web bundle & initialize Capacitor
npm run cap:add-android

# 3. Sync changes & open Android Studio
npm run cap:open-android


In Android Studio:

Go to Build -> Build Bundle(s) / APK(s) -> Build APK(s).

Transfer the generated .apk file to your Android phone and tap to install!

Features

Android Native UX: Clean sticky headers, bottom navigation, and quick mobile sheets.

YAZIO-Style Gram Scaler: Real-time per-100g macro adjustments for ingredients.

Random Recipe Selector (Dice): Spin to get a random breakfast, lunch, or dinner plan.

5 Custom White Themes & Card Sizes: Switch between color themes and card density views.

100% Offline & Private: All data is saved safely in your device's localStorage.
