# zayavka_db
База с заявками

##################
* 'База с заявками'

Нужна программа с интерфейсом, куда можно вводить номер заявки и сумму.
После нажатия на кнопку "сохранить" заявка должна сохраниться в базе данных.
- нужно избежать дубликатов, при повторении заменить на свежую сумму.

Также нужно для интеграции с 1С, нужно выгрузать всю базу в CSV / XLSX.

1. Frontend
* 1.1 Внешний вид - "верстаем" макет в паинте, figma, схемах.
* 1.2 Выбор стека технологий - tkinter, pyside2, pyqt6(V)
* 1.3 Верстать можно: кодом vs QtDesigner(V) (https://www.pythontutorial.net/pyqt/qt-designer/)
* 1.4 Нужно регулярным выражением проверять валидность данных до отправки.(кнопку делать не активной)
* 1.5 Проверить, что кнопка вызывает событие и пробрасывает значения из формы в функию.
* * 

2. Backend
* 2.1 Планирование сущностей (создать таблицу) (https://chat.openai.com/)
* 2.2 Написание сервисов (CRUD) и проверка
* 2.3 Вынос паролей и секретный данных в .env (Only for Postgre)
* 2.4 Отправка части данных на почту.(выжимка за сутки)
* 2.5 Логирование - сохранять в базу данных (txt файл - небезопасно).
* * 

3. DevOps
* 3.1 Создать гитлаб/гитхаб репозиторий и jira/trello
* 3.2 Создание документации, тех.задания, функциональная схема к проекту
* 3.3 Собрать программу .exe. Возможно создать установщик.
* 3.4 Создание скриптов для автоматической сборки/проверки/публикации
* 3.5 Настройка tabnine и black


#
Сначала план
Выбрали список технологий
Создали репозиторий
Нашли туториал
"Набросали" макет
Создали дизайн
Подключили к коду и проверили
#
















