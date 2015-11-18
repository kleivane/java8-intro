# Java 8 - teknisk hjørne

* Sjekk ut vekat java8 hidden gems,
* API design

## Temaer

    Project Lambda

* 3 min: Lambdas - behavior passing
    - HENRIK
* 7 min: Streams
    - TINE
    - når bruker vi hvilken? 
    - filter, map, reduce
    - collect, 
        - toList, groupingBy, mappingBy
        - joining, counting
    - For each -> bør denne brukes mindre enn i dag? 
    - Parallellisering er mulig, men bør ikke være fokus
    - Returnere streams bør være ok
    - Eksempel: modig.lang til java8

* 3 min: Optionals
    - HENRIK: 
    - ikke meningen å bruke overalt. Kun en returtype der hvor 
"tomt resultat" er et forventet resultat
    - hvordan returnere noe tomt?
    - Aldri en optional collection, null-resultat -> kommer til å gi nye code smells :p
    - Eksempel: modig.lang til java8

* 2 min: Sortering
    - TINE
    - comparator.comparing(Person::getName).thenComparing
        - sjekk ut nullhåndteringen her 



* 5 min: hva skjer med modig.lang nå
    - snakke med Kai/Wang?
    - on -> streams
    - optional -> tilsvarende i java8

Tine mailer Kai/Wang om møte denne uka

## Namedropping
Hva med nytt date API?
* Map-interface
    - computeIfAbsent(k, function).add(value)

PermGen XX:PermSize forsvinner 

Valgt bort?
* Static methods in interfaces
* Default methods
* Tuples og Functions

Oppslagsverk: 
* Bok: https://leanpub.com/whatsnewinjava8
* Kodeeksempler: https://github.com/winterbe/java8-tutorial/blob/master/README.md
