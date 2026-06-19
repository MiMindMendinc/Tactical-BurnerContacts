# Tactical-BurnerContacts

Local-first contact manager PWA prototype with expiry, wipe, and vCard export workflows.

## Technical Summary
- **Storage**: Browser localStorage; data is not encrypted by this app
- **Data controls**: Configurable expiry and a shake-to-wipe shortcut
- **Features**: Search/filter, vCard QR export, JSON backup
- **UI**: Dark tactical theme, vanilla JS for auditability
- **Offline behavior**: The app shell is cached after a successful online load; the QR library currently comes from a CDN

## Impact
Demonstrates privacy-minded browser UX. It is not an audited secure-communications tool and does not guarantee deletion from backups, synced browser profiles, screenshots, or forensic recovery.

## Quick Start
Visit [live site](https://mimindmendinc.github.io/Tactical-BurnerContacts/) or:
```bash
git clone https://github.com/MiMindMendinc/Tactical-BurnerContacts.git
cd Tactical-BurnerContacts
# Open index.html in browser
```

## Features
- Auto-expiring contacts
- Panic wipe functionality
- Local vCard export after required assets have loaded
- PWA installation

## License
MIT - Privacy tools for the field.
