Your privacy is important to us. This Privacy Policy describes how **Movie Box** (referred to as "the App", "we", "us", or "our") collects, uses, stores, and discloses information when you use our mobile application. 

By downloading, installing, or using Movie Box, you agree to the collection and use of information in accordance with this policy.

---

## 1. Overview of Movie Box
Movie Box is a movie and TV discovery and streaming client shell. 
* We use **The Movie Database (TMDB)** API for movie and TV metadata, descriptions, images, search results, and cast lists.
* Playback of media content is loaded inside an embedded web browser container (WebView) using external links from **vsembed.ru** (based on TMDB IDs).
* Movie and TV show trailers are loaded inside an embedded WebView via **YouTube**.

---

## 2. Information Collected and Stored

### A. Information Stored Locally on Your Device
Movie Box is designed to respect your privacy and operates primarily without requiring a registered user account. The App saves the following data **locally on your device** (in secure local storage) to provide standard streaming functionality:
* **Onboarding State:** Whether you have completed the initial onboarding introduction.
* **Local Library (Favorites):** Movie and TV show listings you have selected to bookmark or save.
* **Recently Viewed:** A history of details pages you have recently visited (up to 24 items).
* **Continue Watching / Watch Progress:** Your playback percentage, current timestamp, and details of titles you are currently watching (up to 20 items).

*This data remains on your physical device and is not uploaded to our own servers.* You can delete this data at any time by clearing the App's cache and data through your Android device settings.

### B. Information Collected Automatically by Third Parties
To display media content, serve advertisements, and handle update notifications, the App integrates several third-party services. These third parties collect information directly from you according to their own privacy policies.

#### 1. Advertising Networks
We use third-party advertisements to fund the development and operations of Movie Box. These networks collect device and advertising identifiers to personalize ads and perform attribution:
* **AppLovin MAX:** AppLovin collects device information (model, OS, screen size), IP address, and advertising identifiers (e.g., Google AD_ID) to serve banners, MRECs, and native/rewarded advertisements.
  * [AppLovin Privacy Policy](https://www.applovin.com/privacy/)
* **Yandex SDK:** Serves interstitial and app-open ads. Yandex collects device information, advertising IDs, location data (if permitted), and network indicators.
  * [Yandex Privacy Policy](https://yandex.com/legal/confidential/)
* **Google Play Services / AdMob:** Automatically integrates with Android device telemetry for ad delivery.
  * [Google Privacy Policy](https://policies.google.com/privacy)

#### 2. Media Providers & Metadata APIs
To search, display, and play media files, the App communicates with the following external endpoints:
* **The Movie Database (TMDB):** The App queries TMDB servers to search and retrieve listings. TMDB receives queries and metadata requests accompanied by standard browser/device headers. TMDB does not receive any personally identifiable information from you.
  * [TMDB Privacy Policy](https://www.themoviedb.org/privacy-policy)
* **vsembed.ru (Streaming WebView Player):** When playing content, a full-screen WebView opens vsembed.ru pages. vsembed.ru may collect standard server logs (IP address, user agent, referrers) and place cookies to operate their player environment.
* **YouTube (WebView Trailer Player):** When viewing trailers, YouTube loads in a WebView dialog. YouTube/Google may collect cookies, browsing activity, or device identifiers under Google's standard privacy guidelines.
  * [Google/YouTube Privacy Policy](https://policies.google.com/privacy)

#### 3. Update Check Host (GitHub)
The App checks for forced software updates by reading a JSON file hosted on GitHub. GitHub may record standard web request logs (including IP addresses and request timestamps) when the App checks for updates.
* [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)

---

## 3. Android System Permissions Used
To function properly, Movie Box requests and uses the following permissions on your Android device:
* **`android.permission.INTERNET`:** Required to fetch movie/TV metadata, load streams in WebViews, play trailers, load advertisements, and check for app updates.
* **`android.permission.ACCESS_NETWORK_STATE` & `android.permission.ACCESS_WIFI_STATE`:** Required to detect network connectivity, switch between online and offline layouts, and queue network operations.
* **`com.google.android.gms.permission.AD_ID`:** Required on Android 12+ device systems to fetch the Google Advertising ID (AD_ID) for showing relevant advertisements.

---

## 4. Data Sharing and Transfer
We do not sell, rent, or trade your personal information. We do not maintain any centralized user accounts, servers, or databases containing your personal data. 

Any data collected automatically via web services (like TMDB, vsembed.ru, and YouTube) or ad libraries (AppLovin MAX and Yandex SDK) is processed directly by those third parties in accordance with their respective privacy policies.

---

## 5. Security of Your Data
Since all of your bookmarks, viewing history, and playback progress are stored locally on your device, the security of this data depends on the security of your device. We recommend securing your device with a PIN, password, or biometric lock.

---

## 6. Children's Privacy
Our services do not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you are a parent or guardian and you are aware that your child has provided third-party services with personal data through our App, please contact those services directly.

---

## 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date at the top. You are advised to review this Privacy Policy periodically for any changes.
