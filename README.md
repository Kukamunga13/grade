## Готовая сборка Webpack

<div>
    <a href="https://github.com/webpack/webpack">
        <img width="150" height="150" src="https://webpack.js.org/assets/icon-square-big.svg">
    </a>
</div>
<br/>
<br/>

![GitHub release](https://img.shields.io/github/release/brovkin/webpack-frontend-template.svg)
![GitHub stars](https://img.shields.io/github/stars/brovkin/webpack-frontend-template.svg?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/brovkin/webpack-frontend-template.svg?style=social)

## Особенности сборки

* используется [Babel](https://babeljs.io/) для поддержки современного JavaScript (ES6) в браузерах
* выбираете любой препроцессор SASS/SCSS/LESS
* ваш CSS и JS оптимизируется и минифицируется
* установлен пакет webpack-dev-server - вам не потребуется постоянно перезагружать браузер
* поддержка [TypeScript](https://www.typescriptlang.org/)
* анализ вашего бандла с помощью пакета [webpack-bundle-analyzer](https://www.npmjs.com/package/webpack-bundle-analyzer) | команда ```npm run stats```
* [ESlint](https://eslint.org/) позволит сделать ваш код приятным и чистым
* Поддержка и чтение файлов CSV/XML, на выходе получаем массив данных

## Файловая структура

```
webpack-frontend-template
├── dist
├── src
│   ├── assets
│       ├── fonts
│       └── images
│   ├── styles
│   ├── index.html
│   └── index.js
├── webpack.config.js
├── package.json
├── .gitignore
├── .eslintrc
└── .gitignore
```

> В зависимости от фреймворка, вы можете переделать организацию файлов в папке src т.к. обычно она отличается


## Команды

* ```npm run dev``` - собираем development
* ```npm run build``` - собираем production
* ```npm start``` - слежение за файлами и открываем в браузере
* ```npm run stats``` - смотрим размеры и статы бандла

## Установка

Установим все необходимые пакеты из package.json

```bash
npm install
```

Запускаем

```bash
npm start
```

## Связаться со мной

* ВКонтакте: [@artembrovkin](https://vk.com/artembrovkin)
* Instagram: [@brovkin_artem](https://www.instagram.com/brovkin_artem/)

## Сайт
### [brozabro.ru](https://brozabro.ru)


