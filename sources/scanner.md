# Carina Scanner — Privacy Policy

_Last updated: November 24, 2026_

Carina Scanner is published by **Carina Apps**. This policy explains how the app handles your information.

## The short version

**Your scans never leave your phone through Carina Scanner.** We don't run servers, we don't have accounts, and we don't show ads. The scanner and text recognition are Google ML Kit features provided by Google Play services; they process your pages on the device. Like other Google Play services features, ML Kit sends Google limited technical diagnostics (described below), never your documents.

## What the app stores, and where

- Scanned pages (JPEG), the PDFs built from them, recognized text, document names and your settings are saved **only on your device**, in the app's private storage.
- There are **no ads, no analytics, no crash reporting, no watermark and no account** from Carina Apps.
- Carina Apps never receives your scans, your text or anything about you.

## Google ML Kit and Google Play services

Carina Scanner uses two Google ML Kit features that run inside Google Play services on your phone:

- **Document scanner** — the camera screen, edge detection, cropping and filters. It runs inside Google Play services, which is why Carina Scanner itself has no camera permission. The finished page images are handed to Carina Scanner on your device.
- **Text recognition** — reads the text on your pages so you can copy it and search for it. Recognition happens **on the device**; page images are not uploaded. You can turn automatic recognition off in Settings.

Google Play services downloads the models these features need, and may update them. According to Google's ML Kit documentation, ML Kit also sends Google **diagnostics and usage analytics**: device information (such as manufacturer, model, OS version), the app's package name and version, a device identifier and per-installation identifiers, performance metrics, API configuration (such as image format and resolution), input/output sizes, feature versions, event types and error codes. This data is encrypted in transit and, per Google, is not shared with third parties. It does **not** include your images or the recognized text. Google's handling of this data is covered by the [Google Privacy Policy](https://policies.google.com/privacy). See also [ML Kit's data disclosure](https://developers.google.com/ml-kit/android-data-disclosure).

## Imports, sharing and exports

- **Import photos** uses Android's system photo picker. The app only sees the photos you pick.
- **Share PDF / Share as images** sends a copy to the app you choose in the Android share sheet. After that, that app handles it under its own policy.
- **Save PDF / Save images to folder** writes files to a location you pick (for example Downloads or a cloud drive folder). That location's provider handles the files from then on.

## Backups

If Android device backup is on, only the app's **settings** are included in your Google backup; scans are not (they can be too large). Phone-to-phone transfer may copy everything to your new phone.

## Permissions

Carina Scanner requests **no dangerous permissions** — no camera, storage, location, contacts or microphone permission. The only permissions in the app are INTERNET and ACCESS_NETWORK_STATE (no user prompt), which Google's ML Kit libraries add for model downloads and diagnostics, plus an internal Android permission that keeps the app's own broadcasts private. Carina Scanner's own code makes no network requests.

## Children

The app doesn't collect personal information from anyone, including children.

## Deleting your data

Delete documents in the app, clear the app's storage in Android Settings, or uninstall the app. All scans are removed from your device.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions: austin@younggraphix.com
