# Carina Weather — Privacy Policy

_Effective November 24, 2026 · Carina Apps_

Carina Weather is a simple weather forecast app. It has no ads, no analytics, no tracking and no account.

## The short version

**Carina Apps does not collect, receive, store, share or sell any personal data.** To show a forecast, the app asks the free weather service **Open-Meteo** for the forecast at a place's coordinates. That request is the only thing that leaves your phone.

## What is sent to Open-Meteo, and when

Forecasts and city search come from [Open-Meteo](https://open-meteo.com/) (OpenMeteo GmbH, Switzerland). The app connects directly to Open-Meteo; nothing passes through a Carina Apps server (there isn't one).

| When | What is sent |
|---|---|
| You search for a city | The text you type (e.g. "Denver") and your phone's language, to Open-Meteo's geocoding service, to list matching places. |
| The app loads a forecast for a saved city | That city's latitude and longitude, rounded to 2 decimal places (about 1 km). |
| You use **My location** | Your **approximate (coarse) location**, rounded to 2 decimal places (about 1 km), to get the forecast for where you are. |
| A home-screen widget refreshes (about every 2 hours, only if you've added a widget) | The coordinates of the place shown in the widget, as above. Widgets never read your location in the background; they reuse the last place the app saw. |

As with any internet request, Open-Meteo also receives your device's IP address. According to Open-Meteo's own privacy notice, it does not link this to your identity, uses it only for technical reasons such as preventing misuse, and deletes its server logs (which may contain the requested coordinates) after 90 days. See <https://open-meteo.com/en/terms>.

No account, name, email, device ID, advertising ID or other identifier is ever sent.

## Location permission

- Carina Weather only asks for **approximate location** (Android's "coarse" location, about 1–3 km). It never asks for precise or background location.
- It asks only when you tap **Use my location**, and reads your location only while the app is open on screen.
- Location is optional. If you say no, everything else works: search for cities instead.
- You can turn location off at any time in Android Settings › Apps › Carina Weather › Permissions.

## What stays on your device

- Your saved places (city names and coordinates), the last downloaded forecast for each place (so it can be shown offline), and your settings (units, theme, accent).
- This data is stored in the app's private storage. Carina Apps cannot see it.
- If you use Android's own device backup, Android may include this data in your personal backup under your Google account. Carina Apps has no access to that backup.
- Uninstalling the app, or clearing its storage, deletes this data. Removing a place deletes its saved forecast.

## Permissions and why they're used

| Permission | Why |
|---|---|
| Internet | Download forecasts and city search results from Open-Meteo. |
| Network state | Lets widget refreshes wait until you're online. |
| Approximate location (optional) | Forecast for where you are, only when you tap "Use my location" and only while the app is open. |
| Run at startup / keep awake (added by Android's WorkManager library) | Keeps the widget refresh schedule after a reboot and lets a refresh finish. No data is collected. |

## Children

The app collects no personal data from anyone, including children.

## Weather data credit

Weather data by Open-Meteo.com, licensed under CC BY 4.0. City search uses GeoNames data (CC BY 4.0) via Open-Meteo. Forecasts are provided as-is and may be inaccurate; don't rely on the app for safety-critical decisions.

## Changes

If this policy changes, the updated version will be published at this address with a new effective date.

## Contact

Questions: austin@younggraphix.com
