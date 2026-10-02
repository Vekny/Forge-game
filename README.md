# Forge Idle (Web)

Cartoon stílusú multi-age idle RPG – web verzió.

## Futtatás

```bash
npm install
npm run dev
```

Majd nyisd meg a böngészőben a kiírt címet (általában http://localhost:5173).

## Build production-re

```bash
npm run build
```

A `dist` mappa lesz a kész weboldal (ezt lehet Vercelre / Netlify-re tenni).

## Jelenlegi funkciók

- Hős + statok (Damage, Health, Crit)
- Stage harc
- Forge (fegyver)
- Inventory + Equip
- Anyagok
- Mentés localStorage-ba + offline progress
- 10 kor

## Későbbi Flutter átvitel

A játéklogika a `src/models/game.js` fájlban van elkülönítve. Ezt viszonylag könnyű lesz Flutterbe átírni.
