# Play Store listing — Arabic Speaker (متحدث العربية)

Draft copy for Google Play Console "Main store listing" page. Play Console accepts separate translations per language — upload all three.

---

## Metadata (common to all languages)

- **Package name**: `org.workshopdiy.arabicspeaker`
- **Category**: `Books & Reference` (primary), `Education` (secondary if allowed)
- **Tags**: Islamic studies, Arabic, trilingual, education, al-Ghazali
- **Contact email**: `abdelhak.bourdim@gmail.com`
- **Website**: `https://workshop-diy.org`
- **Privacy policy URL**: REQUIRED — host a simple page (see template at end of this file).
- **Content rating**: Everyone (no violence, no gambling, no mature content).
- **Ads**: No.
- **In-app purchases**: No.
- **Data safety**: No data collected, no data shared.

---

## Arabic (ar) — primary

### App name (≤30 chars)
```
متحدث العربية
```

### Short description (≤80 chars)
```
النطق العربي + التعرف على الكلام — متعدد اللهجات
```

### Full description (≤4000 chars)
```
🗣️ متحدث العربية

تطبيق نطق عربي كامل (نص إلى كلام وكلام إلى نص) يعمل في المتصفح فقط. لهجات متعددة (سعودي، مصري، إماراتي، مغربي...)، اختيار الصوت، ضبط السرعة والنبرة والحجم. بدون خادم وبدون تتبع.

— من workshop-diy.org
```

---

## English (en)

### App name
```
Arabic Speaker — Arabic Speaker
```

### Short description
```
Arabic TTS + STT — multi-dialect, offline TTS
```

### Full description
```
🗣️ Arabic Speaker

Fully client-side Arabic Text-to-Speech and Speech-to-Text app. Multiple dialects (ar-SA, ar-EG, ar-AE, ar-MA, etc.), voice selection, adjustable rate/pitch/volume. No backend, no tracking. TTS works offline.

— From workshop-diy.org
```

---

## French (fr)

### App name
```
Arabic Speaker — Locuteur Arabe
```

### Short description
```
Synthèse + reconnaissance vocale arabe — multi-dialecte
```

### Full description
```
🗣️ Locuteur Arabe

Application de synthèse et reconnaissance vocale arabe entièrement côté client. Plusieurs dialectes (ar-SA, ar-EG, ar-AE, ar-MA, etc.), choix de voix, débit/hauteur/volume réglables. Pas de backend, pas de suivi.

— De workshop-diy.org
```

---

## Graphics needed (minimum)

| Asset | Size | Source |
|---|---|---|
| App icon | 512×512 PNG | `store-assets/play-store-icon-512.png` (regenerate per book) |
| Feature graphic | 1024×500 PNG | `store-assets/feature-graphic.png` (render from `feature-graphic.html`) |
| Phone screenshots | min 2, 320–3840px, 16:9 portrait | Capture from emulator / real device |
| 7" tablet screenshots (optional) | min 2, 1024×600+ | Run emulator with tablet profile |

Screenshots to capture (book-specific — adjust list to actual app screens):
1. Home / cover / introduction
2. Main content navigation
3. Reading or interaction mode
4. Quiz or self-assessment (if applicable)
5. Theme switch (optional — shows the 3 variants)

---

## Privacy policy template

Copy to a public page (GitHub Pages works). Change email + date.

```
Privacy Policy — Arabic Speaker
Last updated: 2026-04-27

The Arabic Speaker app does not collect, store, transmit, or share any personal
data. All content is bundled with the app and runs entirely on your device.
The app does not use analytics, advertising networks, crash reporters, or
third-party SDKs.

The app requires no special permissions beyond internet access, which is
used only to load the occasional external link (e.g. workshop-diy.org) if
you tap it — never silently in the background.

If you have questions, contact: abdelhak.bourdim@gmail.com
```
