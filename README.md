# LaTeX-HSE-SPB-beamer
[Официальный шаблон презентации НИУ ВШЭ](https://www.hse.ru/info/brandbook/#templates) в beamer (LaTeX) с корректировками для Санкт-Петербурга и Ubuntu 

Что скорректировано для Санкт-Петербурга: 
- Скачаны [питерские лого из брендбука](https://www.hse.ru/info/brandbook/#campus). Файлы 01_Logo_HSE_SPB_full_eng_CMYK.pdf, 01_Logo_HSE_SPB_full_rus_CMYK.pdf помещены в папку HSE-theme. Для обращения к этим файлам скорректирована строчка 110 в файле HSE-theme/beamerthemeHSE.sty

Что скорректировано для Ubuntu: 
- В файлах example-beamer-HSE-ru.tex, example-beamer-HSE-eng.tex команда \setmonofont{Courier New} заменена на \setmonofont{Liberation Mono}

Что еще понадобиться сделать для Ubuntu:
- Скачать шрифт [HSE_Sans из брендбука](https://www.hse.ru/info/brandbook/#font) и поместить .otf файлы в /usr/share/fonts/opentype/HSE_Sans
- Если не сделано, установить xetex: sudo apt install texlive-xetex
