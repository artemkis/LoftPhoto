## Javascript Boilerplate
Универсальная сборка, позволяющая писать код на современном ES (Javascript) и TypeScript

## Что внутри
- полностью настроенная конфигурация для webpack 5 + babel 7 + typescript
- prettier + eslint - чтобы не заботиться о code-style
- jest - чтобы писать тесты

## Как работает приложение LoftPhoto
Суть мобильного приложения LoftPhoto заключается в том, что бы отправляеть запросы на сервер в VK и получать список всех друзей того человека, от которого эти запрсы исходят. Далее рандомным образом выбирается случайная фотография случайного друга и устанавливается как фотография на фон приложения при помощи CSS-свойства background-image. Этой фотографии мы можем ставить лайки или оставлять комментарии. Приложение имеет свой внутренний сервер для хранения лайков и написания комментариев.

## Как запустить приложение
- чтобы начать отправлять запросы на сервер в VK, нужно зарегистрировать приложение в разделе разработчика и получить api id.
- установить все npm пакеты командой `npm i`
- запустить внутренний сервер командой `node projects/loft-photo/server`
- запустить приложение командой `npm start`
- откройте `http://localhost:8080/loft-photo` и пользуйтесь приложением с удовольствием
