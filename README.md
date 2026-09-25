# 🎬 REEL RAGE 24/7 - Movie Ragebait CTF Website

A static fictional movie-ragebait website designed for CTF challenges, featuring:
- **Author/Admin Persona**: `bluesatta` (permanently suspended from IMDb, hostile, self-proclaimed auteur).
- **Retro / Low-Quality Web Aesthetic**: Neon accents, marquee alerts, pixelated hit counter, beveled buttons, suspicious fake ads ("UltraCodec v3.exe", "Local Cinephiles"), and fake poll.
- **Ragebait Reviews & Exaggerated Ratings**:
  - *The Godfather (1972)*: `0.5 / 10` ("Boring olive oil infomercial, Paul Blart 2 is superior")
  - *Madame Web (2024)*: `11 / 10` ("Modern Shakespeare, Martin Scorsese is shaking")
  - *The Dark Knight (2008)*: `1.2 / 10` ("Throat lozenges & Jim Carrey Grinch rip-off")
  - *Oppenheimer (2023)*: `-4 / 10` ("Zero subway surfers gameplay on screen")
- **Non-Functional Links**: All links and buttons are static / harmless dummy links with vintage in-page alert messages.
- **CTF Features & Easter Eggs**:
  - Hidden HTML comments with credentials / hints in `index.html`.
  - Realistic `robots.txt` containing disallowed administrative routes.
  - Console logs inside developer tools simulating admin session data.

---

## 🚀 How to Run / Test Locally

### Option 1: Double-click to open
Simply open `index.html` in any web browser.

### Option 2: Run a quick local HTTP server
Using Python:
```bash
python -m http.server 8080
```
Then visit: `http://localhost:8080`

Using PHP:
```bash
php -S localhost:8080
```

---

## 🎯 Customizing for your CTF Challenge
- Edit the flag in the header comments of `index.html` (e.g. search for `FLAG` or `Flag_Hint`).
- Customize routes in `robots.txt` to point to actual challenge endpoints if you integrate this into a larger CTF box.
