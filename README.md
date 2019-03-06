Оптимально удобные настройки для PhpStorm
__________________________________________
<a href="https://www.jetbrains.com/help/idea/sharing-your-ide-settings.html#settings-repository">Как установить настройки в свой PhpStorm ?</a><br>
__________________________________________
Для тех, кто использует битрикс, рекомендую установить :<br>
1. <a href="https://dev.1c-bitrix.ru/community/webdev/user/156743/blog/9382/">Встроенная документация по 1С-Битрикс в PhpStorm</a><br>
2. <a href="https://plugins.jetbrains.com/plugin/7616-bitrix-framework-support">Bitrix Framework Support</a><br>
__________________________________________
Несколько полезных ссылок:
1. Устанавливаем плагины в PhpStorm так "Preferences -> Plugins -> getgist -> Install", более подробно <a href="https://loftblog.ru/material/6-plaginy/">смотри тут</a><br>
2. <a href="https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf">Горячие клавиши в PhpStorm/IntelliJIDEA</a><br>
__________________________________________
Полезные плагины:
1. <a href="https://plugins.jetbrains.com/plugin/7495--ignore">.ignore</a> - плагин для автоматизированного создания файла .gitignore. Позволяет выбрать шаблон из удаленного репозитория или создать собственный шаблон.<br>
Шаблон .gitignore для bitrix (все шаблоны, нестандартные компоненты, модули и библиотеки мы должны хранить в local):
<pre>
.idea
.zip
.rar

/composer.lock

/bitrix
/images
/vendor
/upload

</pre>
2. <a href="https://plugins.jetbrains.com/plugin/10080-rainbow-brackets">Rainbow Brackets.</a> Плагин который разукрасит в разные цвета пары скобок в разные цвета.
