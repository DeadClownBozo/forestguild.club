---
layout: wiki
order: 6
title: Аддоны
---

# Что это и зачем?

Аддоны в WoW - скрипты/плагины, которые расширяют стандартный интерфейс игры и/или добавляют новый функционал. Есть аддоны, которые никак не изменяют интерфейс, а срабатывают в нужный момент. Пример: GTFO - визульно никаких изменений, он начнет кричать (точнее, выть сиреной) если ты встанешь в лужу. Штука очень простая, но сколько жизней спасла - просто не счесть.

### Где достать?

CurseForge + Twitch = one love.

Главный сайт с аддонами для WoW - CurseForge, там можно найти и скачать их. **НО!** Если ты хочешь получить автообновление аддонов, синхронизацию и бэкап настроек - то ставь Curse Client, который сейчас называется Twitch Client (да, они скооперировались. Да, странно. Но оно работает). Скачать - на сайте [CurseForge](https://www.curseforge.com/twitch-client). В общем, ставь клиент.

Дальше разберем обязательные аддоны

## Требуемые аддоны

> Без них могут не взять в [рейд](/wiki/raid) и [ключи](/wiki/keystones).

**Для ВСЕХ**

* [Deadly Boss Mods (DBM)](https://www.curseforge.com/wow/addons/deadly-boss-mods) - самый главный аддон, он знает все про скиллы босов и будет подсказывать когда отбегать, прерывать касты, диспеллить, прыгать, ~~танцевать~~ и т.д. Состоит из основного аддона DBM и кучи плагинов к нему. Советую ставить все разом (они загружаются по требованию, так что лагать не будет) _Настройки не требует_
* [GTFO](https://www.curseforge.com/wow/addons/gtfo) - кричит, когда ты стоишь в луже. Дешево и сердито, спас огромное количество жизней. _Настройки не требует_

**Для РЛов**

* [RaidSlackCheck](https://www.curseforge.com/wow/addons/raidslackcheck) - при проверке готовности пишет в чат у кого нет фласок (настоев), баффа от еды и рун. Плюс когда кто-то ставит пир, ремонт или источник душ (локовские камни) аддон автоматом будет делать объявление рейду. _Настройки не требует_
* Команды DBM (вставлять прямо в чат, до символа `#`):

```bash
/dbm ver # Проверка наличия DBM и его версии у игроков в рейде, выполнять при сборе.
# Есть еще вариант /dbm ver2 - шепчет игрокам, если у них устарел DBM

/dbm pull # Команда атаковать через 10 секунд. У всех игроков появится таймер с пояснением посреди экрана.
# Можно указывать кастомное время, например - /dbm pull 4 - атака через 4 секунды

/dbm break 3 # Команда перерыва. Хочешь перекур? Пишешь эту команду, у всех игроков появляется уведомление и таймер.
# Можно указать кастомное время, например - /dbm break 5 - перерыв на 5 минут
```

## Рекомендуемые аддоны

> Поставил все требуемые? ОКей, вот тебе еще несколько, которые можно поставить по желанию. Они практически не изменяют интерфейс, но упрощают жизнь.

* [Scrap (Junk Seller)](https://www.curseforge.com/wow/addons/scrap) - продает весь мусор автоматом при посещении торговцев и чинит надетые вещи (в том числе, за счет гильдейского банка). Советую зайти в настройки - там много интересных опций.
* [Overachiever](https://www.curseforge.com/wow/addons/overachiever) - помогает с ачивками, ооочень полезная вещь. _Настройки не требует_
* [Can I Mog It?](https://www.curseforge.com/wow/addons/can-i-mog-it) - показывает на вещах (в чате, в инвернате, в добыче) есть ли у тебя такой трасмог или нет. Очень полезная штука для любителей трансмога. _Не требует настройки_
* [Bartender 4](https://www.curseforge.com/wow/addons/bartender4) - позволяет биндить кастомные кнопки (хочешь сбитие каста на "Е"? Тебе нужен этот аддон), плюс позволяет сильно изменить интерфейс (но это не обязательно).
* [MBB](https://www.curseforge.com/wow/addons/mbb) - прячет кнопки всех аддонов в одну. Очень простая и полезная штука.
* [SuperGuildInvite Reborn](https://www.curseforge.com/wow/addons/superguildinvite-reborn) - аддон, который автоматом приглашает игроков в гильдию. Выставь фильтр по лвлу: 111-120. Чем больше согильдийцев будет приглашать новых игроков, тем больше народа будет в гильдии, тем больше народа смогут помочь в гильдейском чате и дискорде, тем больше и чаще будем ходить в рейды и ключи.
