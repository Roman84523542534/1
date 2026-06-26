# Gazfond Sensey Email V2

Финальная сборка HTML-письма по обновленному референсу для загрузки в Сенсей и предпросмотра через GitHub Pages.

## Файлы

- `index.html` — публичный preview для GitHub Pages.
- `gazfond-sensey-email-preview.html` — локальный preview с подключенными assets.
- `gazfond-sensey-email.html` — production HTML для Сенсея с placeholders `{{IMAGE_1_URL}}` - `{{IMAGE_4_URL}}`.
- `gazfond-sensey-delivery-notes.md` — инструкция по загрузке и тестированию.
- `assets/full-bg-clean.jpg` — web-optimized фон письма для GitHub preview.
- `assets/icon-rules-v2.jpg`, `assets/icon-support-v2.jpg`, `assets/icon-choice-v2.jpg` — три круглые иллюстрации.

## CTA

Обе кнопки ведут на:

`https://crm.gazfond-pn.ru/landing?name=ZevLanding`

## Сенсей placeholders

- `{{IMAGE_1_URL}}` — фон письма.
- `{{IMAGE_2_URL}}` — первая иконка.
- `{{IMAGE_3_URL}}` — вторая иконка.
- `{{IMAGE_4_URL}}` — третья иконка.

Если в конкретном проекте Сенсея используется другой синтаксис переменных, замените placeholders перед отправкой.
