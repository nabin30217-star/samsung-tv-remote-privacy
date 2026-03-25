# Privacy Policy for Samsung TV Remote – Wi-Fi & IR

**Effective Date:** January 19, 2026

## 1. Introduction
This Privacy Policy describes how **Samsung TV Remote – Wi-Fi & IR** ("we", "our", or "the App") collects, uses, and discloses your information. We respect your privacy and are committed to protecting it. The App allows you to control Samsung TVs via Wi-Fi and Infrared (IR).

## 2. Information Collection and Permissions

We operate on a **privacy-first** basis. We do not require you to create an account, and we do not collect personal information (such as your name, email, address, or phone number) on our servers.

### 2.1. Local Network Information (Nearby Devices)
*   **Permissions Used**: `android.permission.NEARBY_WIFI_DEVICES`, `ACCESS_WIFI_STATE`, `ACCESS_NETWORK_STATE`, `INTERNET`.
*   **Purpose**: To detect and connect to Samsung TVs on your local Wi-Fi network.
*   **Data Usage**: The App scans for devices on your local network. This communication (IP addresses, MAC addresses of your TV) happens **locally on your device**. This network data is **not** uploaded to our external servers.

### 2.2. Infrared (IR) Blaster
*   **Permissions Used**: `android.permission.TRANSMIT_IR`.
*   **Purpose**: To send control signals using your phone's built-in Infrared hardware (if available).
*   **Data Usage**: No data is collected. This is strictly a hardware interaction.

### 2.3. Voice Commands
*   **Permissions Used**: None (Uses System Intent).
*   **Purpose**: To control the TV using voice commands (e.g., "Volume Up").
*   **Data Usage**: The App uses the built-in Android System Speech Recognizer (Google App). Audio is processed by the Android OS and converted to text. The App receives only the **text command**. We do not record, store, or transmit your voice audio.

### 2.4. Advertising (AdMob)
*   **Permissions Used**: `INTERNET`, `com.google.android.gms.permission.AD_ID`.
*   **Purpose**: To display advertisements to support the free version of the App.
*   **Data Usage**: The App uses **Google AdMob**, a third-party advertising service. AdMob may use device identifiers (Advertising ID), cookies, and other data to serve personalized or non-personalized ads.
*   **Opt-Out**: You can manage your advertising preferences in your Android device settings (Settings > Google > Ads).
*   **Third Party Policy**: For more information, please visit [Google AdMob Privacy & Terms](https://policies.google.com/technologies/ads).

### 2.5. Photos and Videos Access (Media Casting)
*   **Permissions Used**: `android.permission.READ_MEDIA_IMAGES`, `android.permission.READ_MEDIA_VIDEO` (Android 13+), or `READ_EXTERNAL_STORAGE` (older Android versions).
*   **Purpose**: To enable you to browse and cast photos and videos from your device's gallery to your Samsung TV using the DLNA media casting feature.
*   **Data Usage**: The App accesses your photos and videos **only** when you navigate to the "Cast & Mirror" screen and choose to browse your media gallery. When you select a photo or video to cast:
    *   The media file is read from your device's local storage
    *   A temporary local web server is created on your device to stream the media
    *   The media is streamed directly to your Samsung TV over your local Wi-Fi network
    *   **No media files are uploaded to external servers, copied, stored permanently, or shared with third parties**
*   **Frequency of Access**: The App accesses your media library frequently during active use of the casting feature. This is a core functionality that requires ongoing access to display media thumbnails in a grid layout and to stream selected media to your TV.
*   **Data Retention**: Media files are **never** copied, stored, or retained by the App. The local streaming server stops when you exit the Cast screen or close the app. All access is read-only and temporary.
*   **User Control**: You can revoke these permissions at any time through your Android device settings (Settings > Apps > Remote For Samsung > Permissions), though this will disable the media casting functionality.

## 3. Data Retention
Since we do not collect personal user data on our servers, we do not retain your personal information. App preferences (like your saved TV IP address) are stored strictly locally on your device and can be cleared by uninstalling the App or clearing App Data.

## 4. Children’s Privacy
Our App is not directed to children under the age of 13. We do not knowingly collect personal information from children.

## 5. Changes to This Policy
We may update this Privacy Policy from time to time. You are advised to review this page periodically for any changes. Changes are effective immediately after they are posted.

## 6. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at:

**Email**: nabin30217@gmail.com
**Developer Website**: https://nabin30217-star.github.io/samsung-tv-remote-privacy/
