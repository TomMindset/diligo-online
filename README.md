# Diligo Website

Statische Neuprogrammierung der bisherigen STRATO-Builder-Seite `https://diligo.online/`.

## Struktur

- `index.html` - Startseite
- `kontakt/index.html` - Kontaktseite mit Mailto-Formular
- `impressum/index.html` - Impressum
- `datenschutz/index.html` - Datenschutzhinweise fuer die statische Version
- `assets/` - Stylesheet, Logo und Keyvisual

## Lokal ansehen

Die Seite ist statisch und kann direkt im Browser geoeffnet werden. Fuer saubere absolute Pfade:

```powershell
python -m http.server 4173
```

Dann `http://localhost:4173/` oeffnen.

## Hinweis

Die Datenschutzseite ist an diese statische Umsetzung ohne externe Fonts, Maps oder Analytics angepasst. Vor Livegang bitte mit dem tatsaechlichen Hosting und allen spaeter ergaenzten Diensten abgleichen.
