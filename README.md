<img width="640" height="640" alt="1000701969" src="https://github.com/user-attachments/assets/1833f805-188e-435e-913f-1b0a36cad3b7" alt="Логотип"/>

# ‧₊˚✧[Old Horizons]✧˚₊‧
*Проект которая цель создать мелон на ccode, уже готово lua, моды, и некоторые другие штуки!* ***Дальше БОЛЬШЕ!!***

<img width="1920" height="1080" alt="IMG_20260929_220318_533" src="https://github.com/user-attachments/assets/210243f6-73b5-4168-83f4-5518e9d7cf04" alt="Old Horizons" />
<hr>

# ‧₊˚✧[Как скачать?]✧˚₊‧

*Нажимаете на кнопку* ***Code*** *затем* ***+*** *и уже потом* ***Download ZIP*** *затем качайте CCode билд 1387 и распакакуйте ZIP файл, и можете удалить всё лишнее, и зайдите в* ***Мои проекты*** *и потом ***+*** и выберите файл проекта,* ***ВСЁ!!!***
*Если вам нужно активировать примеры кодов, то дальше заходите в Главное меню/Консоль и выбирайте режим который вам нужен ***Lua/HTML*** и вставить код.*

<img width="1659" height="935" alt="1000701972" src="https://github.com/user-attachments/assets/6ad6a12a-3d62-4912-9c49-efac95d49262" alt="Как скачать?" />

<hr>

# ‧₊˚✧[Соц. Сети]✧˚₊‧

• ⭕ [YouTube](https://youtube.com/@oldhorizons?si=gEBUlfJlUZY3gdfJ "YouTube")\
• 🔵 [Telegram](https://t.me/OldHorizons "Telegram")\
• 💽 [Discord](https://discord.gg/p4KnZEVPgT "Discord")\
• 🎡 [One Studio](https://github.com/One-Studio-SP "GitHub")\
• 🎁 [Почта](mailto:oldhorizonsofficial@gmail.com "Gmail")

<img width="1013" height="571" alt="1000701975" src="https://github.com/user-attachments/assets/9fd67abd-6656-4134-be91-35ca7926a392" alt="Соц. Сети" />
<hr>

# ‧₊˚✧[Скачать]✧˚₊‧
• 🗑️ [Трешбокс](https://trashbox.ru/topics/192503/old-horizons "Tрешбокс")\
• ⚫ [GitHub](https://github.com/One-Studio-SP/Old-Horizons "GitHub")\
• 🏪 [itch.io](https://gap-apk.itch.io/old-horizons "itch.io")\
• 🩴 [Zoro Game Store](https://zoro-game.store/game.html?id=52 "Zoro Game Store")\
• ⚡ [Game Jolt](https://gamejolt.com/games/oldhorizons/992533 "Game Jolt")\
• 🔵 [RuStore](https://www.rustore.ru/catalog/app/com.oldhorizons.app "RuStore")

<img width="1671" height="942" alt="1000701978" src="https://github.com/user-attachments/assets/8646ba3a-30d3-47e2-8f3d-8de5cfb36693" alt="Скачать" />
<hr>

# ‧₊˚✧[Стафф]✧˚₊‧
• 👑 [Прøбе́л - Разраб/Хост](https://github.com/GapAPK "GitHub")\
• 🎨 Secret Melon - Художник\
• 🔋 Vojijpg - Бета-Тестер\
• 📰 [Viachek - Издатель](https://github.com/Vja0css "GitHub")\
• 🛡️ Coffee - Модератор

<img width="1700" height="1080" alt="1000701979" src="https://github.com/user-attachments/assets/18b12c00-3056-4c03-a79a-8859cb8995cd" alt="Стафф" />
<hr>

# ‧₊˚✧[Модинг]✧˚₊‧

<img width="108" height="108" alt="1000701980" src="https://github.com/user-attachments/assets/c2f51fdf-300a-4f17-ba3d-9acc0fcfb78c" alt="Привью мода." />

*• Текстура привью спавна.*

```lua
system.vibrate(9)
```
*• Пример кода для вибраций в режиме Lua.*

```html
data:text/html,<body bgcolor=red><hr2>М-да</hr2></body>
```
*• Пример кода для сайта в режиме HTML.*

```glsl
P_POSITION vec2 VertexKernel(P_POSITION vec2 position) {
    return position;
}
```
*• Код вершин шейдера воды.*

```glsl
P_COLOR vec4 FragmentKernel(P_UV vec2 texCoord) {

    texCoord.x += 0.01 * sin(texCoord.y * 25.0 + 4.0 * texCoord.x + CoronaTotalTime * 10.0);
    texCoord.y += 0.01 * cos(texCoord.x * 25.0 + 4.0 * texCoord.y + CoronaTotalTime * 10.0);

    P_COLOR vec4 texColor = texture2D(CoronaSampler0, texCoord);
    
    texColor.rgb -= sin(texCoord.y * 25.0 + 4.0 * texCoord.x + CoronaTotalTime * 10.0) * 0.05;
    
    P_DEFAULT vec4 adjLight = CoronaVertexUserData;
    adjLight.rgba /= 16.;
    
    P_DEFAULT float light = ((((1. - texCoord.x) * adjLight.r) + (texCoord.x * adjLight.g)) +
    (((1. - texCoord.y) * adjLight.b) + (texCoord.y * adjLight.a))) / 2. + 0.15;
    
    texColor.r *= light * 1.17;
    texColor.g *= light * 1.1;
    texColor.b *= light + 0.1 * (1. - light);

    return CoronaColorScale(texColor);
}
```
*• Код фрагмент шейдера воды.*


<img width="1701" height="958" alt="1000701985" src="https://github.com/user-attachments/assets/ba8487f1-86ce-4559-8cf3-a7093bdbb2b3" alt="Модинг."  />
<hr>
