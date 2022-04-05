# Feature-Sliced-Krasnodar

## Описание

         Представьте что ваше приложение это живой органзим. Любой организм подвержен старению. Чтобы сгладить углы мы должны ухаживать за ним. Уход должен быть комплексным. В мире разработки абсолютно так же. С годами наши проекты стареют. В мире фронтенда нет единого подхода к организации структуры проекта. Мало реальных примеров с жизнеспособной архитектурой. Каждый проект делают по внутренним стандартам компании и в итоге каждый раз надо вникать в архитектуру. К тому же, чаще всего она затачивается под конкретный фреймворк или библиотеку. Последствия не верного выбора архитектуры в проекте обычно выражаются в росте хаоса, беспорядка,как следствие - неустойчивость к изменениям. Я постараюсь рассказать вам про один стандартизированный подход - Feature Sliced. Но перед этим изучим популярные ошибки и подходы к их решению.

## Презентация


## Материалы

### Интересное по Feature Sliced

[Мифический слой Processes](https://github.com/feature-sliced/documentation/discussions/386)

[Про shared/api](https://t.me/feature_sliced/11340)

[Еще про shared/api](https://t.me/feature_sliced/4021)

[Про shared segments, assets и тд](https://github.com/feature-sliced/documentation/discussions/397#discussioncomment-1869420)

[Про модалки](https://t.me/feature_sliced/10987)

[Где располагать Layout (Header/Footer/...)](https://t.me/feature_sliced/10960)

[Немного про Redux](https://t.me/feature_sliced/3881)

[Еще про Redux](https://github.com/feature-sliced/documentation/discussions/385)

[Про бизнес - сущность](https://t.me/feature_sliced/12779)  

[Entities vs Features vs ...](https://github.com/feature-sliced/documentation/discussions/373#discussioncomment-1869448)  

[Формулировка определения "Feature"](https://github.com/feature-sliced/documentation/discussions/23#discussioncomment-451017)

### Минутка истории

[Vertical Slices](https://jimmybogard.com/vertical-slice-architecture/)

[Еще про Vertical Slices](https://www.kenneth-truyers.net/2016/02/02/vertical-slices-in-asp-net-mvc/)

### Примеры 

[Структура с Atomic Design](https://sova.dev/ru/application-structure/#1-struktura-feature)  

[Cardbox](https://github.com/cardbox/frontend)

[Github-client](https://github.com/ani-team/github-client/tree/workshop/feature-sliced-next)

[Sharead-frontend](https://github.com/select-name/sharead-frontend)

[Effector real world](https://github.com/mg901/effector-react-realworld-example-app/tree/master/src)

### Про миграцию/рефакторинг

[Доклад Ильи Климова про бесконечный рефакторинг](https://youtu.be/aOiJ3k2UvO4)  

[Тред](https://t.me/feature_sliced/13500)

[С легаси](https://feature-sliced.design/docs/guides/migration/from-legacy)
         
#### Что пригодится

[Webpack Circular Dependency Plugin](https://github.com/aackerman/circular-dependency-plugin#basic-usage) - Судя по ишью, не подойдет для 5 версии вебпака  
[Dpdm](https://github.com/acrazing/dpdm) - Статический анализ зависимостей

[Eslint no-cycle](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-cycle.md)

[Dependency Cruiser](https://github.com/sverweij/dependency-cruiser)

Plant UML:    

[WS](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)

[VSCode](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

## Остальное

[Что такое бизнес логика](https://youtu.be/9DW-xdwjop8)

[Почему utils & helpers это свалка](https://sova.dev/ru/why-utils-and-helpers-is-a-dump/)
