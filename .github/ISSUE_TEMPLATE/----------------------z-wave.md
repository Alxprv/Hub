---
name: Добавление устройства Z-Wave
about: Запрос на добавление Z-Wave устройства
title: ''
labels: New device, Z-Wave
assignees: MakeSimpleOrg

---

Для добавления поддержки нового устройства в хаб, необходимо:

1) Спарить устройство с хабом, и убедиться, что оно не поддерживается хабом. Устройство должно появиться на вкладке контроллеров, но не появиться в списке аксессуаров. Модель устройства должна определиться как "Unknown".
2) Найти в интернете или на корпусе/упаковке/инструкции название модели и производителя, и указать их в сообщении.
3) Указать ссылку на сайт производителя с описанием устройства, и pdf файл с описанием настроек и другой информации, если есть.
4) В хабе, напротив устройства нажать на кнопку "i", появится подробная информация об устройстве. Ее нужно скопировать (с помощью кнопки в верхнем правом углу) и вставить в сообщение.

Если на вкладке информации напротив Manufacturer Id/Device Type/Device Id стоит значение "7FFFFFFF" то необходимо вначале переспарить устройство.

В названии issue указать название производителя и модели.
