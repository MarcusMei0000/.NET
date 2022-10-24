# .NET
Приложение, регулирующее работу стоматологии:
1. Регистрация (ФИО, телефон, пароль, почта, дата рождения, фото, для пациента: полис; для врача: специальность, кабинет приёма, календарь)
2. Авторизация (почта/телефон, пароль).
3. Выйти из приложения
4. Сменить пароль

Пациент
1. Профиль  содержит информацию указанную при регистрации и последнюю запись к врачу (текущую или последнюю),
2. Текущую запись можно отменить (на кнопку "Отменить" и подтвердив действие во всплывающем окне, после чего запись удаляется из профиля) или изменить (переход на Страницу врача, где открыта соответствующая дата и список времени (можно сменить и дату, и время)), и открыть детали записи(время, врач, кабинет приёма).
3. На главной странице - список стоматологов (их карточки) с поиском по ФИО стоматлога; чтобы записаться на приём необходимо нажать на карточку врача.
4. Карточка врача содержит описание и календарь, чтобы выбрать дату и время приёма. 
5. Сначала пользователь выбирает дату, затем ему высвечивается список времени (серым цветом обозначено занятое время, ярким цветом - доступное для записи время), после нажатия кнопки "Подтвердить" информация о текущей записи появляется в профиле.

Врач
1. Устанавливать расписание работы на неделю - выбирать целый день или конкретное время на каждый день (существует значение рабочей недели по умолчанию, т.е. на неделе заполнено N приёмов, которые сразу высвечиваются врачу).
2. Просматривать записавшихся пользователей.
* Врач имеет 1 постоянную специальность в стоматологии
* Врач единовременно прикреплён к 1 кабинету, к которому могут быть прикреплены несколько врачей.

![БД](https://user-images.githubusercontent.com/106516611/197479668-5a1ff59c-db3e-4b39-ab6b-7feb439a8248.png)

