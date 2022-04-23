[Documentation](https://feature-sliced.design/)

[Github Feature-Sliced Design](https://github.com/feature-sliced)

[Telegram](https://t.me/feature_sliced)

[Twitter](https://twitter.com/feature_sliced)

## Описание

Представьте что ваше приложение это живой органзим. Любой организм подвержен старению. Чтобы сгладить углы мы должны ухаживать за ним. Уход должен быть комплексным. В мире разработки абсолютно так же. С годами наши проекты стареют. В мире фронтенда нет единого подхода к организации структуры проекта. Мало реальных примеров с жизнеспособной архитектурой. Каждый проект делают по внутренним стандартам компании и в итоге каждый раз надо вникать в архитектуру. К тому же, чаще всего она затачивается под конкретный фреймворк или библиотеку. Последствия не верного выбора архитектуры в проекте обычно выражаются в росте хаоса, беспорядка,как следствие - неустойчивость к изменениям. Я постараюсь рассказать вам про один стандартизированный подход - Feature-Sliced Design. Но перед этим изучим популярные ошибки и подходы к их решению.

## Презентация

Soon

## Материалы

## Доклады по FSD

Я бы очень советовал посмотреть этот доклад:

[Доклад: FSD — Архитектура Frontend проектов / Илья Азин](https://youtu.be/TFA6zRO_Cl0)

[Презентация](https://docs.google.com/presentation/d/1OKtAOP4pQ0IZXyEHx0_L1jrOL_-m8Fyxuq_Cw13UxkA/edit#slide=id.p1)

[Более свежая презентация, но без видосика, с закрытого выступления, Илья разрешил 👀](https://docs.google.com/presentation/d/1cTc0zYo96ftm0Ins8pWMqBE0PCzct8f_xiWbAgngILM/edit#slide=id.p1)

### Интересное по FSD

[Awesome Resources](https://feature-sliced.design/docs/community/awesome)

[Eslint-config, CRA-template, CLI и многое полезеное по FSD](https://github.com/orgs/feature-sliced/repositories) 

[Про разделение хуков по смыслу](https://t.me/feature_sliced/11303)

[Мифический слой Processes](https://github.com/feature-sliced/documentation/discussions/386)

[Про shared/api](https://t.me/feature_sliced/11340)

[Еще про shared/api](https://t.me/feature_sliced/4021)

[Про shared segments, assets и тд](https://github.com/feature-sliced/documentation/discussions/397#discussioncomment-1869420)

[Немного про UI](https://t.me/feature_sliced/17428)

[Про модалки](https://t.me/feature_sliced/10987)

[Про React hooks](https://github.com/feature-sliced/documentation/discussions/380)

[Где располагать Layout (Header/Footer/...)](https://t.me/feature_sliced/10960)

[Немного про Redux](https://t.me/feature_sliced/3881)

[Еще про Redux](https://github.com/feature-sliced/documentation/discussions/385)

[Про бизнес - сущность](https://t.me/feature_sliced/12779)  

[Entities vs Features vs ...](https://github.com/feature-sliced/documentation/discussions/373#discussioncomment-1869448)  

[Формулировка определения "Feature"](https://github.com/feature-sliced/documentation/discussions/23#discussioncomment-451017)

[Еще немного про Слои](https://t.me/feature_sliced/17686)

[Интересное про Public API](https://github.com/feature-sliced/documentation/discussions/427)

[Public API, Антихрупкость или все же Усточивость](https://github.com/feature-sliced/documentation/issues/227)

[Про side effects free для Webpack, для Public API](https://webpack.js.org/guides/tree-shaking/#mark-the-file-as-side-effect-free)

[FSD Angular разбор](https://github.com/feature-sliced/examples/discussions/17)

[FSD Vue разбор](https://github.com/EliseyMartynov/fs-vue/discussions/2)

[FSD NextJs разбор](https://github.com/feature-sliced/documentation/discussions/382)

[Про импорты](https://github.com/feature-sliced/documentation/discussions/52)

[Про тришейкинг ре-экспортов](https://t.me/feature_sliced/4247), 
[Side effects free](https://webpack.js.org/guides/tree-shaking/#mark-the-file-as-side-effect-free)

[model vs store vs ...](https://github.com/feature-sliced/documentation/discussions/68)

[Decompose Github](https://github.com/feature-sliced/documentation/blob/master/static/img/decompose-github.jpg)
[Decompose Twitter](https://github.com/feature-sliced/documentation/blob/master/static/img/decompose-twitter.png)

### Про подходы к архитектуре (в приоритете с оглядкой на Frontend)

[MV* - ui патерны](https://medium.com/you-gotta-get-schwifty/%D0%B0%D0%BB%D1%8C%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B9-%D0%B2%D0%B7%D0%B3%D0%BB%D1%8F%D0%B4-%D0%BD%D0%B0-mvc-mvp-%D0%B8-mvvm-389841cefa70)

[Чистая архитектура на фронтенде](https://bespoyasov.ru/blog/clean-architecture-on-frontend/)

[Еще немного про чистую архитектуру](https://medium.com/you-gotta-get-schwifty/%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0-ios-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-bfa03271cf35)

[Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/)

[Atomic Design: What is it and why is it important in 2022?](https://youtu.be/Yi-A20x2dcA)

[Vertical Slices](https://jimmybogard.com/vertical-slice-architecture/)

[Еще про Vertical Slices](https://www.kenneth-truyers.net/2016/02/02/vertical-slices-in-asp-net-mvc/)

[Solid OCP](https://ota-solid.vercel.app/ocp)

[Feature Driven Architecture - Oleg Isonen](https://youtu.be/BWAeYuWFHhs)

[Live-coding: Чистая архитектура во фронтенде / Александр Беспоясов](https://youtu.be/h4WQRqNjmX0)

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
[Бонус](https://github.com/feature-sliced/documentation/discussions/373#discussioncomment-1971208)

[С легаси](https://feature-sliced.design/docs/guides/migration/from-legacy)
         
#### Что пригодится

[FSD Eslint - config (Beta)](https://github.com/feature-sliced/eslint-config)

[Webpack Circular Dependency Plugin](https://github.com/aackerman/circular-dependency-plugin#basic-usage) - Судя по ишью, не подойдет для 5 версии вебпака  
[Dpdm](https://github.com/acrazing/dpdm) - Статический анализ зависимостей

[Eslint no-cycle](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-cycle.md)

[Dependency Cruiser](https://github.com/sverweij/dependency-cruiser)

[eslint-plugin-boundaries](https://github.com/javierbrea/eslint-plugin-boundaries)  

На выбор по импорт сортировке:

[import-sort](https://github.com/benmosher/eslint-plugin-import/blob/master/docs/rules/order.md)  
[sort-imports](https://eslint.org/docs/4.0.0/rules/sort-imports)  

Plant UML:    

[WS](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)

[VSCode](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

## Остальное

[Youtube Feature-Sliced Design](https://www.youtube.com/channel/UCkng_PHLatpDKPOIKfI731A/featured)

[Нужна ли методология?](https://github.com/feature-sliced/documentation/discussions/27)

[Про Feature Slices](https://t.me/feature_slices/2)

[Про декомпозицию и примеры](https://feature-sliced.design/docs/get-started/cheatsheet)

[Про Isolation](https://enterprisecraftsmanship.com/posts/cohesion-coupling-difference/)

[Структура приложения от Sova](https://sova.dev/ru/application-structure/)

[Что такое бизнес логика](https://youtu.be/9DW-xdwjop8)

[Почему utils & helpers это свалка](https://sova.dev/ru/why-utils-and-helpers-is-a-dump/)

[Структура моделей Effector](https://sova.dev/ru/effector-model-structure/)

[Tight Coupling Vs Loose Coupling](https://youtu.be/ifufbHjIQCo)

[Low Coupling and High Cohesion](https://medium.com/german-gorelkin/low-coupling-high-cohesion-d36369fb1be9)
