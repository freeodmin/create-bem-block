# Быстрое создание нового блока по БЭМ

**По умолчанию создаст следующую структуру**  

src/  
-blocks/  
--имя_блока/  
---img/  
---имя_блока.scss

**Использование**  

`node createBlock.js [имя блока] [доп. расширения через пробел]`

**Пример**  

`node createBlock.js header js`

**Cоздаст следующую структуру**  
src/  
-blocks/  
--header/  
---img/  
---header.scss

**Файл конфига, где можно изменить пути**  

`configCreateBlock.js`
