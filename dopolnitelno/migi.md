---
description: Моддинг Counter-Strike
icon: square-plus
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

# MIGI

**MIGI** — это инструмент для модификации CS:GO, который позволяет заменять файлы игры, не изменяя оригинальные файлы напрямую. \
Проще говоря, это специальная программа, с помощью которой можно устанавливать различные моды: новые скины, модели персонажей, ретекстуры карт для демок и т.д.

**В этом гайде поставим аддон на ПЛЮШЕВЫХ ФУМО.**

<figure><img src="../.gitbook/assets/изображение (51).png" alt=""><figcaption></figcaption></figure>

## Установка MIGI

{% file src="../.gitbook/assets/migi.zip" %}

1. Скачиваете архив и копируете все файлы в корень папки игры

<figure><img src="../.gitbook/assets/изображение (47).png" alt="" width="563"><figcaption></figcaption></figure>

2. Запускаете `migi.exe`&#x20;
3. В открывшемся окне жмёте "BUILD!", после чего ждёте загрузки

<figure><img src="../.gitbook/assets/изображение (48).png" alt="" width="563"><figcaption></figcaption></figure>

4. Как только всё сбилдилось, можно закрывать MIGI и переходить в HLAE. В пользовательском загрузчике нужно поменять `-game csgo` на `-game migi/csgo`

<figure><img src="../.gitbook/assets/изображение (49).png" alt="" width="440"><figcaption></figcaption></figure>

5. Нажимаете "OK" и вместо обычной игры должна открыться модифицированная версия

<figure><img src="../.gitbook/assets/изображение (50).png" alt="" width="381"><figcaption></figcaption></figure>

## Установка аддонов (модов)

В качестве примера установим мод на плюшевых фумо вместо гранат в контр страйк.

{% file src="../.gitbook/assets/fumogrenades.zip" %}

1. Скачиваем архив и заходим в папку `/migi/csgo/addons/`\
   На данный момент у вас там должно быть пусто.\
   Перекидываем все из архива в папку аддонов.

<figure><img src="../.gitbook/assets/изображение (52).png" alt=""><figcaption></figcaption></figure>

2. Заходим в `migi.exe` и нажимаем "UPDATE BUILD" чтобы аддоны загрузились в игру.
3. Запускаем через пользовательский загрузчик HLAE игру.
4. Заходим на любую карту. При запуске MIGI на карте может **ДИКО** падать фпс _(будет часто происходить если на прошлых этапах не запускали `migi.exe` от имени администратора)_, достаточно подождать 2-3 минуты для того чтобы MIGI подгрузил всё что ему надо и карта перезапустится.

<figure><img src="../.gitbook/assets/изображение (53).png" alt="" width="528"><figcaption><p>Инициализация MIGI в консоли и просадки ФПС из-за этого повода 0_0</p></figcaption></figure>

4. Выдаём себе гранаты и видим что модели заменены на фумо!!! 0\_0

<figure><img src="../.gitbook/assets/изображение (54).png" alt=""><figcaption><p>Если гранаты не заменились - запустите migi.exe от имени администратора и нажмите "UPDATE BUILD"</p></figcaption></figure>

Готово! На демках теперь тоже будут заменены гранаты.

{% hint style="info" %}
Удалить аддоны можно просто удалив их из папки `/migi/csgo/addons/`
{% endhint %}

## Где искать аддоны?

Аддоны можно найти на специализированных серверах Discord, вот парочка из них:

### Discord Server: Derivative Eagles

{% columns %}
{% column width="33.33333333333333%" valign="middle" %}
<div align="left"><figure><img src="../.gitbook/assets/изображение (64).png" alt="" width="183"><figcaption></figcaption></figure></div>
{% endcolumn %}

{% column width="66.66666666666667%" %}
Вступить можно по ссылке:

[https://discord.com/invite/UmE9JG7](https://discord.com/invite/UmE9JG7)
{% endcolumn %}
{% endcolumns %}

### Discord Server: Parabellum Hub

{% columns %}
{% column width="33.33333333333333%" valign="middle" %}
<figure><img src="../.gitbook/assets/Discord_hWeN2RdIu7.png" alt="" width="183"><figcaption></figcaption></figure>


{% endcolumn %}

{% column width="66.66666666666667%" %}
Вступить можно по ссылке:

[https://discord.com/invite/GrYQmDMs8w](https://discord.com/invite/GrYQmDMs8w)
{% endcolumn %}
{% endcolumns %}



***

### Аддоны unner'a

Собраны лучшие аддоны для клипов в одной папке:

{% columns %}
{% column width="58.333333333333336%" %}
<figure><img src="../.gitbook/assets/изображение (55).png" alt="" width="563"><figcaption></figcaption></figure>


{% endcolumn %}

{% column width="41.666666666666664%" %}
Скачать можно по ссылке:

[https://www.mediafire.com/folder/?ljptdvhdnmcn6#ljptdvhdnmcn6](https://www.mediafire.com/folder/?ljptdvhdnmcn6#ljptdvhdnmcn6)
{% endcolumn %}
{% endcolumns %}
