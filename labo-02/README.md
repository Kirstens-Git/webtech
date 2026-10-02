# Labo 2 - reflecties

Naam: (Kirsten)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`:
        elk a element dat een kind is van een li dat een kind is van ul dat een kind is van nav dat een kind is van header.
- b. `article > p`: 
        de buitenste paragrafen in het article element.
- c. `.uren li:nth-child(3)`: 
        het derde kind onder de klasse uren.
- d. `h2 ~ p`: 
        elke p na h2 met dezelfde ouder.
- e. `.rassen li:first-child`: 
        het eerste kind onder de klasse rassen.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | green | herkomst | green | j |
| 2 | blue | volgorde | blue | j |
| 3 | blue | em = belangrijker | red | f |
| 4 | red | volgorde | red | j |
| 5 | blue | id = belangrijker | blue | j |
| 6 | blue | klasse v6 word niet gebruikt | blue | j |
| 7 | black | geen css regel -> browser standaard | red | f |
| 8 | blue | specifiteit | blue | j |
| 9 | red | specifiteit | red | j |
| 10 | green | specifiteit | green | j |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

Vraag 3: dacht dat klassen minder belangrijk waren dan standaard html tags.
Vraag 7: ik zag niet dat de kleur overgeërfd werd van het section element.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
        nav a omdat dat al het juiste deel van de pagina aanspreekt.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
