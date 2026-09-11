---
icon: video
---

# Запись

## Запись демки

**До загрузки карты** обязательно откройте консоль и активируйте GOTV командой:\
`tv_enable 1`

<figure><img src="../.gitbook/assets/изображение (72).png" alt="" width="563"><figcaption></figcaption></figure>

После захода на карту запустите запись, указав любое имя файла:\
`tv_record <название_демки>` _(например, tv\_record my\_match)_

<figure><img src="../.gitbook/assets/изображение (73).png" alt="" width="563"><figcaption></figcaption></figure>

Для остановки записи введите в консоли:\
`tv_stoprecord`

<figure><img src="../.gitbook/assets/изображение (74).png" alt="" width="507"><figcaption></figcaption></figure>

Отлично! Теперь демка записана и сохранена.

## Просмотр записанной демки

Записанный файл с расширением **.dem** автоматически сохраняется в корневую папку игры, чтобы просмотреть демку, нажмите **Shift+F2** и выберите **Load**, в открывшемся проводнике выбираете демку с вашем названием которое вы выбрали до этого и спокойно просматриваете.

<figure><img src="../.gitbook/assets/изображение (75).png" alt=""><figcaption></figcaption></figure>

## Лайфхак для быстрой записи лучшего момента

{% hint style="info" %}
Убедитесь что перед подключением на сервер вы включили `tv_enable 1`
{% endhint %}

После того как вы сделали хороший клип - введите в консоли `tv_record <название демки>` и сразу же завершите командой `tv_stoprecord`

В итоге вы получите короткую GOTV демку, которая захватит последние \~2 минуты игры и будет весить меньше 2мб (от 6000 тиков)

{% embed url="https://www.youtube.com/watch?v=uFWCjM1zncE" %}
reupload from unner discord server
{% endembed %}
