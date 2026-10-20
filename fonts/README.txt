ПАПКА ШРИФТОВ САЙТА
===================

В макете используются коммерческие шрифты Suisse Intl (Swiss Typefaces)
и Gilroy (Radomir Tinkov). Их нельзя скачивать с бесплатных «сборников»
шрифтов — только купить лицензию у правообладателя, поэтому их здесь нет.

Вместо них сайт использует бесплатные шрифты из Google Fonts
(лицензия SIL Open Font License 1.1 — можно свободно использовать на сайте),
файлы лежат прямо в этой папке, интернет для них не нужен:

  Suisse Intl  ->  Manrope (начертания 300–700, вариативный шрифт)
      Manrope-cyrillic.woff2   — русские буквы
      Manrope-latin.woff2      — латиница, цифры, знаки
      OFL-Manrope.txt          — лицензия

  Gilroy       ->  Onest Bold (700)
      Onest-Bold-cyrillic.woff2
      Onest-Bold-latin.woff2
      OFL-Onest.txt            — лицензия

Подключение — в начале style.css (@font-face), переменные --font-main
и --font-accent. Если Gilroy установлен в системе, браузер возьмёт его
(local() в @font-face), иначе — Onest.

На странице сертификата в макете ещё встречаются Montserrat и Roboto —
это бесплатные шрифты, они подключены из Google Fonts (ссылка в <head>).
