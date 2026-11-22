# RS World Business – Android APK Project

यह Android Studio project है जो RS World Business के मौजूदा HTML app को Android WebView में चलाता है।

## APK बनाने के steps
1. Android Studio में इस folder को Open करें.
2. Gradle Sync पूरा होने दें (internet से Android Gradle Plugin/SDK download हो सकता है).
3. Android SDK Platform 35 install करें अगर prompt आए.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें.
5. APK location: `app/build/outputs/apk/debug/app-debug.apk`

## App
- Offline app assets included.
- Leads, call links, lead status, sales, invoice, expenses, installer records, reports, backup/restore.
- WhatsApp/customer message links Android पर external app में खुलेंगे.
- Print invoice Android print dialog के जरिए.
- Data local app storage/WebView में रखा जाता है. फोन बदलने से पहले Backup JSON export करें.

## Build note
इस environment में Android SDK/Gradle build tools installed नहीं हैं, इसलिए यहां APK compile नहीं किया गया. Android Studio में project open करके APK build किया जा सकता है.
