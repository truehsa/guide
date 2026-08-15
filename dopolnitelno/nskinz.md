---
description: Смена скинов на демке
icon: gun
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# nSkinz

Для каждого уважаемого человека очевидно, что скины на клипе дают эстетическое удовольствие у зрителя и вызывает интерес. Если у вас есть чужая или своя демка без скинов, но очень хочется поставить, то нужно использовать nSkinz.

**nSkinz** — скинченджер работающий по SteamID64. Можете взять айди любого человека на демке и заменять ему уже существующие скины.

{% hint style="danger" %}
Использование любых сторонних программ для смены скинов (скинченджеров) строго запрещено правилами Valve и может привести к блокировке аккаунта.
{% endhint %}

## Видео-гайд

У [unner'a](https://www.youtube.com/@unner) был стрим где он точно так же разбирал как заинжектить и использовать **nSkinz**, советую к просмотру:

{% embed url="https://www.youtube.com/live/2IKMlYBag74?si=lOCvGWvtTRj4t4k1&t=2799" %}
Тайминг начала разбора: **46:39**
{% endembed %}

## Установка

Скачайте архив и разархивируйте nSkinz.dll куда вам удобно.

{% file src="../.gitbook/assets/nskinz.zip" %}

## Инжект

Зайдите в игру через HLAE и введите в консоль команду mirv\_loadlibrary "путь/до/nskinz.dll", пример:\
\
`mirv_loadlibrary "C:\Users\hsa\Desktop\nskinz\nSkinz.dll"`

## Использование

Заходите на любую демку где хотите поменять скины. Переходите к POV нужного вам игрока и нажимаете `Insert`.

<figure><img src="../.gitbook/assets/изображение (38).png" alt="" width="563"><figcaption></figcaption></figure>

При верном инжекте должно открыться меню скинченджера. Слева сверху - список всех скинов которые вы добавили. Справа - настройка скина. Снизу - настройка стикеров на оружие.

Чтобы добавить скин для определённого человека вам нужен его SteamID64, если вы используете [мой конфиг](../zapis-hlae-+-reshade/zapis.md#konfig), то при написании id в консоли у вас выведет всех игроков с их никами и ID, ищем нужного человека и копируем этот набор цифр в поле XUID.

<figure><img src="../.gitbook/assets/изображение (39).png" alt="" width="443"><figcaption></figcaption></figure>

Основные настройка скина:

* **Name**: имя для скина внутри скинченджера.
* **Item**: выбор предмета для скина (ножи, перчатки, AK-47, AWP и т.д.)
* **XUID**: SteamID64 игрока которому вы хотите изменить скин.
* **Knife/Glove**: выбор типа перчаток/ножа.
* **Paint Kit**: выбор скина на этот предмет.
* **Name tag**: изменение внутриигрового названия.

<figure><img src="../.gitbook/assets/изображение (41).png" alt=""><figcaption></figcaption></figure>

После настройки нажимайте кнопку "Update" и обновите демку.

<figure><img src="../.gitbook/assets/изображение (42).png" alt=""><figcaption></figcaption></figure>

Теперь вы можете видеть скин который вы установили прямо на демке игрока:

<figure><img src="../.gitbook/assets/изображение (43).png" alt="" width="563"><figcaption></figcaption></figure>

