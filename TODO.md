# POBP

Redesign i przygotowanie trzech oddzielnych sekcji strony; odświeżenie identyfikacji wizualnej.

## architecture v2

urls:

- /
- /pl/zabytki
    - /pl/zabytki/obiekt-zabytkowy-1
    - /pl/zabytki/obiekt-zabytkowy-2
- /projekty
    - /projekty/obiekt-1
    - /projekty/obiekt-2
- /kajaki
    - /kajaki/wyprawa-1
    - /kajaki/wyprawa-2

## architecture

Use collections instead of posts http://jekyllrb.com/docs/collections/
https://www.sylvaindurand.org/making-jekyll-multilingual/

- root page
    - language select (optional, bold/hide current)
        - english
        - polski
        - deutsch
    - category select (bold current)
    - content
        - featured project (root)
        - selected project
        - category listing
        - contact
        - offer
    - contact
    - offer + short about
    - other places select (bold/hide current)
        - zabytki
        - projekty w polsce
        - kajaki

## brief - strona 1: zabytki

Wymagania:
- CMS
- multi języki (niemiecki, angielski i polski)
- kilka twarzowych projektów dokładnie opisanych
- oferta

Cel:
- przedstawicielstwo producentów materiałów dot. zabytków za granicą

## brief - strona 2: pozostałe projekty

Wymagania:
- CMS
- jeden język (polski)
- kategorie projektów

Cel:
- dokumentacja polskich realizacji

## brief - strona 3: kajaki hobby

Wymagania:
- CMS
- jeden język

Cel:
- pokazanie obecności w Polsce i Niemczech
- rodzinny biznes z charakterem


To check:
- http://www.hellermanus.com/portfolio.html
- http://conixrdbm.com/portfolio-category/proj-renovation/?lang=en
- http://www.berglandandcram.com/sustainability
