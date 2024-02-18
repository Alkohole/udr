# [MRT] - Машинное чтение текста
Расширение позволяет воспроизвести написанный текст синтезированным голосом, теперь доступен не только в Yandex Browser версии Windows. Признателен **[Yandex.Translate](https://translate.yandex.ru/)** за такую возможность.
- Функция **"Слушать"** имеет лимит в 20k символов *(≈3000 слов)* на запрос. **(✅ Cтабильна)**
- Функция **"Скачать"** имеет лимит в 1k символов *(≈140 слов)* на запрос. **(⚠️ НЕ стабильна + ЗАБРОШЕНА)**

|  | From | To | Date |
|---|---|---|---|
| Расширение | ~~v0.4.6~~ | **v0.4.7** | 09.12.23 |
| Страница окна | ~~v0.2~~ | **v0.2.1** | 18.02.24 |

## Демо видео:

https://github.com/Alkohole/udr/assets/59339504/99fdac2b-0f26-42e5-94eb-2a550acb5a7c

## Окно объявлений:

> [!Note]
> |  | Объявление |
> |----|---------|
> | ⚠️ | Если вам нужна английская версия - воспользуйтесь **[Edge TTS](https://github.com/EdgeTTS/EdgeTTS.github.io)** или любым другим TTS. |
> | ⚠️ | Функция **"Скачать"** - **НЕ стабильна**, да еще и **ЗАБРОШЕНА**, а вероятность сбоя выше альпийских гор. Если вам интересна данная функця - пожалуйста, исправьте и пришлите ее мне **[Pull requests](https://github.com/Alkohole/udr/pulls)**, сам линк **[Скрипта](https://github.com/Alkohole/udr/blob/main/down.html#L81)**. _(нагло? я полностью с вами согласен!)_ |
> | ⚠️ | В случае неполадок - перезагрузите браузер. |
> | ⚠️ | Открыть окно плагина в **Github**'е не получится, из-за того, что страница находится на поддомене самого **Github**. |
> | 🙂 | Класс `.boxButton_tts.state-` прекрасный класс. |


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



- Имеется обработчик дропа в окно ввода (Выделите текст и перетащите его в окно ввода, ранее находящийся в окне текст автоматически стирается).
- Имеется счетчик количества символов в окне (Если превышение лимита - вы увидите сообщение).

### ⚠️ Не доступно:
- Пауза.
- Регулировка громкости.
- Выбор голоса озвучки.

### ⚠️ Возможные планы:
- [ ] Пауза.
- [ ] Визуализация блоков озвучки.
- [ ] Таймер.
- [ ] Регулировка громкости.
- [ ] Отказ от лимита.
- [ ] Переработка скрипта в стандартное расширение.
- [ ] Переосмысление логики.
- [ ] Отчистка кеша.
- [x] **Исправить ошибки в README.md**...

## Демонстрационные страницы:
1. **[Слушать](https://alkohole.github.io/udr/)** **(✅ Stable)**
2. **[Скачать](https://alkohole.github.io/udr/down)** **(⚠️ Unstable and Abandoned)**

<hr>

> ### PS:
> Это **домашний скрипт**, изначально предназначенный для личного использования. <br>
> Т.к. я являюсь пользователем Linux, я не имею желания и адекватной возможности пользоваться шиндорс версией Yandex Browser, только в которой есть возможность прочитать страницу с помощю Яндекс Алисы.

<hr>
