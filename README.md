# Study with Abhi Pro — editable source

This is a clean Android source starter for the rebuilt app. The app uses a Kotlin/Jetpack Compose wrapper and the editable interface lives in:

- `app/src/main/assets/grown.html` — the start page
- `app/src/main/assets/grow.html` — a matching alternate page
- `app/src/main/java/com/techabhi/studyproapp/MainActivity.kt` — the Android WebView wrapper

## Using it with Google AI Studio

1. In Google AI Studio, open **Build** and choose **Android**.
2. Use the contents of `AI_STUDIO_PROMPT.txt` as your first prompt.
3. In the generated project's Code view, replace its `MainActivity.kt` and add the two HTML files under `app/src/main/assets/`.
4. Ask AI Studio to make design or feature changes. For example: “Change the home page colors to blue and add a Search Institutes field. Do not add a payment system.”

The original APK was not a source project; it was a WebView app containing HTML and Firebase-hosted institute data. This folder is the maintainable source-style version for future edits.
