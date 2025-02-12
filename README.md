# Twitter Bootstrap

![Bootstrap logo](https://i.imgur.com/qhtywl2.png)  
**Twitter Bootstrap** - популярный набор компонетов для фронтенд-разработки.     
Пострен на базе следующих технологий:
* HTML;
* CSS;
* JavaScript.

## Начало работы
Есть несколько вариантов подключения:
1. Пакетный менеджер [npm](https://npmjs.com);
1. CDN.

### Установка при помощи npm
Откройте консоль и выполните следующую команду: `npm install bootstrap`

### Установка помощи CDN
Если вы хотите подключить только CSS (без JavaScript-плагинов), добавьте в ваши html-файлы следующий код:
```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha284-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkF0JwJ8ERdknLPMO" crossorigin="anonymous">
```

Для JavaScript необходимо добавить следующий код:
```html
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.3/dist/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```

### Использование
Все возможности по использованию описаны в [официальной документации](https://getbootstrap.com/docs/4.1/getting-started/introduction/).