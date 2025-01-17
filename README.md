# BlockVote: Децентрализованная система голосования

### Система голосования на блокчейне Substrate

## Описание проекта

Проект представляет собой децентрализованное приложение (dApp) для организации голосований с использованием блокчейна Substrate. Основная идея — создать простую систему, в которой пользователи могут предлагать свои вопросы для голосования и голосовать за них.

## Основные функции

- **Регистрация пользователей**: Каждый пользователь может зарегистрировать уникальную учетную запись через интерфейс dApp. Для этого используется встроенный в Substrate модуль управления учетными записями.

- **Создание голосований**: Зарегистрированные пользователи могут создавать новые голосования, задавая вопрос и варианты ответов (например, "Да" или "Нет"). Каждое голосование записывается в блокчейн и получает уникальный идентификатор.

- **Голосование**: Пользователи могут голосовать за предложенные варианты ответов. Каждое голосование записывается в блокчейн, что обеспечивает прозрачность и невозможность изменения данных задним числом.

- **Подсчет голосов**: В любой момент можно получить текущее состояние голосования — количество голосов за каждый вариант. Подсчет голосов происходит автоматически и данные доступны в блокчейне для всех участников.

- **Просмотр истории голосований**: Любой пользователь может просмотреть историю предыдущих голосований, включая вопросы, варианты ответов и результаты.

## Особенности

- **Прозрачность**: Все голосования и их результаты хранятся в блокчейне, что делает систему прозрачной и надежной.

- **Децентрализация**: Проект не требует центрального сервера или администраторов, вся логика работы обеспечивается с помощью блокчейна Substrate.

- **Простота интерфейса**: Для взаимодействия с блокчейном создается простой веб-интерфейс на React или Vue.js, который позволяет пользователям легко создавать и участвовать в голосованиях.

## Технологии

- **Substrate**: Для разработки блокчейна и всей логики работы системы голосования.

- **Polkadot.js**: Для взаимодействия фронтенда с блокчейном через браузер.

- **React или Vue.js**: Для создания пользовательского интерфейса.

## Фронтенд

Фронтенд отвечает за взаимодействие пользователя с блокчейном и предоставляет интерфейс для выполнения основных операций:

- **Регистрация пользователей.**
- **Создание новых голосований.**
- **Голосование.**
- **Просмотр результатов и истории голосований.**

## Substrate блокчейн

Блокчейн на основе Substrate играет роль децентрализованного хранилища и выполняет логику управления голосованиями. Вся важная информация (вопросы голосований, голоса пользователей, результаты) сохраняется в блокчейне, что обеспечивает прозрачность и неизменность данных.
