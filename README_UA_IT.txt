МІСІЯ УКРАЇНА / MISSIONE UCRAINA
Версія 3.0 · Insieme Per Ucraina

ЛОКАЛЬНА ГРА НА MAC / GIOCO IN LOCALE SU MAC
1. Розпакуйте ZIP-архів.
2. Відкрийте index.html у Safari або Chrome.
3. Для гри не потрібні інтернет, WordPress або сервер.
4. Прогрес зберігається тільки у вашому браузері (localStorage).

СЕРТИФІКАТ / CERTIFICATO
- Сертифікат один для всіх, без імені та email.
- Кнопка «Завантажити сертифікат PNG» завантажує ТІЛЬКИ сертифікат у файл PNG.
- Кнопка «Сертифікат у PDF / друк» відкриває системний діалог друку. На Mac: PDF → Save as PDF.
- У друк потрапляє лише сертифікат, а не вся сторінка гри.

FACEBOOK
- Після розміщення гри на публічному HTTPS-сайті кнопка Facebook відкриває вікно поширення посилання.
- Якщо гру відкрито локально (file://), Facebook не може поширити локальний файл. Тому з’являється текст готового допису і кнопка відкриття Facebook.
- Для красивої картки Facebook можна пізніше додати публічний og:image з HTTPS URL. Прев’ю формує Facebook, воно може кешуватися.

WORDPRESS
Варіант без плагінів:
1. Створіть у корені сайту на хостингу папку /misiia-ukraina/.
2. Завантажте у неї файл index.html.
3. Гра матиме адресу https://ВАШ-ДОМЕН/misiia-ukraina/.
4. У WordPress додайте сторінку та блок «Custom HTML» з кодом:

<iframe src="/misiia-ukraina/" title="Місія Україна / Missione Ucraina" style="width:100%;height:1000px;border:0;border-radius:16px" loading="lazy"></iframe>

Рекомендація: для гри на весь екран зручніше дати посилання «Грати» на окрему сторінку /misiia-ukraina/.

ПОСИЛАННЯ НА ДОПОМОГУ
Для активації посилань на донат і волонтерство відкрийте index.html у текстовому редакторі,
знайдіть рядок const CONFIG = { donateUrl: '', volunteerUrl: '' };
і вставте тільки перевірені офіційні URL. Без цього кнопки сховані.

PRIVACY
Гра не збирає імена, email або дані оплати. Дані про прогрес лише в localStorage браузера.

NOTE IN ITALIANO
Il gioco funziona offline aprendo index.html. Per pubblicarlo su WordPress carica il file
in una cartella accessibile via HTTPS. Il certificato è uguale per tutti: nessun nome o email.
Il pulsante PNG scarica solo il certificato; il pulsante PDF/stampa stampa solo il certificato.
La condivisione diretta su Facebook funziona con un URL pubblico, non con file locali.
