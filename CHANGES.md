# Внесённые изменения

Статическая страница образовательного портала Газпромбанка о финансах.

## Исходник

- Ветка: `base/original`
- Тег: `original-source`
- SHA первого коммита: `1e722d6e600325b8a1629692242f68f8dbde6e95`

## Сводка по файлам

| Файл | Статус | Что произошло |
|---|---|---|
| `LICENSE` | добавлен | Добавлен текст лицензии MIT. |
| `articles.html` | изменён | Использование SVG-иконок переведено на ссылки на символы общего спрайта. |
| `img/sprite.svg` | добавлен | Создан SVG-спрайт с символами логотипа, QR-кода, соцсетей, ссылки, глаза и времени чтения. |
| `img/eye.svg` → `img/sprite/eye.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/`. |
| `img/logo_head.svg` → `img/sprite/logo_head.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/`. |
| `img/qr.svg` → `img/sprite/qr.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/`. |
| `img/soc/19.vk.svg` → `img/sprite/soc/19.vk.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/soc/`. |
| `img/soc/link.svg` → `img/sprite/soc/link.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/soc/`. |
| `img/soc/odnoklassniki.svg` → `img/sprite/soc/odnoklassniki.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/soc/`. |
| `img/soc/tg.svg` → `img/sprite/soc/tg.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/soc/`. |
| `img/watch.svg` → `img/sprite/watch.svg` | изменён | SVG-файл перемещён в каталог `img/sprite/`. |

Удалённых файлов нет.

## Что доработано

### SVG-спрайт — `359c892 add sprite`

- Добавлен файл `img/sprite.svg` с SVG-символами.
- В `articles.html` ссылки на SVG заменены на использование соответствующих символов спрайта.
- Прежние отдельные SVG-файлы перенесены в каталог `img/sprite/`.

### Лицензия — `302a08f Create LICENSE`

- Добавлен файл `LICENSE` с текстом лицензии MIT.

## Как проверить дельту

[Сравнить `base/original` и `main`](https://github.com/romiusricco/gazprom_5/compare/base/original...main).

## TODO / известные проблемы

Явных маркеров TODO/FIXME в коде не найдено; известных проблем по рассматриваемым изменениям не зафиксировано.
