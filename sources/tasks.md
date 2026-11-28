# Carina Tasks — Privacy Policy

_Effective November 28, 2026 · App: Carina Tasks (com.carina.tasks) · Developer: Carina Apps_

Carina Tasks is a to-do list and reminder app. It works on your phone, and optionally on a computer, without a Carina account.

## The short version

**Carina Tasks does not collect, store on a server, share, or sell any personal data.** There are no Carina accounts, no ads, no analytics and no tracking. Carina Apps has no servers and cannot read your tasks.

Your tasks stay on your device unless you turn on **Sync**, which is optional, off by default, and available with Carina Pro. If you turn it on, the app first encrypts your tasks on the device with a passphrase only you know, then saves that encrypted copy to a place you choose: a hidden folder in your own Google Drive, or a file you pick. Internet is used by Google Play for the optional Pro purchase and, if Sync is on and you chose Google Drive, to upload and download that encrypted file.

## What stays on your device

- **Your tasks, notes, checklists, lists, board columns, due dates, reminders and settings** (theme, accent, week start, default reminder time) are stored locally in the app's private storage on your device (or, for the desktop app, in its data folder on your computer).
- Unless you turn on Sync, this data never leaves your device through the app. The app doesn't send it to Carina Apps or anyone else.
- **Backup export and import** happen only when you choose them. You pick where the JSON file is saved (or which file to read) with the system file picker. Carina Apps never sees those files. Where they go afterwards (for example a cloud drive you chose) is up to you and that service.
- If you use Android's own device backup, Android may include the app's local data in your personal backup under your Google account settings. Sync settings, including your passphrase, are left out of that backup. Carina Apps has no access to the backup.
- Uninstalling the app, or clearing its storage, deletes the copy on that device.

## Optional Pro purchase (Google Play Billing)

Carina Tasks is free to use. An optional one-time Carina Pro upgrade is sold through Google Play. When you buy or restore Pro, **Google Play Billing** handles the purchase: Google processes the payment and keeps your payment details and purchase record under the [Google Privacy Policy](https://policies.google.com/privacy). The app only asks Google Play whether Pro has been bought, and saves a yes/no on your device so Pro keeps working offline.

Google Play Billing is why the Android app has the Internet permission even when Sync is off. Carina Apps never receives your card or payment details. Google Play gives us the standard order record for a sale (such as the order number, date, price and country), as it does for every Play purchase.

## Sync (optional, Carina Pro)

Sync is off by default. If you have Carina Pro, you can turn it on in Settings to keep tasks in sync between the Android app and Carina Tasks for desktop. This policy covers both. Carina Apps has no servers and never sees your tasks.

**What is synced.** Your lists, board columns, and tasks, including titles, notes, due dates and times, reminders, priority, repeat rules, completion, and checklists. Appearance settings such as theme and accent stay on each device and are not synced. Your passphrase stays on each device; it is never uploaded.

**How it is encrypted.** Before anything is saved off the device, the app encrypts it on the device with AES-256-GCM. The encryption key is derived from a passphrase only you choose. Without that passphrase, the synced copy cannot be read. Carina Apps cannot decrypt it. If you forget the passphrase, the synced copy cannot be unlocked; your tasks still remain on each device until you delete them there.

**Where it goes.** You choose one of two places:

- **Your own Google Drive.** The encrypted file is saved in a hidden app folder in your Google account that only Carina Tasks can see. The app asks Google only for the `drive.appdata` scope: it can create, read, update and delete its own configuration data in that hidden folder. It cannot see, read or change any of your other Drive files. Sign-in is handled by Google under the [Google Privacy Policy](https://policies.google.com/privacy). Carina Apps does not get a Carina account and does not receive your Google password.
- **A file or folder you pick.** For example a file in a folder that Google Drive for desktop, Dropbox or another service already keeps in sync. The app writes the same encrypted file to the location you choose. What happens to that file afterwards is covered by that service's policy.

**How to turn Sync off and delete the synced copy.**

- Turn Sync off in Settings. The app will stop uploading.
- Your tasks remain on each device until you delete them there, clear the app's storage, or uninstall the app.
- If you used Google Drive: in Drive, go to Settings → Manage apps → Carina Tasks → Delete hidden app data. You can also revoke the app's access in your Google Account under Security → Third-party access.
- If you used a file you picked: delete that file in the folder you chose.

## Permissions

- **Internet:** added by Google Play Billing, used to process and check the optional Pro purchase. If you turn on Google Drive sync, the app also uses it to upload and download the encrypted sync file in your Drive.
- **Notifications:** to show the reminders you set. You can turn them off at any time in Android settings.
- **Alarms & reminders (exact alarms):** optional. It lets reminders arrive at the exact minute. Without it, reminders can arrive up to about 10 minutes late.
- **Run at startup:** so your reminders are set again after the phone restarts.

The app does not access your contacts, location, camera, calendar, files (other than a backup or sync file you pick) or any other app's data.

## Children

The app collects no data from anyone, including children.

## Changes

If this policy changes, the updated version will be published at this address with a new effective date.

## Contact

Questions: austin@younggraphix.com
