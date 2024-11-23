# Роли пользователей

- **Создатель проекта** - Может создавать проект, может добавлять людей в проект, может создавать задачи, может редактировать задачи, может изменять статус задачи (все права внутри проекта)

- **Член проекта редактор (исполнитель)** - Может просматривать список задач в проект, может просматривать карточку задачи, может редактировать задачи, может изменять статус задачи, может оставлять комментарии в задаче.

- **Член проекта просмотр** - Может просматривать список задач в проект, может просматривать карточку задачи, не может ничего редактировать

Любой из пользователей может создавать свой проект.

Любой из пользователей может получить роль “Создатель проекта“, в рамках своего созданного проекта.

# USER STORY

- Я, как пользователь (Любой), хочу авторизоваться, чтобы получить доступ к функционалу

- Я, как пользователь (Любой), хочу просматривать список задач на сегодня, чтобы знать, что я должен выполнить сегодня

- Я, как пользователь (Любой), хочу получать уведомления по напоминаниям из задач, чтобы не забывать о них

- Я, как пользователь (Любой), хочу просматривать настраивать свой профиль, чтобы менять Имя, Фамилию, пароль

- Я, как пользователь (Любой,) хочу просматривать список достижений, чтобы иметь мотивацию для выполнения задач

- Я, как пользователь (Любой), хочу просматривать свое расписание в ВУЗе, чтобы оценивать свое время

- Я, как пользователь (Любой), хочу изменять тему интерфейса (светлая/темная), чтобы работать в удобных условиях.

- Я, как пользователь (Любой), хочу видеть диаграмму прогресса выполнения задач в проекте, чтобы оценивать эффективность работы.

- Я, как пользователь (Любой), хочу включать/отключать уведомления для задач и комментариев, чтобы регулировать количество получаемой информации.

- Я, как пользователь (Создатель проекта), хочу создать проект, чтобы добавлять в него других пользователей

- Я, как пользователь (Создатель проекта), хочу создать проект, чтобы заводить в нем задачи для других пользователь

- Я, как пользователь (Создатель проекта), хочу создать задачу, чтобы назначить на нее исполнителя

- Я, как пользователь (Создатель проекта), хочу создавать задачу, чтобы устанавливать дату ее окончания

- Я, как пользователь (Создатель проекта), хочу создавать задачу, чтобы устанавливать дату ее напоминания

- Я, как пользователь (Создатель проекта), хочу создавать задачу, чтобы устанавливать ее приоритет

- Я, как пользователь (Создатель проекта), хочу устанавливать роли (Редактор или Просмотр) для участников, чтобы разделить зоны ответственности.

- Я, как пользователь (Создатель проекта), хочу удалять участников из проекта, чтобы управлять составом команды.

- Я, как пользователь (Создатель проекта, Редактор), хочу просматривать карточку задачи, чтобы менять ее описание

- Я, как пользователь (Создатель проекта, Редактор), хочу просматривать карточку задачи, чтобы менять ее статус

- Я, как пользователь (Создатель проекта, Редактор), хочу просматривать карточку задачи, чтобы добавлять в нее комментарий

- Я, как пользователь (Создатель проекта, Редактор), хочу просматривать карточку задачи, чтобы менять ее приоритет

- Я, как пользователь (Создатель проекта, Редактор, Просмотр), хочу фильтровать задачи по приоритету, чтобы сосредоточиться на более важных задачах.

- Я, как пользователь (Создатель проекта, Редактор, Просмотр), хочу просматривать карточку задачи, чтобы просматривать ее описание

- Я, как пользователь (Создатель проекта, Редактор, Просмотр), хочу просматривать карточку задачи, чтобы просматривать статус задачи

- Я, как пользователь (Создатель проекта, Редактор, Просмотр), хочу просматривать карточку задачи, чтобы просматривать комментарии к задаче

- Я, как пользователь (Создатель проекта, Редактор, Просмотр), хочу просматривать список задач, чтобы видеть даты окончания задач

- Я, как пользователь (Создатель проекта, Редактор, Просмотр), хочу просматривать список задач, чтобы видеть даты окончания задач

# USE CASE

Open plant-1.png

![blob:https://antonbaturin2003.atlassian.net/b7fd0604-3f90-43cd-ba4c-21c3c0753ecc#media-blob-url=true&id=88a8cda4-46d0-445a-ab5a-f4b97b883a60&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=plant-1.png&size=33117&width=1289&height=344&alt=plant-1.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/b7fd0604-3f90-43cd-ba4c-21c3c0753ecc#media-blob-url=true+id=88a8cda4-46d0-445a-ab5a-f4b97b883a60+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=plant-1.png+size=33117+width=1289+height=344+alt=plant-1.png)

Open plant.png

![blob:https://antonbaturin2003.atlassian.net/9412a6a2-72c7-4cc7-a1d5-44a4dcf09b2c#media-blob-url=true&id=0be844a0-c376-4225-a9b2-3766812a9dd6&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=plant.png&size=47727&width=2466&height=234&alt=plant.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/9412a6a2-72c7-4cc7-a1d5-44a4dcf09b2c#media-blob-url=true+id=0be844a0-c376-4225-a9b2-3766812a9dd6+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=plant.png+size=47727+width=2466+height=234+alt=plant.png)

Open plant-2.png

![blob:https://antonbaturin2003.atlassian.net/4f9db678-2fc5-40fe-830d-f36960af5dbe#media-blob-url=true&id=cd84c11f-fb4a-48fb-bbf1-8bb479d2f2c4&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=plant-2.png&size=57542&width=1978&height=345&alt=plant-2.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/4f9db678-2fc5-40fe-830d-f36960af5dbe#media-blob-url=true+id=cd84c11f-fb4a-48fb-bbf1-8bb479d2f2c4+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=plant-2.png+size=57542+width=1978+height=345+alt=plant-2.png)

Код на Plant UML



# План реализации

## Изменение темы

У пользователя есть возможность менять тему на Светлую, Темную или Системную

Open image-20241123-153831.png

![blob:https://antonbaturin2003.atlassian.net/e98184fd-2e19-42d6-9688-5d231f3fc5bf#media-blob-url=true&id=d2aa9d32-0514-4b86-a4e3-074ad0a60472&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-153831.png&size=13140&width=155&height=156&alt=image-20241123-153831.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/e98184fd-2e19-42d6-9688-5d231f3fc5bf#media-blob-url=true+id=d2aa9d32-0514-4b86-a4e3-074ad0a60472+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-153831.png+size=13140+width=155+height=156+alt=image-20241123-153831.png)

## **Авторизация**

### Макет:

Open Авторизация.png

![blob:https://antonbaturin2003.atlassian.net/635d2c8a-f93b-4c78-b443-d8ab3162b598#media-blob-url=true&id=7f8bd035-dbe4-4a95-b25e-a4cdd2a60c2c&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.png&size=172981&width=917&height=626&alt=%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/635d2c8a-f93b-4c78-b443-d8ab3162b598#media-blob-url=true+id=7f8bd035-dbe4-4a95-b25e-a4cdd2a60c2c+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.png+size=172981+width=917+height=626+alt=%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.png)

### Описание элементов:

|||||
|-|-|-|-|
|**№**|**Название элемента**|**Тип поля**|**Описание элемента**|
|1||Иконка|При нажатии на иконку форма закрывается|
|2|Авторизация|RadioButton|При нажатии на RadioButton открывается вкладка авторизации, где пользователь может ввести email и пароль для входа в аккаунт|
|3|Регистрация|RadioButton|При нажатии на RadioButton открывается вкладка регистрации, где пользователь может зарегистрировать свой аккаунт|
|4|Email|Текст
Поле ввода
Обязательное|Поле для ввода email|
|5|Пароль|Текст
Поле ввода
Обязательное|Поле для ввода пароля. При вводе пароля скрываем символы, которые вводит пользователь|
    ![blob:https://antonbaturin2003.atlassian.net/bdf8670a-4516-4d4e-b561-f3430e8c2da0#media-blob-url=true&id=16618ef1-fd2a-4e63-9454-c0bfa9887b79&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-120631.png&size=46683&width=556&height=432&alt=image-20241123-120631.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/bdf8670a-4516-4d4e-b561-f3430e8c2da0#media-blob-url=true+id=16618ef1-fd2a-4e63-9454-c0bfa9887b79+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-120631.png+size=46683+width=556+height=432+alt=image-20241123-120631.png)

## **Регистрация**

### Макет:

Open Регистрация.png

![blob:https://antonbaturin2003.atlassian.net/66a2b2de-e5cd-4dc9-b4d4-c92be539e793#media-blob-url=true&id=b0a5d27b-a5df-42dd-aac0-2047fe286e6c&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png&size=290492&width=901&height=952&alt=%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/66a2b2de-e5cd-4dc9-b4d4-c92be539e793#media-blob-url=true+id=b0a5d27b-a5df-42dd-aac0-2047fe286e6c+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png+size=290492+width=901+height=952+alt=%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png)

### Описание элементов:

|||||
|-|-|-|-|
|**№**|**Название элемента**|**Тип поля**|**Описание элемента**|
|1||Иконка|При нажатии на иконку форма закрывается|
|2|Авторизация|RadioButton|При нажатии на RadioButton открывается вкладка авторизации, где пользователь может ввести email и пароль для входа в аккаунт|
|3|Регистрация|RadioButton|При нажатии на RadioButton открывается вкладка регистрации, где пользователь может зарегистрировать свой аккаунт.|
    ![blob:https://antonbaturin2003.atlassian.net/6535bd88-00f9-4a35-a5a8-78ef5b4ba07a#media-blob-url=true&id=a2a6afe2-216e-448a-8ba1-5c7d164678d1&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-122352.png&size=14681&width=537&height=131&alt=image-20241123-122352.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/6535bd88-00f9-4a35-a5a8-78ef5b4ba07a#media-blob-url=true+id=a2a6afe2-216e-448a-8ba1-5c7d164678d1+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-122352.png+size=14681+width=537+height=131+alt=image-20241123-122352.png)

    ![blob:https://antonbaturin2003.atlassian.net/ec6a7651-b79d-4fd7-b15c-225645553e7c#media-blob-url=true&id=931d7d22-5cd3-4921-9217-430c5c7d01e6&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-122456.png&size=33445&width=526&height=132&alt=image-20241123-122456.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/ec6a7651-b79d-4fd7-b15c-225645553e7c#media-blob-url=true+id=931d7d22-5cd3-4921-9217-430c5c7d01e6+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-122456.png+size=33445+width=526+height=132+alt=image-20241123-122456.png)

    ![blob:https://antonbaturin2003.atlassian.net/aa926760-110e-4c85-b565-d9e6b4f5c433#media-blob-url=true&id=cc21ea9c-db0f-4e6d-b58b-7ec0e43be93b&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-122610.png&size=24936&width=526&height=121&alt=image-20241123-122610.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/aa926760-110e-4c85-b565-d9e6b4f5c433#media-blob-url=true+id=cc21ea9c-db0f-4e6d-b58b-7ec0e43be93b+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-122610.png+size=24936+width=526+height=121+alt=image-20241123-122610.png)

|7|Подтвердите пароль|Текст
Поле ввода
Обязательное|Поле для ввода пароля, чтобы подтвердить ранее введенный пароль|
|8|Зарегистрироваться|Кнопка|При нажатии на кнопку пользователь регистрируется в системе. После нажатии кнопки форма закрывается.|

## Бокова панель

### Макет:

Open Боковая панель.png

![blob:https://antonbaturin2003.atlassian.net/f9416bd5-da36-4a44-9a54-3066b28ab4a7#media-blob-url=true&id=705db4b8-22e2-4678-9838-5cd94910bef9&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=%D0%91%D0%BE%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F%20%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C.png&size=364675&width=466&height=895&alt=%D0%91%D0%BE%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F%20%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/f9416bd5-da36-4a44-9a54-3066b28ab4a7#media-blob-url=true+id=705db4b8-22e2-4678-9838-5cd94910bef9+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=%D0%91%D0%BE%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F%20%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C.png+size=364675+width=466+height=895+alt=%D0%91%D0%BE%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F%20%D0%BF%D0%B0%D0%BD%D0%B5%D0%BB%D1%8C.png)

### Описание элементов:

![blob:https://antonbaturin2003.atlassian.net/784d233c-5838-4466-80e2-546cc7b051a7](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/784d233c-5838-4466-80e2-546cc7b051a7)

|||||
|-|-|-|-|
|**№**|**Название элемента**|**Тип поля**|**Описание элемента**|
|1||Рисунок|Хэдер боковой панели, в котором выводим Команду и Иконку “Центр-Инвеста“|
    ![blob:https://antonbaturin2003.atlassian.net/d01592ca-a2ab-482b-80e4-2b4d48b2a2e0#media-blob-url=true&id=7de7dcfc-e0cb-4cb7-99c0-f1d54b2b0211&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-143500.png&size=23545&width=197&height=204&alt=image-20241123-143500.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/d01592ca-a2ab-482b-80e4-2b4d48b2a2e0#media-blob-url=true+id=7de7dcfc-e0cb-4cb7-99c0-f1d54b2b0211+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-143500.png+size=23545+width=197+height=204+alt=image-20241123-143500.png)

    ![blob:https://antonbaturin2003.atlassian.net/52fb80f9-7e9d-4526-a624-41cf25a88d89#media-blob-url=true&id=d1d1f1a9-b49a-4add-9d65-a39de34b3757&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-153714.png&size=58905&width=387&height=204&alt=image-20241123-153714.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/52fb80f9-7e9d-4526-a624-41cf25a88d89#media-blob-url=true+id=d1d1f1a9-b49a-4add-9d65-a39de34b3757+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-153714.png+size=58905+width=387+height=204+alt=image-20241123-153714.png)

|4|Добавить задачу|Кнопка|При нажатии на кнопку открывается Поп-ап с созданием задачи - [CyberGarden 18 2024 | Добавить задачу](https://antonbaturin2003.atlassian.net/wiki/spaces/~6364bc70548f1fe6f0c869eb/pages/98328/CyberGarden+18+2024#%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%B8%D1%82%D1%8C-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D1%83)Данный элемент должен быть зеленого цвета и быть больше других элементов|
|5|Сегодня|Кнопка|Выводим все задачи созданные на сегодня. Данная страница открывается пользователю первой.|
|6|Расписание вуза|Кнопка|Выводим расписание ВУЗа ИКТИБ ЮФУ. API - [О сайте - ictis alex b](https://ictis.ru/about).|
|7|Достижения|Кнопка|Выводим список достижений. Сначала в списке выводим полученные достижения. Потом достижения, которые ближе к выполнению.|
|8|Проекты|Тест|Данная надпись является заголовком. Рядом с надписью есть знак +, который используется для создания нового проекта. Так же можно сворачивать разворачивать данный блок, при нажатии на >.|
|9||Иконка|При нажатии на иконку открывается Поп-ап создания проекта.|
|10|Название проекта|Кнопка|При нажатии на элемент выводится список задач, созданных в рамках данного проекта.Рядом с названием проекта есть иконка … При нажатии на иконку выводим кнопки:
 1. Редактировать - открывается заполненная форма создания задачи, которую можно изменить и сохранить
 2. Выполненные задачи - при нажатии на данный элемент открывается список задач в статусе “Готово“ в данном проекте
 3. Удалить - удалить проект|

## Добавить задачу

### Макет:

Open Добавление задачи.png

![blob:https://antonbaturin2003.atlassian.net/bf913f7f-7f0a-4ca9-b50a-ddb0f519f92f#media-blob-url=true&id=6bedc891-2a2a-432e-b45d-a40f475a3202&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8.png&size=117379&width=802&height=327&alt=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/bf913f7f-7f0a-4ca9-b50a-ddb0f519f92f#media-blob-url=true+id=6bedc891-2a2a-432e-b45d-a40f475a3202+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8.png+size=117379+width=802+height=327+alt=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8.png)

### Описание элементов:

При нажатии на кнопку создать задачу открывается Поп-ап в котором можно создать задачу.

|||||
|-|-|-|-|
|**№**|**Название элемента**|**Тип поля**|**Описание элемента**|
|1||Иконка|При нажатии на иконку форма закрывается|
|2|Название задачи|Поле ввода
Обязательное|В данном поле пользователь вводит название задачи.
Текст в данном поле должен быть больше, чем в поле “Описание задачи“|
|3|Описание задачи|Поле ввода
Необязательное|В данном поле пользователь вводит описание задачи. Поле должно шириной в 3 строчки. Если пользователь вводит более 3 строк, то поле расширяется.|
    ![blob:https://antonbaturin2003.atlassian.net/36cfd9b6-9c9f-45c9-b35c-2a13f0bb2e4f#media-blob-url=true&id=a4d1c688-128c-4f32-8245-5511b19676d1&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-145332.png&size=40453&width=291&height=333&alt=image-20241123-145332.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/36cfd9b6-9c9f-45c9-b35c-2a13f0bb2e4f#media-blob-url=true+id=a4d1c688-128c-4f32-8245-5511b19676d1+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-145332.png+size=40453+width=291+height=333+alt=image-20241123-145332.png)

    ![blob:https://antonbaturin2003.atlassian.net/7216ac75-8238-424e-9d10-5392e4e8f671#media-blob-url=true&id=26d0759b-a151-4839-a673-198e5f4675d6&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-145510.png&size=15794&width=125&height=178&alt=image-20241123-145510.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/7216ac75-8238-424e-9d10-5392e4e8f671#media-blob-url=true+id=26d0759b-a151-4839-a673-198e5f4675d6+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-145510.png+size=15794+width=125+height=178+alt=image-20241123-145510.png)

    ![blob:https://antonbaturin2003.atlassian.net/c5ced7d2-c744-4c26-8ee3-734a8bc341f4#media-blob-url=true&id=5b85791c-bedd-419c-9bbe-de27dfbf05f7&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-145810.png&size=32675&width=256&height=338&alt=image-20241123-145810.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/c5ced7d2-c744-4c26-8ee3-734a8bc341f4#media-blob-url=true+id=5b85791c-bedd-419c-9bbe-de27dfbf05f7+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-145810.png+size=32675+width=256+height=338+alt=image-20241123-145810.png)

    ![blob:https://antonbaturin2003.atlassian.net/29769bc0-9abf-4b65-8d2e-949ac63bb7d6#media-blob-url=true&id=468de51b-91f5-4cc0-8c1f-90a6ec7d8ba5&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-150712.png&size=25640&width=255&height=209&alt=image-20241123-150712.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/29769bc0-9abf-4b65-8d2e-949ac63bb7d6#media-blob-url=true+id=468de51b-91f5-4cc0-8c1f-90a6ec7d8ba5+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-150712.png+size=25640+width=255+height=209+alt=image-20241123-150712.png)

    ![blob:https://antonbaturin2003.atlassian.net/a76db164-7cfa-4cf8-a4b0-da67cd257796#media-blob-url=true&id=c0a3077e-df85-44cc-a6a8-c4e027001caf&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-150744.png&size=40624&width=255&height=266&alt=image-20241123-150744.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/a76db164-7cfa-4cf8-a4b0-da67cd257796#media-blob-url=true+id=c0a3077e-df85-44cc-a6a8-c4e027001caf+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-150744.png+size=40624+width=255+height=266+alt=image-20241123-150744.png)

|9|Отмена|Кнопка|При нажатии на кнопку происходит отмена создания события|
|10|Добавить задачу|Кнопка|При нажатии на кнопку создается задача. После создания задача должна появится в списке задач|

## **Создание проекта**

### Макет:

Open Добавление проекта.png

![blob:https://antonbaturin2003.atlassian.net/a270dc1f-cea5-4ed6-af70-5d258595c39c#media-blob-url=true&id=0e03a3f7-f509-4458-9592-2cdc7f1fc311&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0.png&size=115888&width=494&height=321&alt=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/a270dc1f-cea5-4ed6-af70-5d258595c39c#media-blob-url=true+id=0e03a3f7-f509-4458-9592-2cdc7f1fc311+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0.png+size=115888+width=494+height=321+alt=%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0.png)

### Описание элементов:

При нажатии на + рядом с Проект ([CyberGarden 18 2024 | 0a0d0f21 a8f5 40d5 a925 b11792572586](https://antonbaturin2003.atlassian.net/wiki/spaces/~6364bc70548f1fe6f0c869eb/pages/98328#0a0d0f21-a8f5-40d5-a925-b11792572586) ) открывается Поп-ап с созданием проекта.

|||||
|-|-|-|-|
|**№**|**Название элемента**|**Тип поля**|**Описание элемента**|
|1||Иконка|При нажатии на иконку форма закрывается|
|2|Добавить проект|Текст|Данная надпись является заголовком|
|3|Имя проекта|Текст
Поле ввода
Обязательное|В данном поле пользователь вводит название (имя) проекта|
    ![blob:https://antonbaturin2003.atlassian.net/4d9afc2b-37c9-433d-95eb-5e186d6eca84#media-blob-url=true&id=f6c1768d-e5f8-4388-b187-2aebe48e0d76&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image%2010.png&size=98432&width=425&height=656&alt=image%2010.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/4d9afc2b-37c9-433d-95eb-5e186d6eca84#media-blob-url=true+id=f6c1768d-e5f8-4388-b187-2aebe48e0d76+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image%2010.png+size=98432+width=425+height=656+alt=image%2010.png)

|5|Отмена|Кнопка|При нажатии на кнопку происходит отмена создания проекта|
|6|Добавить|Кнопка|При нажатии на кнопку создается задача. После создания задача должна появится в списке проектов|

1. **Список задач | Проект**

Заголовок - Название проекта

Ниже выводим количество задач, которое есть в списке

Выводим список задач по датам. С возможностью создать задачу в данную дату

**При нажатии на чекбокс (можно выбирать несколько чекбоксов разом) появляется кнопка “Закрыть задачи“ рядом с Заголовком (Название проекта). При нажатии на кнопку открывается поп-ап. Заголовок - Закрыть задачу. Две кнопки - Да / Нет.**

Пример:

Open image-20241122-225446.png

![blob:https://antonbaturin2003.atlassian.net/3a591129-736a-4e11-a613-fffaf3e21462#media-blob-url=true&id=3baea36f-2319-4483-8d8b-2b45e504e954&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241122-225446.png&size=6956&width=811&height=138&alt=image-20241122-225446.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/3a591129-736a-4e11-a613-fffaf3e21462#media-blob-url=true+id=3baea36f-2319-4483-8d8b-2b45e504e954+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241122-225446.png+size=6956+width=811+height=138+alt=image-20241122-225446.png)

Задачи в списке выводятся согласно их приоритетам. Задачи с высшим приоритетом выводятся выше. Если у задач одинаковый приоритет, то выводим согласно алфавиту от А-Я.

В списке задач, на каждой строчке задачи выводится исполнитель.

Рядом с название задачи выводим Выпадающий список с моновыбором статусов задачи. Возможность изменять статус есть у Создателя проекта и Редактора.

1. **Список задач | Сегодня**

Заголовок - Сегодня

Ниже выводим количество задач, которое есть в списке

Выводим список задач по датам.

**При нажатии на чекбокс (можно выбирать несколько чекбоксов разом) появляется кнопка “Закрыть задачи“ рядом с Заголовком (Название проекта). При нажатии на кнопку открывается поп-ап. Заголовок - Закрыть задачу. Две кнопки - Да / Нет.**

Open image-20241123-002845.png

![blob:https://antonbaturin2003.atlassian.net/017962f6-f0d7-433f-925d-3fcc23d3ec68#media-blob-url=true&id=b739f74c-5fb0-4544-a9f0-83e11d04ea30&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-002845.png&size=5292&width=845&height=107&alt=image-20241123-002845.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/017962f6-f0d7-433f-925d-3fcc23d3ec68#media-blob-url=true+id=b739f74c-5fb0-4544-a9f0-83e11d04ea30+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-002845.png+size=5292+width=845+height=107+alt=image-20241123-002845.png)

Задачи в списке выводятся согласно их приоритетам. Задачи с высшим приоритетом выводятся выше. Если у задач одинаковый приоритет, то выводим согласно алфавиту от А-Я.

В списке задач, на каждой строчке задачи выводится исполнитель.

Рядом с название задачи выводим Выпадающий список с моновыбором статусов задачи. Возможность изменять статус есть у Создателя проекта и Редактора.

**В самом верху выводим просроченные задачи (нынешняя дата > дата окончания задачи)**

Заголовок - Просроченные задачи. Под названием задачи пишется насколько просрачена задача

Пример:

Open image-20241123-002807.png

![blob:https://antonbaturin2003.atlassian.net/e244be07-15bc-429b-a6ee-411647b0a90c#media-blob-url=true&id=d5194cf0-ecc3-40eb-b841-42a6ed300614&collection=contentId-98328&contextId=98328&mimeType=image%2Fpng&name=image-20241123-002807.png&size=2412&width=222&height=59&alt=image-20241123-002807.png](CyberGarden+18+2024+d467ef6f-9c3b-4887-930e-24f74e9bcaf3/e244be07-15bc-429b-a6ee-411647b0a90c#media-blob-url=true+id=d5194cf0-ecc3-40eb-b841-42a6ed300614+collection=contentId-98328+contextId=98328+mimeType=image%2Fpng+name=image-20241123-002807.png+size=2412+width=222+height=59+alt=image-20241123-002807.png)

1. **Карточка задачи**
При нажатии на название задачи открывается карточка задачи. Данная карточка состоит из 2 блоков - Блок с Названием/Статусом/Описанием/Возможность добавлять подзадачи/Комментарием и Блок с Проектом/Исполнителем/

