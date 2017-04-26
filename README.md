Project Empty Template (less, pug, gulp)

For start you need to enter in the console the following commands:

   1. git clone https://github.com/Jakovich/project-start.git && cd Project-start
   2. npm i
   3. npm i -g bower
   4. bower i
- *Local development:* npm start
- *Production version:* npm run build
- *Create new block:* node createBlock.js blockName. It will create less file in less/blocks/blockName.less & pug file in pug/includes/blockName.pug

Structure of files:
```bash
img/                    # General images for optimisatons
  icons-png/            # Icons in format png for create sprite.png
  icons-svg/            # Icons in format svg for create sprite.svg
  icons-svg-inline/     # Icons in format svg for create sprite-inline.svg (for html inline <svg><use href=""></use></svg>)
  img-svg/              # Images in format svg for minification
fonts/                  
vendor/                 # Стилевой файл блока
scripts/                # Custom scripts (minifiction)
less/
  blocks/
  mixins/
  variables.less
  style.less            # Point of css creation
pug/
  mixins/
  includes/
  extends/
  index.pug

```
