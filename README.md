# Выбор решения
Мы выбрали Module Federation для реализщации микрофронтедов. В командах уже была экспертиза использования данного фреймворка. А также он позволяет переиспользовать разные версии зависимостей. В будущем, возможно, некоторые команды будут изолированы и смогут выбирать стек самостоятельно.

# Структура проекта

├── src
│   ├── controller
│   │   ├── **/*.css
│   ├── views
│   ├── model
│   ├── index.js
├── public
│   ├── css
│   │   ├── **/*.css
│   ├── images
│   ├── js
│   ├── index.html
├── dist (or build
├── node_modules
├── package.json
├── package-lock.json
└── .gitignore