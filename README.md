# 🥷 Night of the Ninja

Joc de party multiplayer pentru 4-8 jucători - fiecare cu propriul telefon!

## 🎮 Cum se joacă

### Pas 1: Firebase Setup (o singură dată - 3 minute)

1. Deschide [console.firebase.google.com](https://console.firebase.google.com)
2. Click **"Add project"** → nume: `ninja-game` → Continue × 2 → **Create project**
3. **Build** → **Realtime Database** → **Create Database**
4. Alege location (Europe - Belgium) → Next
5. **Start in test mode** → **Enable**
6. **Copiază URL-ul** (ex: `https://ninja-xxxxx-default-rtdb.firebaseio.com/`)

### Pas 2: Joacă!

1. **Host**: Deschide linkul jocului → lipește URL-ul Firebase → **"Creează Cameră"** → primește cod (ex: `ABCD`)
2. **Jucători**: Fiecare deschide linkul pe telefon → lipește URL-ul Firebase → introduc codul `ABCD` → **Join**
3. **Fiecare vede doar propriul ecran** cu rolul și cărțile lui - 100% privat! 🥷

## 🎯 Reguli

- **Ninja**: Evită să fii prins
- **Ofițer**: Prinde Ninja-ul
- **Mafiot**: Protejează Ninja-ul
- **Cetățeni**: Ajută Ofițerul

Fiecare rundă: jucătorii primesc 3 cărți de acțiune și aleg una simultan!

## 🔧 Tehnologii

- Firebase Realtime Database (sincronizare în timp real)
- HTML5 + Vanilla JavaScript
- Responsive design pentru mobile

---

**Made with ❤️ for game nights**
