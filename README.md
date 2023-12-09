# [MRT] - Машинное чтение текста
Расширение позволяет воспроизвести написанный текст синтезированным голосом, теперь доступен не только в Yandex Browser версии Windows. Признателен **[Yandex.Translate](https://translate.yandex.ru/)** за такую возможность.
- Функция **"Слушать"** имеет лимит в 20k символов *(≈3000 слов)* на запрос. **(✅ Cтабильна)**
- Функция **"Скачать"** имеет лимит в 1k символов *(≈140 слов)* на запрос. **(⚠️ НЕ стабильна)**
  
>  ## Окно объявлений:
>
> | [!] | Объявление |
> |----|---------|
> | ⚠️ | Функция **"Скачать"**, на данный момент, НЕ стабильна, а вероятность сбоя составляет ≈75%. |
> | ⚠️ | Если вам интересно помоч мне починить функцию **"Скачать"**, пожалуйста, предлогайте **[Pull requests](https://github.com/Alkohole/udr/pulls)**, сам линк **[Скрипта](https://github.com/Alkohole/udr/blob/main/down.html#L81)**. |
> | ❓ | Контекстное окно в 50k символов не работает стабильно и прерывается на 18-19kk символе. При этом 20k работают стабильно. |
>
> ## Демо видео:
>
> https://github.com/Alkohole/udr/assets/59339504/99fdac2b-0f26-42e5-94eb-2a550acb5a7c

## Установка расширения:

1. Установите расширение **[Tampermonkey](https://www.tampermonkey.net/)** (Альтернатива для Safari: **[UserScripts](https://apps.apple.com/app/userscripts/id1463298887 )**).
2. **[Установите Скрипт](https://github.com/Alkohole/udr/raw/main/mrt.user.js)**.

## Примечание:

| Кнопка | Действие |
|----|---------|
| **⇅** | Cворачивает/разворачивает окно ввода. |
| **⚙** | Cворачивает/разворачивает окно настроек. |
| **▶** | Воспроизводит/останавливает озвучивание текста. |
| **⏎** | Скачивает озвученный текст. |

<br>

- Имеется обработчик дропа в окно ввода (Выделите текст и перетащите его в окно ввода, ранее находящийся в окне текст автоматически стирается).
- Имеется счетчик количества символов в окне (Если превышение лимита - вы увидите сообщение).

### ⚠️ Не доступно:
- Пауза.
- Регулировка громкости.
- Выбор голоса озвучки.

## Демонстрационные страницы:
1. **[Слушать](https://alkohole.github.io/udr/)** **(✅ Stable)**
2. **[Скачать](https://alkohole.github.io/udr/down)** **(⚠️ Unstable)**

### PS:
Это **домашний скрипт**, изначально предназначенный для личного использования. <br>
Т.к. я являюсь пользователем Linux, я не имею желания и возможности пользоваться Yandex Browser, где только в версии Windows есть возможность прочитать страницу с помощь Яндекс Алисы.
