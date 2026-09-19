Veily — Advanced Device Environment & Privacy Manager

Veily is a professional-grade device environment and privacy management utility for rooted Android, built on the Xposed/LSPosed framework. It gives you precise, per-application control over how device hardware, system, network, telephony, and regional identifiers are presented to any installed app.

---

Device & System Hooks

- Android ID
- App Set ID
- Advertising ID
- GSF ID
- Media DRM ID
- Boot ID
- Anonymous App ID (AAID)
- Device Model
- Manufacturer
- Brand
- OS Version
- Build Information
- Build Fingerprint
- Hardware Information
- Board Information
- Display Information
- Hardware Serial
- Developer Options / Developer State

---

Telephony & SIM Hooks

- IMEI
- IMSI
- MEID
- SIM Serial / ICCID
- Subscriber ID
- Phone Number
- Voicemail Number
- SIM Country
- SIM Operator
- MCC / MNC
- Carrier Network
- Country ISO / Region
- International Dialing Code

---

Wi-Fi & Connectivity Hooks

- Wi-Fi MAC Address
- BSSID
- SSID
- Bluetooth MAC Address
- Carrier and Network Information

---

Country Profiles

Apply a complete regional environment through one profile:

- Country & Region
- Timezone
- Currency & Currency Symbol
- SIM Country
- MCC / MNC
- International Dialing Code
- Locale & Language
- Date Format
- Related country-specific settings

---

Location

- Custom latitude and longitude
- Country/region-based location configuration
- Interactive map with pan and zoom
- Apply individually or through App Groups

---

Multi-Profile System

Create multiple independent profiles per application — each with its own device environment, country settings, location, and rules — and switch between them instantly.

---

App Groups & Batch Management

Organize multiple applications into groups and apply the following in one tap:

- Device profiles
- Country profiles
- GPS coordinates
- Configuration rules

Groups can be exported and restored as a single ".veily" archive.

---

App Backup & Restore

A ".veily" backup can include:

- Device profile
- App data
- Internal CE data
- Device-protected / DE storage
- External "/sdcard/Android/data"
- Runtime permissions

Runtime permissions are automatically restored when included in the backup.

Additional controls: Force Stop, Clear App Data.

---

Anti-Fingerprinting

Veily covers 50+ device and environment signals to help prevent device fingerprinting and hardware profiling by target applications. All spoofed values are internally consistent across related hardware, system, and build properties to avoid cross-signal contradictions.

---

Privacy & Detection Controls

- Xposed Concealment — Hides installed Xposed/LSPosed modules from target applications.
- Hide Root Detection — Suppresses root-related indicators from target app visibility.
- Hide Developer Options — Hides developer state and related checks from target applications.
- Installation Source Spoofing — Reports Google Play Store as the install source to target applications.

---

Device Presets

800+ authentic device presets with genuine specifications, hardware info, board details, display properties, and certified build fingerprints across a wide range of manufacturers and models.

---

Randomization Engine

Generates randomized device environments while maintaining property consistency — designed to prevent mismatched combinations between related device attributes.

---

RAM & Storage Emulation

- Total RAM
- Available RAM
- Total Internal Storage
- Available Internal Storage

---

Per-App Control

Every target application maintains its own independent:

- Device environment
- Country profile
- Location
- Hooks
- Detection controls
- Backup configuration
- Profile settings

---

Interface

Modern dark-themed UI built on the Cosmic Noir design system.

---

Privacy & Data

All configurations, profiles, and rules are stored locally on your device. Veily does not upload, sync, or transmit any configuration data to external servers.

Note: Back up your data regularly using the ".veily" export. Uninstalling Veily or clearing its app data will permanently delete locally stored profiles and settings.

---

Access

Veily is a paid application. A trial period is available before purchase.

---

Requirements

- Rooted Android device
- Magisk or KernelSU , Apatch
- LSPosed

---

Installation

1. Install the Veily APK.
2. Set up Magisk or KernelSU.
3. Install and activate LSPosed.
4. Enable Veily within LSPosed.
5. Add target applications to Veily's LSPosed scope.
6. Open Veily and configure profiles, hooks, and rules.

---

Support

- Telegram Support: @veilysupport
- Info Bot: @veilyinfo_bot
- Channel: [@veily_app](https://t.me/veily_app)
