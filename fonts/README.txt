ПАПКА ДЛЯ ОРИГИНАЛЬНЫХ ШРИФТОВ МАКЕТА
=====================================

В макете используются коммерческие шрифты Suisse Intl (Swiss Typefaces)
и Gilroy (Radomir Tinkov). Их нельзя скачивать с бесплатных «сборников»
шрифтов — только купить лицензию у правообладателя. Поэтому папка пустая.

Пока файлов нет, сайт показывает бесплатные похожие шрифты из Google Fonts:
  Suisse Intl  ->  Inter
  Gilroy       ->  Onest

Если у шрифта есть лицензия, положите сюда файлы ровно с такими именами
(формат WOFF2) — style.css подхватит их сам, менять код не нужно:

  SuisseIntl-Light.woff2      (Suisse Intl, начертание 300)
  SuisseIntl-Regular.woff2    (Suisse Intl, начертание 400)
  SuisseIntl-Medium.woff2     (Suisse Intl, начертание 500)
  SuisseIntl-SemiBold.woff2   (Suisse Intl, начертание 600)
  SuisseIntl-Bold.woff2       (Suisse Intl, начертание 700)
  Gilroy-Bold.woff2           (Gilroy, начертание 700)

Если шрифты уже установлены в системе (Suisse Intl / Gilroy), браузер
возьмёт их оттуда даже без файлов в этой папке (local() в @font-face).

Когда оригинальный Suisse Intl загрузился, script.js добавляет к <html>
класс fonts-original, и стили убирают небольшое сжатие букв (letter-spacing),
которое нужно только для замены Inter.

На странице сертификата в макете ещё встречаются Montserrat и Roboto —
это бесплатные шрифты, они подключены из Google Fonts.
