## Чтобы запустить скрипт в Telegram Web App с использованием веб-инспектора, выполните следующие шаги:
Подготовительные действия

- Скачайте и Запустите Бета-версию Telegram Desktop:
- Скачайте и установите Бета-версию Telegram Desktop для Windows или Linux.
- Запустите Telegram Desktop Beta.
- Перейдите в Настройки > Дополнительно > Экспериментальные настройки > Включить инспекцию веб-виджета.
- Щелкните правой кнопкой мыши на окно с игрой в Веб-виджете и нажмите комбинацию Ctrl+Shift+I

1. Откройте игру в Telegram Web App и веб-инспектор вашего браузера. Щелкните правой кнопкой мыши на рамку окна с игрой в Веб-виджете и нажмите комбинацию **Ctrl+Shift+I**
2. Перейдите на вкладку **Источники** в веб-инспекторе:
3. В папке **"tgCat/game/cat/js"** находится файл "bundle-*.js".
4. Откройте файл **"bundle-*.js"** и нажмите **Ctrl+F** вставьте  **L([A("leaguechange")], M.prototype, "updateBg", null),** и найдите строку. 
5. Установите точку останова на этой строке. Вы можете сделать это, щелкнув по номеру строки слева от кода или нажав клавишу **F9** на клавиатуре.
6. Перезагрузите страницу. Нажмите клавишу **F5** на клавиатуре, чтобы перезагрузить страницу.
7. Перейдите на вкладку **Консоль** и внизу страницы введите скопированный скрипт из файла **script.js** и нажмите клавишу **Enter**.
8. Далее нажмите кнопку продолжить для запуска игры со скриптом, в игре жмём на кнопку автобота чтобы его включить!
   можем закрыть окно консоли по желанию
Для последующих запусков убедитесь что стоит точка останова, перейдите в консоль, нажмите клавишу **Вверх** и **Enter** и продолжить для запуска приложения
