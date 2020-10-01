# Список классных программ для 1С [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

`proposal of the list to for the 1C Enterprise platform (1c-dn.com), will be in Russian right now`

> todo - сделать оглавление автоматизировано

перед добавлением своей программы в список пожалуйста изучите

* [Инструкцию по добавлению](CONTRIBUTING.md)
* [Критерии качества добавляемого приложения](CONTRIBUTING.md)

## Официальные репозитории компании 1С

* [DirectBank (прямой обмен с банком) – технология системы "1С:Предприятие 8"](https://github.com/1C-Company/DirectBank) - 
* [Пример конфигурации для EDT](https://github.com/1C-Company/dt-demo-configuration)
* [Пример плагина для EDT](https://github.com/1C-Company/dt-example-plugins)
* [1С:ГитКонвертер - односторонняя синхронизация хранилища конфигураций 1С в репозиторий Git](https://github.com/1C-Company/GitConverter)


## Примеры интеграций 1C и <что-то>

* [1C и Slack](https://github.com/pbazeliuk/1C-Slack)
* [1C и HipChat](https://github.com/pbazeliuk/1C-HipChat)
* [1C и CropIO](https://github.com/cropio/cropio-1c)
* [1C и WooCommerce](https://github.com/sgtpep/woocommerce-1c)
* [1C и Redmine](https://github.com/SmokyAce/integration-1c-redmine)
* [1C и PricePlan](https://github.com/linskiy/priceplan_1C/) 
* [1C и HBCI](https://github.com/pintov/1c-fints)
* [1C и Google Analytics](https://github.com/infosoft-v/GA_SAMPLE)

## Контроль качества разработки

* [Automation Driven Development](https://github.com/silverbulleters/add) - ADD для 1C (BDD&TDD&etc)
* [xUnitFor1C](https://github.com/xDrivenDevelopment/xUnitFor1C) - TDD для 1С
* [Tester](https://github.com/grumagargler/CommonTests) - Почти SpecLog для 1С

## Библиотеки и утилиты для работы

* [Инструменты разработчика от tormozIT](https://github.com/tormozit/1C-Runtime-Developer-Tools) - инструменты разработчика (дай бог здоровья автору)
* [Local Compile Utils](https://github.com/silverbulleters/vanessa-runner) - скрипты для локальной сборки "за один шаг"
* [v8unpack](https://github.com/dmpas/v8unpack/tree/v.3.0) - утилита С++ для работы с бинарными файлами 1С
* [oscript-library](https://github.com/EvilBeaver/oscript-library) - полезные библиотеки на 1Script
* [Tool1CD](https://bitbucket.org/awa15/tool_1cd/) - консольная и GUI утилита для работы с DT файлами
* [PreCommit Hook for EPF, ERF](https://github.com/xDrivenDevelopment/precommit1c) - поддержка возможности работы с EPF внутри git репозиториев через "перехваты git"
* [Password Changer](https://github.com/alekseybochkov/PasswordChanger1C) - утилита для исправления чужих ошибок ;-)
* [V8PasswordEjector](https://github.com/YPermitin/V8PasswordEjector) - Сброс учетных записей для 1С:Предприятия 8.x
* [One DT Tools](https://github.com/Infactum/onec_dtools) - python библоитека для работы с бинарными файлами
* [Консоль запросов + БИТ:Финанс](https://github.com/CryptedSky/QueryConsolePBF) - работа с источниками данных БИТ:Финанс
* [V8Formats](https://github.com/YPermitin/V8Formats) - Библиотеки на .NET для работы с форматами файлов платформы 1С:Предприятие 8.x


## DevOps

* [1C GitLab CI](https://github.com/nixel2007/gitlab-ci-for-1c) - скрипты для работы с GitLab CI и 1С
* [OneC Docker](https://github.com/VanessaDockers/onecdocker) - Vagrant машина разработчика 1С
* [OScript](https://github.com/EvilBeaver/OneScript) - интерепретатор 1С языка для написания скриптов
* [OneWS](https://github.com/crsde/one-ws) - docker контейнер для Web адаптеров (в связи с выходом 8.4 актуальность падает)
* [OneWSAP](https://github.com/crsde/one-wsap) - docker контейнер для Web адаптеров под Apache 2.4, поддерживает масштабирование + HAProxy
* [PostgreSQL для 1С (сборка под Windows)](https://github.com/postgrespro/pgwininstall) - репозиторий для автоматизированной сборки PostgreSQL для 1С из исходников
* [PostgreSQL для 1С (сборка под Vagrant+Docker)](https://github.com/VanessaDockers/pgsteroids) - виртуальная машина для использования на разработческих контурах в связке с мини-сервером 1С
* [LogStash для 1С Sqlite](https://github.com/silverbulleters-research/logstash-vanessa-sqlitelogs) - плагин для LogStash для инкрементальной выгрузки журналов регистрации 1С в ElasticSearch
* [TaskManagerFor1C](https://github.com/wizi4d/TaskManagerFor1C) - инструмент для создания параллельных алгоритмов с гарантированным выполнением в среде 1С Предприятия 

## Подсветка синтаксиса и пакеты для редакторов

* [1C Syntax Highlight](https://github.com/xDrivenDevelopment/1c-syntax) - поддержка 1С в редакторах Atom, VSC, Sublime
* [GitLab Syntax Highlight](https://github.com/karnilaev/1c-syntax-for-GitLab) - подсветка синтаксиса 1С для GitLab Server
* [Vim Syntax Highlight](https://github.com/andreevlex/vim-language-1c-bsl) - поддержка 1С в редакторе Vim

## Внешние компоненты

* [Small Wrapper AddIn 1C](https://github.com/tapapax/Addin1C) - пример работы с Native API
* [BROM-Asterisk-Native](https://github.com/shachneff/BROM-Asterisk-Native) - Открытая, работающая в 1С >= 8.3.6 версия компоненты ROM-Asterisk-Native от Simplit
* [Template for 1C:Enterprise add-in](https://github.com/gnusi/AddInNativeTemplate) - Шаблон внешней компоненты. Сборка с помощью CMake
* [FPNativeAPI](https://github.com/Zawullon/fpnativeapi) - пример Native API расширения для 1С на FreePascal/Lazarus
* [RegEx1CAddin](https://github.com/alexkmbk/RegEx1CAddin) - Внешняя Native API компонента для выполнения регулярных выражений на платформе 1С:Предприятие 8

## Фреймворки для интеграции с 1С

* [Metadata.JS](https://github.com/oknosoft/metadata.js)
* [Транслятор запросов и Linq-провайдер для 1С](https://github.com/gusev-p/simple-1c)

## OScript интересное

* [SQL запросы на OScript](https://github.com/ret-Phoenix/oscript-sql) - внешняя компонента реализующая возможность работы с базами данных из onescript.

## Курсы, книги и примеры

* [Управление небольшой фирмой](https://github.com/eetk/1c-management-small-firm) - документация по УНФ

### Потенциально интересное (без категорий)

**Ручной поиск**

* https://github.com/purtcer/NurseConsole1CServer
* https://github.com/TeamBIOS/cfg_tools
* https://github.com/EnterraInc/1C-.Net-Adapter
* https://github.com/tarasii/1c_rs232
* https://github.com/deshaion/service_for_connect_1c_com
* https://github.com/alekseybochkov/WebRAS
* https://github.com/vladon/SocketNative
* https://github.com/pbazeliuk/V8Commit
* https://github.com/antioff/afalina
* https://github.com/skyksandr/1c-log-to-es
* https://github.com/ANtlord/price-import-1c
* https://github.com/1CEnterprise/MSQL-for-1C
* https://github.com/asdaru/postgres_1c
* https://github.com/SergeFocus/1C-Functin-to-yEd
* https://github.com/pintov/1c-jwt
* https://github.com/goshulina/auto_act_1c

**Автоматический поиск**

[Данные согласно поиску GitHub](data/README.md)

[Инструкция по скриптам поиска](tools/README.md)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
