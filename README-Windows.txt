# ONLY US — Windows 11 browser prototype

This is a separate browser-test version. It does not replace the SwiftUI iOS starter.

## Quick start (no install required)
1. Unzip `ONLY_US_Windows.zip`.
2. Open the `ONLY_US_Windows` folder.
3. Double-click `index.html`. It opens in Edge or Chrome.
4. Use the five navigation sections. Add records, choose whether they are shared or private, edit and delete records. Data is saved in this browser on this PC.

## Recommended local-server mode (for offline PWA caching)
If Python 3 is installed:
1. Open the folder in File Explorer.
2. Click the address bar, type `cmd`, press Enter.
3. Run: `py -m http.server 8000`
4. Open `http://localhost:8000` in Edge or Chrome.
5. Use browser menu → Install ONLY US (if offered) to pin it like an app.

If `py` is not recognized, direct opening of `index.html` still works for normal testing. Service-worker offline caching and installability require localhost/HTTPS.

## Included in this prototype
- Responsive desktop/mobile interface, Russian UI, ONLY US branding.
- Five sections: Главная, Мы, Моменты, Планы, Коллекция.
- Catalogue of all 36 agreed functions; expense tracking is excluded.
- Create/edit/delete records, search, local persistence, shared/private visibility labels and two demo profile names.
- Mini interactions for date ideas, couple questions and beginner English.
- Local browser notification permission demo.
- Export records to JSON.
- PWA manifest and service worker for static asset caching when served from localhost.

## Limitations — not yet production features
- Two profiles are a local demonstration, not two authenticated accounts.
- Shared/private labels are not secure server-side access control. Do not put sensitive real information in this demo.
- Data is saved in the current browser profile on this computer; it does not sync with the other person's phone.
- Browser notifications are local permission/demo only, not remote push from the partner.
- No real cloud file storage, live chat, real map geocoding, calendar integration, or WidgetKit system widgets yet.
- Photos and files are represented in the feature catalogue but upload/storage is not yet implemented.
- Offline PWA caching works only from localhost/HTTPS; localStorage still works when index.html is opened directly.

## Visual palette
#E8D8C3 · #856551 · #A68A7B · #DCCCBD · #516B84 · #E6E5E4 · #536878 · #EAE0C8
