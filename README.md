# Show-answer-name-DLE-
Показывает в `древовидных` ответах на комментариях имя пользователя кому был дан ответ.


Не использует дополнительных sql запросов. Показывает во всех разделах где выводятся комментарии.
Минимальные требования DLE 13.0 версии (Установка в разделе плагины). На ранние версии произвести все правки вручную.

Для 13.2 версии есть отдельный файл.

---
В шаблоне `comments.tpl` используйте в нужном месте [answer]{answer}[/answer]
`{parent}` используйте в нужном месте для вывода ID комментария на котодый рали ответ.


В настройках параметров скрипта в разделе комментарии дополнительные 4 настройки.
  - Включить\Выключить. (Влияет только на показ)
  - Выводить имя в виде ссылки на профиль если это зарегистрированный пользователь, иначе выводит email или ссылку на комментарий кому отвечают.
  - Поле с текстом которое показывается если пользователь ответил самому себе. (Можно оставить пустым и убрать вывод)
  - Префикс текст для ответов посетителям. (Оставив поле пустым выведет только имя)

---
Перед установкой если у вас уже много комментариев то произведите перестроение комментариев в соответствующем разделе.

### Donate
Для материальной благодарности.

<img src="https://qiwi.com/favicon.ico" width="16" height="16"> [Qiwi](https://qiwi.me/teramoune)

<img src="https://www.webmoney.ru/img/logo-wm-sat-small.png" width="139" height="34">

 - Z990082286464
 - 4100115063692304 (yandex)

teramoune@gmail.com на всякий случай.
