# Personal tasks Sergey — публичные страницы подключения Obsidian

Статический сайт для `https://obsidian.mirsa-ai.ru/` на бесплатном GitHub Pages.

## Публичные файлы

- `index.html` — описание подключения.
- `privacy.html` — политика конфиденциальности и раздел условий использования `#terms`.
- `style.css` — локальное оформление без внешних библиотек и шрифтов.
- `CNAME` — отдельный поддомен сайта.
- `.nojekyll` — публикация готовых HTML-файлов без Jekyll.

Сайт не содержит паролей, OAuth-ключей, токенов, идентификаторов календарей или содержимого хранилища Obsidian.

## Публикация

Репозиторий: `sergeym-80/obsidian-calendar-site` (публичный для GitHub Pages на бесплатном тарифе).

Источник GitHub Pages: ветка `main`, корневая папка `/`.

Порядок: подтвердить владение доменом в GitHub → настроить Pages и Custom domain → добавить CNAME поддомена в Beget → дождаться DNS и сертификата → включить Enforce HTTPS → проверить оба URL.

Предлагаемая запись DNS: `obsidian.mirsa-ai.ru CNAME sergeym-80.github.io.`. Существующие записи корневого домена, почты и `n8n` сохраняются. Точное значение TXT для проверки владения выдаёт GitHub; оно не должно быть придумано.

## Страницы для описания подключения

- Homepage: `https://obsidian.mirsa-ai.ru/`
- Privacy: `https://obsidian.mirsa-ai.ru/privacy.html`
- Terms: `https://obsidian.mirsa-ai.ru/privacy.html#terms`
- Authorized domain: `mirsa-ai.ru`

Данные Google не должны добавляться в этот репозиторий. В репозиторий отправляются только перечисленные статические файлы.
