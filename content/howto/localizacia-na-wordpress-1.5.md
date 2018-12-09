---
title: "Локализация на WordPress 1.5"
date: 2006-03-23T08:44:33+01:00
---

[WordPress](http://www.wordpress.org/) e система за персонално публикуване. В това кратко описание ще научите как можете да локализирате вашата инсталация на WordPress в случая - на български език.

Първото и най-важно нещо което трябва да знаете е каква кодировка използва Вашият блог. По подразбиране това е UTF-8, а използваната кодировка можете да разберете от Administration -> Options -> Reading -> Code page .... За български страници най-често се използват UTF-8 и Windows-1251 кодировки. Ако желаете да използвате вече направените преводи, можете да ги намерите на адрес: http://svn.automattic.com/wordpress-i18n/bg_BG/tags/ Там намерете желаната версия (ако използвате WordpPress 1.5 или 1.5.x за препоръчване е да изберете превода на 1.5.1.3) и изтеглете .po файла ако желаете да правите промени, или само .mo файла при положение че желаете да ползвате готовият както следва:

```
bg_BG.mo - UTF-8 компилиран превод
bg_BG.po - UTF-8 превод в текстов формат
```

Ако желаете да редактирате .po файловете, можете да използвате текстов редактор, POEdit, KBabel или gtranslator. След това компилирайте файла чрез командата:

```
msgfmt -o bg_BG.mo bg_BG.po
```

включена в пакета GNU Gettext. Копирайте bg_BG.mo файла в директория:

```
wp-includes/languages/
```

Отворете файлa wp-config.php и променете часта:

```
// Change this to localize WordPress.  A corresponding MO file for the
// chosen language must be installed to wp-includes/languages.
// For example, install de.mo to wp-includes/languages and set WPLANG to 'de'
// to enable German language support.
define ('WPLANG', 'bg_BG');
```

N.B. Файлът трябва да се казва bg_BG.po

Това е всичко.

За повече информация прочетете [Localizing WordPress](http://codex.wordpress.org/Localizing_WordPress)
