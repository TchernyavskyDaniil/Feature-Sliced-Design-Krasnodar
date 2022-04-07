# Feature-Sliced-Krasnodar

## Описание

Представьте что ваше приложение это живой органзим. Любой организм подвержен старению. Чтобы сгладить углы мы должны ухаживать за ним. Уход должен быть комплексным. В мире разработки абсолютно так же. С годами наши проекты стареют. В мире фронтенда нет единого подхода к организации структуры проекта. Мало реальных примеров с жизнеспособной архитектурой. Каждый проект делают по внутренним стандартам компании и в итоге каждый раз надо вникать в архитектуру. К тому же, чаще всего она затачивается под конкретный фреймворк или библиотеку. Последствия не верного выбора архитектуры в проекте обычно выражаются в росте хаоса, беспорядка,как следствие - неустойчивость к изменениям. Я постараюсь рассказать вам про один стандартизированный подход - Feature Sliced. Но перед этим изучим популярные ошибки и подходы к их решению.

## Презентация


## Материалы

### Интересное по Feature Sliced

[Eslint-config, CRA-template, CLI и многое полезеное по FS](https://github.com/orgs/feature-sliced/repositories) 

[Про разделение хуков по смыслу](https://t.me/feature_sliced/11303)

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

[Про side effects free для Webpack, для Public API](https://webpack.js.org/guides/tree-shaking/#mark-the-file-as-side-effect-free)

### Минутка истории

[MV* - ui патерны](https://medium.com/you-gotta-get-schwifty/%D0%B0%D0%BB%D1%8C%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B9-%D0%B2%D0%B7%D0%B3%D0%BB%D1%8F%D0%B4-%D0%BD%D0%B0-mvc-mvp-%D0%B8-mvvm-389841cefa70)

[Чистая архитектура на фронтенде](https://bespoyasov.ru/blog/clean-architecture-on-frontend/)

[Еще немного про чистую архитектуру](https://medium.com/you-gotta-get-schwifty/%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0-ios-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-bfa03271cf35)

[Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/)

[Vertical Slices](https://jimmybogard.com/vertical-slice-architecture/)

[Еще про Vertical Slices](https://www.kenneth-truyers.net/2016/02/02/vertical-slices-in-asp-net-mvc/)

[Про декомпозиацию](https://feature-sliced.design/docs/get-started/cheatsheet)

### Примеры 

[Структура с Atomic Design](https://sova.dev/ru/application-structure/#1-struktura-feature)  

[Cardbox](https://github.com/cardbox/frontend)

[Github-client](https://github.com/ani-team/github-client/tree/workshop/feature-sliced-next)

[Sharead-frontend](https://github.com/select-name/sharead-frontend)

[Effector real world](https://github.com/mg901/effector-react-realworld-example-app/tree/master/src)

[Еще примеры из доки](https://feature-sliced.design/examples)

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

[Структура приложения от Sova](https://sova.dev/ru/application-structure/)

[Что такое бизнес логика](https://youtu.be/9DW-xdwjop8)

[Почему utils & helpers это свалка](https://sova.dev/ru/why-utils-and-helpers-is-a-dump/)

[Структура моделей Effector](https://sova.dev/ru/effector-model-structure/)
