# Пример из библиотеки maxGRAF
Простой пример проверки работоспособности и запуска на openServer
## Setup

Качаем все зависимости и сам node js
> Из корневой директории проекта качаем maxGraf `npm install @maxgraph/core`.




## Запуск
Если надо просто запустить на отдельном веб сервере в node то все просто пишем `npm run dev` в корневой директории проект и отправляеемся на http://localhost:8080/

А теперь если нам надо забилдить наш проект для запуска на других веб сервера то пишем `npm run build` и затем можно его запустить командой `npm run preview`.

Для запуска на OpenServer нам понадобится взять папу `dist` из корня проекта и это есть наш сайт. 
