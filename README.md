# dle-plugins
Сборник плагинов для новой системы управления модулями/хаками в DLE 13.x

## auto-subcats.xml
Хак позволяет использовать запись `{subcat=3}` для вывода списка подкатегорий в виде списка `3,5,7,8,9`

https://sandev.pro/web/136-hak-avtomaticheskiy-vyvod-spiska-id-podkategoriy.html

## cat-expand.xml
Когда занимаешься созданием развернутой структуры категорий - при каждом обновлении страницы приходится повторно нажимать кнопку "Развернуть все".

Данный хак запоминает состояние кнопки и при перезагрузке страницы нет необходимости повторно нажимать эту кнопку.

## cat-new-posi.xml
При создании категории или подкатегории не учитывается параметр posi. Вернее у новой категории этот параметр позиции равен единице, отчего при создании категория размещается не в конце списка, а в начало ветки.

Данный хак размещает новую созданную категорию/подкатегорию в конец списка ветки.

## cat-sub-add.xml
Когда много категорий - становится довольно неудобно добавлять подкатегории. В частности каждый раз приходится искать нужную категорию в списке.
Данный хак добавляет кнопку, при клике на которую сразу становится отмеченной выбранная категория.

## Headers-Menu.xml
Автоматическое создание содрежания для статьи из заголовкой `H2-H6`

https://sandev.pro/web/129-avtomaticheskoe-sozdanie-soderzhaniya-stati-dlya-dle.html

## breadcrumbs.xml
Хлебные кроши в соответствии с schema.org

https://sandev.pro/web/105-hlebnye-kroshki-speedbar.html

## multivybor-v-doppoljah-by-sander.xml
Простенький плагин, который позволит в доп.поле тип "Список" выбирать несколько значений.

https://sandev.pro/web/146-multivybor-v-doppolyah-dlya-dle-13.html
