---
icon: gears
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
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

# Запуск

Осталось подружить HLAE и решейд вместе для записи видео.

## Пользовательский загрузчик HLAE

Поскольку мы запускаем HLAE вместе с решейдом нужно добавить решейд в пользовательский загрузчик.

1.  Открываем HLAE. Выбираем из меню: \
    _&#x418;нструменты > Разработчик > Пользовательский загрузчик_<br>

    <figure><img src="../.gitbook/assets/изображение (21).png" alt="" width="450"><figcaption></figcaption></figure>
2.  В открывшемся окне нужно настроить несколько параметров:\
    \
    _&#x41F;уть к программе_ — пропишите полный путь до **csgo.exe**\
    _&#x41F;араметры запуска_ — можете оставить как есть или если там пусто, вписать дефолтные значения: `-steam -insecure +sv_lan 1 -window -console -game csgo`

    <figure><img src="../.gitbook/assets/изображение (22).png" alt="" width="447"><figcaption></figcaption></figure>
3.  В поле _DLL для инъекции_ нужно добавить .dll самого HLAE и решейда. Для этого нажимаете кнопку обзор и из корневой папки HLAE выбираете _AfxHookSource.dll_<br>

    <figure><img src="../.gitbook/assets/изображение (23).png" alt="" width="563"><figcaption><p>AfxHookSource.dll</p></figcaption></figure>

Так же делаем с .dll решейда (_d3d9.dll_), которая находится в папке решейда куда вы его устанавливали

<figure><img src="../.gitbook/assets/изображение (24).png" alt="" width="563"><figcaption><p>d3d9.dll</p></figcaption></figure>

4. После настройки этого окна оно автоматически сохранится, ничего вписывать заново не придётся. Нажимайте **OK** и ждите когда запуститься игра.
5.  Если игра запустилась и на кнопку _Home_ открывается меню решейда, то вы молодец и всё работает!<br>

    <figure><img src="../.gitbook/assets/изображение (25).png" alt="" width="563"><figcaption></figcaption></figure>
