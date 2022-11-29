# MGM.js
Mini Game Maker

|| ПРОЕКТ НАХОДИТСЯ В РАЗРАБОТКЕ ||

## Description

Библиотека для помощи в создании игр на `javascript`.

____

# Instruction

Скачать `MGM.js`, создать файл `game.html`, и написать там код:

```html
<script src="MGM.js"></script>
<script>
    const Mgm = new MGM()
</script>
```

Или

```html
<script src="MGM.js"></script>
<script>
    const Mgm = new MGM({
        name: 'My game',
    })

    Mgm.object['unit'] = {
        init: th => {
            th.drawCircle = {
                radius: 30,
                fillColor: 'green',
            }
        },
        update: th => {
            th.wasd(5)
        },
    }
</script>
```
____

# Donate

Зодонатить:

[yoomoney](https://yoomoney.ru/to/410018410401723)

