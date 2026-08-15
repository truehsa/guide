---
icon: camcorder
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

# Запись

## Конфиг

### Установка

Для записи используются внутренние команды HLAE в консоли CS:GO, чтобы постоянно их не вписывать и легко ориентироваться при записи я доработал конфиг [adam sandler](https://www.youtube.com/watch?v=_sv7HkTPa24) и делюсь им:

{% file src="../.gitbook/assets/hsa.cfg" %}

Файл должен лежать в корневой папке игры `/csgo_legacy/csgo/cfg/`

Конфиг записывает видео в 1080 FPS, накидывая на него очень крутой Motion Blur. Пример показан тут: [https://www.youtube.com/watch?v=\_sv7HkTPa24](https://www.youtube.com/watch?v=_sv7HkTPa24)

{% hint style="warning" %}
**ВАЖНО!**\
\
Создайте папку куда будут сохраняться все ваши записанные клипы и на 3 строке конфига поменяйте путь к этой папке на свой:

![](<../.gitbook/assets/изображение (8).png>)
{% endhint %}

### Бинды & Алиасы

Чтобы узнать все бинды и алиасы в конфиге, можете написать в консоли commands.

**Напишу основные**:\
\
bind "O" — начать/закончить запись\
hud — включить/выключить hud (кроме киллфида и прицела)\
radar — включить/выключить радар\
chat — включить/выключить чат\
noflash — убрать ослепление от флешки\
\
Добавлено мной:\
\
bind "L" — включить/выключить превью решейда\
bind "K" — включить/выключить гринскрин (для отдельной записи худа)

## Запись&#x20;

1. Заходите на любую демку, для меня это будет [роут unner'a c демопака карты Guard](https://www.youtube.com/watch?v=Ux2QNQie-38).
2. Выбираете любой понравившийся пресет в решейде.
3. Переходим к нужному тику через `demo_goto <tick>`
4. Нажимаете "O" и начинается запись в замедленном времени. Не пугайтесь резких звуков, на аудио-дорожке всё будет нормально.
5. После того как клип сделан, нажимаете "O" для остановки записи и смотрите в консоль, если всё успешно, должно быть написано примерно такое:\
   \
   <kbd>Starting recording ... done.</kbd>\ <kbd>Recording to "C:\hlae\_cuts\take0006".</kbd>\ <kbd>Finishing recording ... done.</kbd>&#x20;
6.  Заходите в папку куда поставили путь для сохранения видео. Если всё правильно, то будут лежать папка `rec` с .mp4 видео и audio.wav с отдельной аудио-дорожкой.<br>

    <figure><img src="../.gitbook/assets/изображение (27).png" alt="" width="542"><figcaption></figcaption></figure>
7. **Результат:**

{% embed url="https://www.youtube.com/watch?v=LQjquuDYVO0" %}

{% hint style="info" %}
На этом основной гайд заканчивается. Возможно будут добавлены дополнительные топики по другим темам или аддонам к Counter-Strike. Спасибо за прочтение.
{% endhint %}
