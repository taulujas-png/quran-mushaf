# Quran Mushaf — Madani pages (PNG)

604 страницы Мединского Мусхафа (Hafs 'an 'Asim) в формате **PNG (палитра, 16 уровней серого)** для оффлайн-ридеров.

- **Источник:** [batoulapps/quran-svg](https://github.com/batoulapps/quran-svg) (MIT) — официальные
  векторные файлы Королевского комплекса печати Корана (KFGQPC), конвертированы в SVG.
- **Здесь:** SVG → grayscale → PNG-палитра, ширина 900px, 16 уровней.
- **Имена файлов:** `001.png` … `604.png` (3 цифры с ведущими нулями).
- **Разрешение:** ~900×1287 (портрет).
- **Вес:** ~40 МБ на весь пакет (усреднённо ~65 КБ/страница).

## Прямой доступ (jsDelivr)

```
https://cdn.jsdelivr.net/gh/taulujas-png/quran-mushaf@main/{page3}.png
```

`{page3}` — номер страницы с ведущими нулями (например `293.png` → `https://cdn.jsdelivr.net/gh/taulujas-png/quran-mushaf@main/293.png`).

## Сборка

```bash
node scripts/build-mushaf.mjs          # PNG @900px (~40 МБ)
node scripts/build-mushaf.mjs --format webp   # WebP, если нужен другой формат
```
