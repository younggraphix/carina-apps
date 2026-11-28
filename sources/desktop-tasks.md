# Carina Tasks for desktop

*Version 1.2.0 · Windows, Linux, and any computer with Java 21 · Carina Apps*

Carina Tasks for desktop works with the Android app. You can add, edit, complete and delete tasks, with due dates, priorities and checklists. Optional Sync (a Carina Pro feature, off by default) keeps the two in step through your own Google Drive. Your tasks are encrypted on the device with a passphrase only you know, then saved to a hidden folder in your Drive. Carina Apps has no servers and never sees them.

## Download

- **[Windows, portable zip](https://github.com/younggraphix/carina-apps/releases/download/v1.2.0-desktop/CarinaTasks-1.2.0-windows-x64-portable.zip)** (about 114 MB). Unzip it anywhere, for example into Documents, and double-click `CarinaTasks.exe`. No installer and no admin rights are needed. Your tasks are stored in `%APPDATA%\CarinaTasks`.
- **[Linux, .deb](https://github.com/younggraphix/carina-apps/releases/download/v1.2.0-desktop/carina-tasks_1.2.0_amd64.deb)** (about 95 MB). For Debian 13 or Ubuntu 24.04 and newer. Then run: `sudo apt install ./carina-tasks_1.2.0_amd64.deb`
- **[Java jar](https://github.com/younggraphix/carina-apps/releases/download/v1.2.0-desktop/CarinaTasks-1.2.0-all.jar)** (about 122 MB). On any computer with Java 21: `java -jar CarinaTasks-1.2.0-all.jar`

All three files are also on the [v1.2.0-desktop release](https://github.com/younggraphix/carina-apps/releases/tag/v1.2.0-desktop) page. This is a prototype.

## Windows SmartScreen

Windows may show a warning that the app is from an unknown publisher, because this prototype is not code-signed yet. That is expected. Click **More info**, then **Run anyway**.

## Set up sync

1. Install Carina Tasks 1.2.0 or later on your phone, and this desktop app on your computer.
2. On your phone, turn on Carina Pro (in a test build, use the Pro toggle in Settings). Go to **Settings → Sync with desktop**, choose **Google Drive**, connect your Google account, choose a passphrase of 8 or more characters, turn Sync on, and tap **Sync now**.
3. On your computer, open Settings (the gear at the bottom left), choose **Google Drive**, sign in with the same Google account, enter the **same passphrase**, and click **Sync now**.
4. Google may show an "unverified app" warning. Click **Advanced** and continue. That is expected until the brand is verified.

After that, the phone syncs when you open or leave the app, and a few seconds after a change. The desktop app syncs at startup, every two minutes, after changes, and when you close it.

You can also skip Google sign-in and sync through a shared file or folder, for example a folder that Google Drive for desktop already keeps in sync. Choose **Sync file / folder** in Settings on both sides, point them at the same place, and use the same passphrase.

## Privacy

Sync is optional, off by default, and uses only the `drive.appdata` Google scope: the app can see its own hidden folder, not the rest of your Drive. To turn it off, switch Sync off in Settings. To delete the Drive copy, go to Drive → Settings → Manage apps → Carina Tasks → Delete hidden app data. The [privacy policy](https://younggraphix.github.io/carina-apps/privacy/tasks/) has the full details.

Questions: austin@younggraphix.com
