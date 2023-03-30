# Arcade
Аркадная игра по получению больше очков
В данной игре главная цель это набивание больше очков чем в прошлый раз
Самое главное это добовление шрифта для игры
    
    font.init()
      font = font.SysFont("Georgia",60)
      
И также вторая самая главная часть игры это работа со звуком

    pistol_sounds = [mixer.Sound('sounds/pistol-fire-1.ogg'),mixer.Sound('sounds/pistol-fire-2.ogg')]
    shotgun_sounds = [mixer.Sound('sounds/shotgun-fire-1.ogg'), mixer.Sound('sounds/shotgun-fire-2.ogg')]
    pistol_reload = mixer.Sound('sounds/reload-pistol.ogg')
    shotgun_reload = mixer.Sound('sounds/reload-shotgun.ogg')
    imposible_reload = mixer.Sound('sounds/imposible-reload.ogg')
Самое главное поменять формат с mp3 на ogg

Второй гланый пункт это импортировать класс Sprite.sprite из библеотеки PyGame
![image](https://user-images.githubusercontent.com/128893943/228895084-e6e8140c-3b26-4677-b683-ce70d08b6071.png)

Данный класс также нужен для других подклассов к примеру для классов героя и классов противников
![image](https://user-images.githubusercontent.com/128893943/228897130-40e160a1-284b-44f3-8fc0-fd9956069d5c.png)
![image](https://user-images.githubusercontent.com/128893943/228897251-1ad72877-5e42-48e1-aece-9f8133be5e80.png)

