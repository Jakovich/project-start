Project Empty Template (less, pug, gulp)

For start you need to enter in the console the following commands:

   1. git clone https://github.com/Jakovich/project-start.git && cd Project-start
   2. npm i
   3. npm i -g bower
   4. bower i
Local development: npm start
Production version: npm run build
Create new block: node createBlock.js blockName
It will create less file in less/blocks/blockName.less & pug file in pug/includes/blockName.pug

Structure of files:
```bash

img/
  icons-png/                      # Изображения, используемые блоком и обрабатываемые автоматикой сборки
  icons-svg/                      # Изображения, используемые блоком и обрабатываемые автоматикой сборки
  icons-svg-inline/                      # Изображения, используемые блоком и обрабатываемые автоматикой сборки
  img-svg/                      # Изображения, используемые блоком и обрабатываемые автоматикой сборки
some-folder/            # Какая-то сторонняя папка, не обрабатываемая автоматикой
demo-block.scss         # Стилевой файл блока
demo-block--mod.scss    # Отдельный стилевой файл БЭМ-модификатора блока
demo-block.js           # js-файл блока
demo-block--mod.js      # js-файл для отдельного БЭМ-модификатора блока
demo-block.html         # Варианты разметки (как документация блока или как вставляемый микрошаблонизатором фрагмент)
readme.md               # Какое-то пояснение
```
