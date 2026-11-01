Сайт «Аргументы для папы»
=========================

Что внутри
- index.html  сам сайт
- macbook.glb, airpods.glb, gamingpc.glb  3D-модели (должны лежать рядом с index.html)

Как открыть
Если просто дважды щёлкнуть по index.html, браузер не загрузит 3D-модели
(это защита браузера), и вместо них будут упрощённые фигуры.
Нужен интернет (библиотека three.js и шрифты грузятся из сети) и один из способов:

1) Выложить в интернет (проще всего).
   Открой https://app.netlify.com/drop и перетащи всю папку papa-site.
   Получишь ссылку, которую можно отправить папе.

2) Запустить у себя на компьютере.
   Открой терминал в папке papa-site и выполни:
   python3 -m http.server 8000
   Затем открой в браузере http://localhost:8000

Авторы 3D-моделей (по лицензии нужно указывать, на сайте это есть внизу страницы)
- "macbook pro M3 16 inch 2024" by jackbaeten, CC-BY-4.0
  https://sketchfab.com/3d-models/macbook-pro-m3-16-inch-2024-8e34fc2b303144f78490007d91ff57c4
- "AirPods Max" by Bernardo Ferreira Baptista, CC-BY-NC-4.0 (только некоммерческое использование)
  https://sketchfab.com/3d-models/airpods-max-5656bcc0034c4f3bb86e30cae0a0a596
- "Custom Gaming PC" by Yolala1232, CC-BY-4.0
  https://sketchfab.com/3d-models/custom-gaming-pc-1a24273417534f69afa0f7c62b643ffc
Модели упрощены, чтобы быстро грузиться в браузере.
