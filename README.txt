FUTURECARE PLAY STORE / PWA PACKAGE

Source portal: FutureCare_SUPPORT_AGENT_RECEIVE_FIXED.html

This package preserves the selected working HTML as a separate copy and adds:
- PWA manifest
- service worker
- Android-friendly app icons

NEXT STEPS:
1. Host this folder on a public HTTPS website (GitHub Pages is one option).
2. Open the HTTPS address and verify Owner/Agent/Member login.
3. Use PWABuilder to package the PWA for Google Play / Android.
4. Build/sign the Android App Bundle (AAB) and submit it through Google Play Console.

IMPORTANT:
- Do not expose any Supabase service-role/secret key in the browser.
- The included portal uses the existing Supabase configuration from the source HTML.
- Google Play new apps currently need Android 16 / API 36 or higher for submission as of Aug 31, 2026.
