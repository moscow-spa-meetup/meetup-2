# Moscow SPA Meetup №2

Первый [митап посвященный SPA](https://moscow-spa.timepad.ru/event/185632/) (Single Page Application), который прошел в Москве в офисе [Авито](https://www.avito.ru/), 23 апреля 2016 года.

*Видео-запись выступлений в обработке, появится позже*

## Упрощаем «жизнь» в большом проекте
 
*Константин Лебедев, Mail.ru*

Неважно какой фреймворк вы используете, внутри всё равно будет ваш уникальный код под проект, со своей структурой и логикой. Его нужно поддерживать, а коллегам нужно в него вникать. Как минимизировать порог вхождений и в целом облегчить поддержку проекта? Какие инструменты и подходы можно использовать, или сделать самому, для анализа, даже не кода, а проекта в целом? Константин поделится своим взглядом на этим вопросы и какие могут быть решения.

Слайды: [PDF](https://github.com/lahmatiy/moscow-spa-meetup-2/raw/master/pdf/make-life-easy.pdf)
 
## МРТ для данных
 
*Анастасия Горячева, Avito*

Человеческий мозг устроен сложно. А если с ним что-то не так в современной медицине используют магнитно-резонансный томограф.

Большие одностраничные приложения тоже устроены сложно. Чтобы их починить или обвесить новым функционалом, требуется вникнуть в их устройство. Для этого нередко приходится засучивать рукава и с головой погружаться в самые потроха проекта. И немалая часть проблем связана именно с бизнес логикой и потоками данных. Но что если у нас будет возможность проникнуть в структуру данных, способ увидеть связи между ними и отслеживать то, как они влияют друг на друга? Такой способ, чтобы не требовалось вскрытие черепной коробки, ну все как с МРТ.
Настя расскажет о собственных разработках в этой области.

Слайды: [HTML](http://www.slideshare.net/negoryacheva/avito-spa-meetup-2-61405477), [PDF](https://github.com/lahmatiy/moscow-spa-meetup-2/raw/master/pdf/make-life-easy.pdf)

## Чему можно научиться у Dart: переносим подходы из Dart и Angular2 в SPA на JavaScript
 
*Алексей Золотых, Wrike*

В своём докладе Алексей поделится опытом использования подходов из Dart и Angular 2 при разработке одностраничных приложений на JS. В частности, поговорим о Dependency injection, поиске ошибок с помощью Zone.JS, а также о потоках событий и асинхронном коде.

Слайды: [HTML](http://zolotyh.github.io/spa-pres/)

## Изоморфность без прикрас, или серверный рендеринг без Node.js

*Александр Зубов, Avito*

Сейчас никого не удивишь изоморфным приложением на react’е: node’a на сервере, react — на клиенте и все вроде бы хорошо. А что делать, если по каким-то причинам у вас нет возможности использовать node’у, а так нужен серверный рендеринг? Боль и страдания гарантированы… На самом деле, все не так плохо как кажется.

Слайды: [PDF](https://github.com/lahmatiy/moscow-spa-meetup-2/raw/master/pdf/server-side-rendering.pdf)

## CSSO — сжимаем CSS

*Роман Дворнов, Avito*

CSSO — инструмент для минификации CSS, который недавно вернулся к активной разработке. Зачем?

Дело в том, что минификация CSS — задача сложная. Сейчас нет идеального минификатора: чтобы и эффективным был, и делал все правильно. Ведь нужно учитывать не только особенности CSS, который постоянно меняется, но и уровень его поддержки браузерами, их баги, префиксы, хаки и т.д. Все это требует решения ряда непростых задач. Поговорим об этом, а также о принципах работы CSS-минификаторов, новых идеях и развитии CSSO.

Слайды: [HTML](http://www.slideshare.net/basisjs/csso-css-2), [PDF](https://github.com/lahmatiy/moscow-spa-meetup-2/raw/master/pdf/csso2.pdf)
