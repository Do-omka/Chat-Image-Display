# Что нужно для отображения картинок и гифок в чате? 🤔

> Просто отправьте в чат ссылку на изображение с форматом файла

## Установка

> Установить расширение [«Tampermonkey»](https://www.tampermonkey.net/) для [«Chrome»](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo), [«Microsoft Edge»](https://microsoftedge.microsoft.com/addons/detail/iikmkjmpaadaobahmlepeloendndfphd), [«Firefox»](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/), [«Opera Next»](https://addons.opera.com/en/extensions/details/tampermonkey-beta/), Альтернатива для [«Safari»](https://apps.apple.com/app/userscripts/id1463298887)
>
> Установить [«скрипт»](https://github.com/c0IIwr/Chat-Image-Display/raw/main/Chat%20Image%20Display.user.js)
>
> Обновить страницу браузера 😁👍

<img  src="https://c0IIwr.github.io/Chat-Image-Display/zapaska-archive.gif">

## Часто задаваемые вопросы

Почему Tampermonkey, если скрипт можно добавить в браузер с помощью любого расширения, которое умеет инъектить код в открытые странички? ([«Пример»](https://chromewebstore.google.com/detail/custom-javascript-for-web/ddbjnfjiigjmcpcpkmhogomapikjbjdk))

> Tampermonkey предлагает ряд преимуществ, включая автоматические обновления скриптов, управление ими через одно удобное расширение, а также широкие возможности настройки. Это делает процесс добавления, управления и обновления скриптов более простым и эффективным, чем при использовании других расширений.

На каких стриминговых платформах доступен скрипт?

> На данный момент скрипт работает для сайтов [«VK Play Live»](https://vkplay.live/) и [«Boosty»](https://boosty.to/). В будущем скрипт будет доступен для [«Kick»](https://kick.com/), [«Twitch»](https://www.twitch.tv/), [«YouTube»](https://www.youtube.com/), [«Trovo»](https://trovo.live/)

Какие форматы файлов изображений поддерживаются?

> Форматы .jpeg, .jpg, .png, .gif, .gifv, .webp, .avif отображаются в чате

## Автообновление

> **Для автообновления Tampermonkey, перейдите:**
> - Панель управления → Настройки → Обновление пользовательских скриптов → Проверять обновления: Каждый день
>
> **Для автообновления скрипта, перейдите:**
> - Установленные скрипты → Chat Image Display → Настройки → Обновления → ✅ Проверять наличие обновлений → Сохранить

<img  src="https://c0IIwr.github.io/Chat-Image-Display/AutoUpdate.gif">

## Список изменений

**1.0**
- Выпущено

**1.1**
- Нажатие ЛКМ теперь копирует изображение в буфер обмена
- Ссылка обрезается после расширения файла изображения (полезно для дискорд ссылок)

**1.2**
- Добавлен .webp формат для отображения в чате

**1.3**
- Добавлен .avif формат для отображения в чате (для 7tv смайлов)
- Добавлен .gifv формат для отображения в чате (для imgur гифок)
- Курсор изменен на 'pointer' при наведении на изображдение
- Двойной клик теперь открывает изображение в новой вкладке
- Скрипты 'VK Play Chat Image Display' и 'Boosty Chat Image Display' были объединены в один 'Chat Image Display'
- Теперь скрипт автообновляется

**1.4**
- Исправлен автопрокрут чата (спасибо @shtrih)
