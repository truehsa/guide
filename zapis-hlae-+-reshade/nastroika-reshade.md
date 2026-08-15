---
icon: file-heart
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

# Настройка ReShade

## Добавление путей к шейдерам и текстурам

Если вы [отсюда](../reshade/ustanovka.md#id-1-gotovyi-pak-reshade-v6.0.1) скачивали уже готовый пак решейда, то скорее всего при первом запуске у вас выйдет ошибка о том что эффекты недогрузились из-за того что не выставлены пути к ним.

<figure><img src="../.gitbook/assets/изображение (1).png" alt="" width="474"><figcaption></figcaption></figure>

**Решение**:

1. Зайдите во вкладку _Settings_
2.  Нажмите на "+" возле параметра _Effect Search paths_ и проставьте путь к шейдерам, по умолчанию шейдеры лежат в той же папке что и устанавливался решейд по пути `/reshade-shaders/Shaders`<br>

    <figure><img src="../.gitbook/assets/изображение (2).png" alt="" width="478"><figcaption></figcaption></figure>
3.  То же самое проделываем и для текстур:<br>

    <figure><img src="../.gitbook/assets/изображение (3).png" alt="" width="478"><figcaption></figcaption></figure>
4.  Заходим на обратно на вкладку Home и жмём Reload.<br>

    <figure><img src="../.gitbook/assets/изображение (4).png" alt="" width="441"><figcaption></figcaption></figure>
5.  У вас должна начаться компиляция шейдеров, в первый раз это может занять некоторое время.<br>

    <figure><img src="../.gitbook/assets/изображение (5).png" alt=""><figcaption></figcaption></figure>
6. Если всё скомпилилось верно в меню появятся настройки разных шейдеров, можно приступать к следующим этапам.\
   \
   После компиляции в меню могут появится ошибки некоторых шейдеров, в этом нет ничего страшного, можно спокойно игнорировать, если не нравится - удалить из папки Shaders нескомпиленные.
