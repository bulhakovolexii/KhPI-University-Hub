# KhPI University Hub

Дочірня тема для wordpress, що базується на темі University Hub від WEN Themes і є її редизайном з дотриманням корпоративного стилю Національного технічного університету "Харківський політехнічний інститут".

Для редагування файлів стилів та змінних необхідно:

1. встановити Node.js [інструкція](https://nodejs.org/en/download/prebuilt-installer);
2. перейти до кореневого каталогу теми;
3. виконати команду `npm install`;
4. для генерації стилів використовується препроцесор SASS в синтаксисі SCSS [інструкція](https://sass-lang.com/);
5. відстеження змін та збирання `.css` файлів виконується командою `npm run watch`;
6. для збереження змін необхідно:
    - 6.1 видалити директорію node_modules з усім вмістом;
    - 6.2 збільшити номер версії у заголовку файлу style.css;
    - 6.2 заархівувати кореневий каталог у форматі .zip;
    - 6.3 встановити оновлення через інтерфейс майстерні wordpress.
