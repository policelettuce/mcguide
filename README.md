# MC FAQ

## Как начать играть?


Видеоinstruction (1 min): https://youtu.be/7Uah3MtlPZw


1. Скачать TLauncher с офф. сайта + зарегистрироваться на нём (введённый логин будет вашим ником в игре): https://tlauncher.org/
2. Установить лаунчер
3. В лаунчере войти в свой аккаунт (слева внизу, вводить данные, под которыми вы зарегались на сайте)
4. Выбрать версию "Версия 1.19".
5. Запустить и коннектиться :)


## Консольные команды


Видео-версия с демонстрацией: https://youtu.be/iv5Y5uZAK4g


Квадратные скобки в командах писать не нужно! Они здесь для более наглядного обозначения :)


Все команды, использующие никнеймы игроков, работают, только если этот игрок онлайн! Например, вы не можете выписать из привата или отпарвить инвайт на варп игроку, который оффлайн.

### Регионы (WorldGuard)

Максимум 7 регионов на одного игрока, 50000 блоков на один регион!


Не ставьте регионы вплотную к краям или стенам своих построек, чтобы никто не подсунул вам динамит или не залил все вокруг лавой :)


Вместо "rg" можно писать "region", но зачем...

| <b>Команда</b> | <b>Описание</b> |
| ---- | ---- |
| `//pos1` `//pos2` | Выделение региона. Легче использовать деревянный топор. Две точки являются диагональю куба, который и будет вашей зоной привата |
| `/rg claim [название]` | Заприватить регион. |
| `/rg remove [название]` | Удалить регион. Для этого вы должны быть одним из владельцев (Owners) региона. |
| `/rg info` | Вывести в чат информацию о регионе, в котором вы стоите. |
| `/rg info [назавние]` | Вывести в чат информацию о регионе с таким названием. |
| `/rg flag [название_рега] [флаг] [deny/allow/none]` | Текущие доступные флаги: enderpearl, chorus-fruit-teleport |
| `/rg addowner [название_рега] [никнейм]` | Добавляет владельца в регион. Владелец может делать с регионом все, что захочет! |
| `/rg addmember [название_рега] [никнейм]` | Добавляет участника в регион. Может делать все, что угодно, но не имеет доступа к консольным командам для региона. |
| `/rg removeowner [название_рега] [никнейм]` | Убрать владельца региона из привата. |
| `/rg removemember [название_рега] [никнейм]` | Убрать участника региона из привата. |

### Варпы (MyWarp)

Максимум 6 варпов на одного игрока!


При телепортации есть задержка в 3 секунды. Если во время этих 3 секунд вы получите урон или будете двигаться, то телепортация отменится.


Варп может быть: 
- Публичным - любой может телепортироваться на этот варп
- Приватный - изначально только вы можете телепортироваться на этот варп. Можно заинвайтить игроков на этот варп, чтобы они смогли на него телепортироваться.


Вместо /warp можно использовать /to для телепортации.

| <b>Команда</b> | <b>Описание</b> |
| ---- | ---- |
| `/warp [название]` | Телепортироваться на варп с таким названием. |
| `/warp assets` | Вывести все ВАШИ варпы. |
| `/warp create [название]` | Создать публичный варп с таким названием. |
| `/warp pcreate [название]` | Создать приватный варп с таким названием. |
| `/warp private [название]` | Сделать ваш варп приватным. |
| `/warp public [название]` | Сделать ваш варп публичным. |
| `/warp invite [никнейм] [название]` | Пригласить игрока на ваш приватный варп, т.е. этот игрок отныне сможет пользоваться этим варпом. |
| `/warp uninvite [никнейм] [название]` | Отменить инвайт игрока на варп. |
| `/warp public [название]` | Сделать ваш варп публичным. |
| `/warp delete [название]` | Удалить варп. |
| `/warp info [название]` | Вывести в чат информацию о варпе. |
| `/warp update [название]` | Переместить варп с таким названием на ваше текущее положение |
| `/warp list` | Вывести ВСЕ доступные вам варпы (да, и варпы других игроков) |
| `/warp list -c [никнейм]` | Вывести все публичные варпы игрока с таким ником. |
| `/warp welcome [название]` | Создать приветствие, которое будет выводиться игроку в чат после телепортации на этот варп. После введения команды у вас есть 60 секунд, чтобы написать в чат новое приветствие. |
