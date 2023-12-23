# Что нужно для отображения картинок, гифок, видео и аудио в чате? 🤔

> Просто отправь в чат ссылку с поддерживаемым форматом файла (Пример: .jpg, .gif, .mp4, .mp3)

## Установка

> Установить расширение [«Tampermonkey»](https://www.tampermonkey.net/) для [«Chrome»](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo), [«Microsoft Edge»](https://microsoftedge.microsoft.com/addons/detail/iikmkjmpaadaobahmlepeloendndfphd), [«Firefox»](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/), [«Opera Next»](https://addons.opera.com/en/extensions/details/tampermonkey-beta/), Альтернатива для [«Safari»](https://apps.apple.com/app/userscripts/id1463298887)
>
> Установить [«скрипт»](https://github.com/c0IIwr/Chat-Image-Display/raw/main/Chat-Image-Display.user.js)
>
> Обновить страницу браузера 😁👍

<img  src="https://c0IIwr.github.io/Chat-Image-Display/zapaska-archive.gif">

## Часто задаваемые вопросы

Как скопировать изображение или открыть в новой вкладке?

> Клик левой кнопкой мыши по изображению копирует ссылку в буфер обмена, двойной клик открывает ссылку в новом окне

Какие форматы файлов поддерживаются?

> Ссылки со следующими форматами отображаются в чате:
> > Для изображений: .jpeg, .jpg, .png, .gif, .gifv, .webp, .avif
> >
> > Для видео: .mp4, .webm, .mov
> >
> > Для аудио: .mp3, .ogg

На каких стриминговых платформах доступен скрипт?

> На данный момент скрипт работает для сайтов [«VK Play Live»](https://vkplay.live/) и [«Boosty»](https://boosty.to/). В будущем скрипт будет доступен для [«Kick»](https://kick.com/), [«Twitch»](https://www.twitch.tv/), [«YouTube»](https://www.youtube.com/), [«Trovo»](https://trovo.live/), [«GoodGame»](https://goodgame.ru/)

Почему Tampermonkey, если скрипт можно добавить в браузер с помощью любого расширения, которое умеет инъектить код в открытые страницы? ([«Пример»](https://chromewebstore.google.com/detail/custom-javascript-for-web/ddbjnfjiigjmcpcpkmhogomapikjbjdk))

> Tampermonkey предлагает ряд преимуществ, включая автоматические обновления скриптов, управление ими через одно удобное расширение, а также широкие возможности настройки. Это делает процесс добавления, управления и обновления скриптов более простым и эффективным, чем при использовании других расширений

## Автообновление

> **Для автообновления Tampermonkey, перейдите:**
> - Панель управления → Настройки → Обновление пользовательских скриптов → Проверять обновления: Каждый день
>
> **Для автообновления скрипта, перейдите:**
> - Установленные скрипты → Chat Image Display → Настройки → Обновления → ✅ Проверять наличие обновлений → Сохранить

<img  src="https://c0IIwr.github.io/Chat-Image-Display/AutoUpdate.gif">

## Список изменений

**v1.0**
- Выпущено

**v1.1**
- Нажатие ЛКМ теперь копирует изображение в буфер обмена
- Ссылка обрезается после расширения файла изображения (полезно для Discord ссылок)

**v1.2**
- Добавлен .webp формат для отображения в чате

**v1.3**
- Добавлен .avif формат для отображения в чате (для 7TV смайлов)
- Добавлен .gifv формат для отображения в чате (для Imgur гифок)
- Курсор изменен на 'pointer' при наведении на изображдение
- Двойной клик теперь открывает изображение в новой вкладке
- Скрипты 'VK Play Chat Image Display' и 'Boosty Chat Image Display' были объединены в один 'Chat Image Display'
- Теперь скрипт автообновляется

**v1.4**
- Исправлен автопрокрут чата (спасибо @shtrih)

**v1.5**
- Добавлен автопрокрут чата Boosty
- Исправлено наложение сообщений чата Boosty друг на друга
- Улучшено отображение границ изображений

**v1.6**
- Добавлена поддержка видео форматов для отображения в чате
- Добавлена поддержка аудио форматов для отображения в чате
