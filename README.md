# UNIMAG — Система проверки подлинности

Открытый сайт для проверки подлинности флаконов парфюма из лимитированной коллекции.

## 🌐 Сайт

https://dousheng34.github.io/unimag-check/

## 🧪 Тестовые ссылки

- https://dousheng34.github.io/unimag-check/?id=1 → ✓ Флакон №0001
- https://dousheng34.github.io/unimag-check/?id=250 → ✓ Флакон №0250
- https://dousheng34.github.io/unimag-check/?id=500 → ✓ Флакон №0500
- https://dousheng34.github.io/unimag-check/?id=9999 → ✗ Код не найден

## 📦 Что внутри

- `index.html` — готовый сайт со встроенной базой из 500 флаконов
- `flacons.csv` — справочная база
- `qr_codes/` — 500 QR-кодов, ведущих на сайт

## 🚀 После теста — перенос на Tilda

1. Скопировать содержимое `index.html`
2. Вставить в блок T123 на Tilda (`qrorig.tilda.ws/kaz2026`)
3. Перегенерировать QR-коды с Tilda-URL
