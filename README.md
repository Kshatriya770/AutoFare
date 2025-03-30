# AutoRickshaw Fare Estimator

## Overview

The **AutoRickshaw Fare Estimator** is a simple Android app designed to help users estimate shared auto fares between hotspots in metro cities, starting with **Delhi NCR**. The app provides accurate fare calculations based on predefined routes and hotspots.

## Features

- **Fare Estimation**: Users can enter their starting and destination points to get an estimated fare.
- **Hotspot-Based Routing**: The app calculates fares based on predefined shared auto hotspots.
- **Nearest Hotspot Detection**: Uses GPS to find the nearest auto hotspot.
- **No Login Required**: Simple and easy to use without any signup or login process.
- **Google Maps Integration**: Displays nearby auto hotspots on a map.
- **Crowdsourced Fare Data (Future Update)**: Users will be able to contribute fare details to improve accuracy.

## Tech Stack

- **Language**: Kotlin
- **UI Framework**: ConstraintLayout
- **Maps API**: Google Maps SDK for Android
- **Platform**: Android

## Installation

### 1. Clone the Repository

```sh
git clone https://github.com/Kshatriya770/AutoFare
cd autofare
```

### 2. Open in Android Studio

- Open **Android Studio**
- Select **Open an Existing Project**
- Navigate to the cloned repository folder
- Wait for dependencies to sync

### 3. Set Up Google Maps API Key

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Enable **"Maps SDK for Android"**
3. Generate an **API Key**
4. Add the following to your `AndroidManifest.xml` inside `<application>`:
   ```xml
   <meta-data
       android:name="com.google.android.geo.API_KEY"
       android:value="YOUR_API_KEY_HERE" />
   ```
   Replace `YOUR_API_KEY_HERE` with your actual API key.

### 4. Run the App

- Connect an Android device or launch an emulator
- Click **Run (▶) Button** in Android Studio
- The app should open with input fields and a map showing nearby hotspots

## Future Enhancements

- **User-Contributed Fare Updates**
- **Multi-City Support** beyond Delhi NCR
- **Offline Mode** for fare estimations

## License

This project is open-source under the **MIT License**.

---

### 🔥 Need Help?

Feel free to raise an issue or contribute to the project!

