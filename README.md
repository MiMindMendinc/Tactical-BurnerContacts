# Tactical Burner Contacts

> Offline "burner" phonebook. No cloud. No tracking. No leaks.

![Screenshot placeholder](screenshot.png)

---

## Features

- 🔒 **100% client-side** — localStorage only, nothing ever leaves your device
- ⏱ **Auto-delete after 30 days** — configurable per contact
- 📳 **Panic wipe** — shake phone 3× within 1.5 seconds to erase everything instantly
- 📷 **vCard QR export** — works offline after first load
- 📦 **JSON export / import** — backup and transfer between devices
- 🔍 **Search** — filter by name, phone, tag, or notes
- 🌑 **Dark tactical theme** — low visibility, high contrast
- 📲 **Installable PWA** — add to home screen, works in airplane mode

Built in vanilla JS — same zero-dependency philosophy as [Tactical-FieldKit](https://github.com/MiMindMendinc/Tactical-FieldKit).

---

## How to use

1. Open `index.html` in any modern browser (or visit the GitHub Pages URL)
2. Tap **Add to Home Screen** to install as a PWA
3. Use it anywhere — even in airplane mode
4. Contacts auto-expire after 30 days (or your chosen duration)
5. Three rapid shakes triggers an instant full wipe — no confirmation needed

---

## File structure

```
index.html     ← entire app (single file, ~760 lines)
manifest.json  ← PWA install manifest
sw.js          ← service worker (offline cache)
LICENSE        ← MIT
```

---

## Privacy model

| What | How |
|------|-----|
| Storage | Browser `localStorage` only |
| Network | Zero after first load (SW cache) |
| Cloud sync | Never |
| Analytics | None |
| Crash reporting | None |

---

## License

MIT License — see [LICENSE](LICENSE)  
Built by **MichiganMindMendink**
