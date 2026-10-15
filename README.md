# Алёна Егоровна — taro-privorot-gadanie.site

Статический лендинг. Основа — сайт Зарины (`gadalka-medium-privorot.site`, шаблон `privorot-gadanie-taro.site`),
переделанный визуально (фиолетовая палитра, другие шрифты, порядок блоков, мозаичная галерея) и по текстам.

- Имя: `Алёна Егоровна`
- Телефон: `+7 707 949 03 14`
- WhatsApp: `77079490314`
- Домен: `taro-privorot-gadanie.site`

## Фото

- `media/hero.jpg` — главный экран
- `media/avatar.jpg` — круглая кнопка связи
- `media/about.jpg` — «Обо мне»
- `media/gallery/` — галерея (мозаика)
- `media/og-image.jpg` — превью ссылки, 1200×630

Сертификаты пока не добавлены — стили `.cert-grid` / `.cert-card` уже есть в `styles.css`.

## Защита от копирования

[site-copytrap](https://github.com/daviddt369/site-copytrap): все `og:*`, `twitter:*` и фавиконки стоят выше скриптов
защиты, а `<` в inline-блоке записаны как `\x3c`.

## Локально

```bash
python -m http.server 8080
```
