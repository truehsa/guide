---
icon: desktop-arrow-down
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

# Установка

Есть два способа установить ReShade:

1. Лёгкий и быстрый (рекомендую) — готовый рабочий билд решейда (v6.0.1) под CS:GO с нужными аддонами и шейдерами.
2. Установка всего вручную.

**Не бойтесь, разберу сразу два!** Если не доверяете не понятным архивам с интернета, можете сделать всё вручную =)

## 1) Готовый пак ReShade v6.0.1

Скачайте архив ниже:

{% file src="../.gitbook/assets/reshade_hsa_guide.zip" %}

Откройте архив и перекиньте папку `reshade` в любое удобное место, например на рабочий стол.

<figure><img src="../.gitbook/assets/изображение (18).png" alt=""><figcaption></figcaption></figure>

Всё! Решейд и нужные к нему компоненты для нормальной работы с CS:GO установлены, в вашем случае можно двигаться дальше по гайду.

## 2) Установка всего вручную

### Установка ReShade

1. Зайдите на сайт ReShade: [https://reshade.me/](https://reshade.me/)
2.  Нажмите "Download" и выберите версию инсталлера с Add-on Support<br>

    <figure><img src="../.gitbook/assets/изображение (28).png" alt="" width="563"><figcaption></figcaption></figure>
3. Создайте отдельную папку где будет храниться решейд, шейдеры, аддоны и прочее.
4. В эту папку перекиньте скачанный инсталлер.
5.  Зайдите в корневую папку HLAE (обычно это путь `C:\Program Files (x86)\HLAE`), **скопируйте (именно скопировать, не перекинуть)** из этой папки `injector.exe` и вставьте в созданную папку для решейда. Выглядеть должно это вот так:<br>

    <figure><img src="../.gitbook/assets/изображение (29).png" alt="" width="563"><figcaption></figcaption></figure>
6.  Откройте инсталлер решейда. Нажмите "Browse" и выберите скопированный инжектор.<br>

    <figure><img src="../.gitbook/assets/изображение (30).png" alt="" width="563"><figcaption></figcaption></figure>
7.  В следующем окне выберите Rendering API - **DirectX 9**<br>

    <div align="center"><figure><img src="../.gitbook/assets/изображение (31).png" alt="" width="361"><figcaption></figcaption></figure></div>
8. В выборе эффектов выберите все эффекты, нажав два раза на кнопку "Uncheck All".
9. В выборе аддонов ничего не ставьте если не знаете что он делает.
10. Если всё произошло успешно, то в конце выведет окно с зеленой галочкой.<br>

    <figure><img src="../.gitbook/assets/изображение (32).png" alt="" width="361"><figcaption></figcaption></figure>

### Установка аддона ReShade\_AdvancedFX

По умолчанию ReShade накладывается на игру полностью, так же покрывая и внутриигровой HUD, чтобы этого избежать есть специальный аддон который убирает наложение решейда на худ.

**Установка**:

1. Переходим на релизы аддона в GitHub: [https://github.com/advancedfx/ReShade\_advancedfx/releases](https://github.com/advancedfx/ReShade_advancedfx/releases)
2.  Устанавливаем архив .zip: <br>

    <figure><img src="../.gitbook/assets/изображение (33).png" alt="" width="563"><figcaption></figcaption></figure>
3.  В архиве будет лежать две папки x64 и x86, заходите в x86 и перекидывайте файл с аддоном в корневую папку решейда.<br>

    <figure><img src="../.gitbook/assets/изображение (34).png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="success" %}
Готово! Теперь у вас есть новейшая версия решейда со всеми эффектами.
{% endhint %}

{% hint style="warning" %}
НО! Количество шейдеров почти в два раза больше в новых версиях, поэтому дальнейшая компиляция может занять в несколько раз дольше времени, чем готовый пак со всем нужным. Поэтому рекомендую использовать всё таки уже готовое! =)
{% endhint %}
