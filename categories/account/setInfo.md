---
layout: default
title: Метод Account.SetInfo
permalink: account/setInfo/
comments: true
---
# Метод Account.SetInfo
Позволяет редактировать информацию о текущем аккаунте.

Страница документации ВКонтакте [account.setInfo](https://vk.com/dev/account.setInfo).

## Синтаксис
``` csharp
public bool SetInfo(string name, string value)
```

## Параметры
+ **name** - Имя настройки строка, доступен начиная с версии 5.49
+ **value** - Значение настройки строка, доступен начиная с версии 5.49

## Результат
В результате успешного выполнения возвращает **true**.

## Пример
``` csharp
var setInfo = _api.Account.SetInfo("own_posts_default", "1");
```

## Версия Вконтакте API v.5.50
Дата обновления: 10.02.2016 13:55:10