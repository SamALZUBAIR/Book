# booksmk Android

Native Android project (Java + Android SDK), Arabic RTL intent, black/gold theme, local SQLite catalog, document picker, Android PdfRenderer, EPUB first-content extraction, and JSON backup export scaffold.

## Build
Open this repository in Android Studio with Android SDK 35 and JDK 17, then run `:app:assembleDebug`.

## Important status
This source is an initial native implementation, not a verified release. It requires compilation and device tests. EPUB support currently renders the first HTML/XHTML entry rather than a full EPUB spine/navigation implementation. Backup restore and PDF/EPUB regression tests remain to be completed. No network permission is declared.
