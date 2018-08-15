# Rafagas Mini-HOWTO

## Fonts de dades

* [Agregat blogs RSS](mapes_brut_20180706.opml), actualitzat a juliol del 2018.
* [Comptes que segueix @geoinquiets a Twitter](https://twitter.com/geoinquiets/following).
* A Reddit hi ha [/mapporn](https://www.reddit.com/r/MapPorn/), que també és a l'RSS, però sense imatges.
* [Menéame](https://www.meneame.net/) és un agregador salvatge i usualment apareixen coses de mapes relacionades amb política.
* Via Linkedin també arriben força enllaços, alguns des de fonts insospitades (aquesta font és difícil de despersonalitzar).

## Procediment

* Obres el **lector RSS** i vas llegint titulars. Si et fa el pes cliques l'enllaç, i si la notícia s'ho val copies la URL en un draft de **Gmail88.
* Vas llegint **Twitter** i fas el mateix.
* En acabat tries 3 o 4 enllaços del draft, fas les **captures de pantalla**, redactes la frase per a cada un i els programes a Gmail per enviar (ja no funciona i s'ha de fer a mà).
* Els copies a **Buffer** a l'slot corresponent per enviar per Twitter i Linkedin automàticament a l'hora programada.

Comptat i debatut al final són unes dues hores diàries de dedicació mitjana.

## Eines

* Lectors de RSS: des que va desaparèixer Google Reader la cosa està malament.
    * Windows: [Greatnews](http://www.curiostudio.com/), amb la bbdd en un drive per poder sincronitzar els diferents lectors (casa, feina, portàtil). Molt vell i qualsevol dia morirà ja que em sembla que només queda algú de Madrid fent manteniment mínim.
    * Linux: [FeedReader](https://jangernert.github.io/FeedReader/). Recomanat per similitud al reader de Windows.
* Clients de Twitter:
    * [Tweetdeck](https://tweetdeck.twitter.com/) permet gestionar diferents comptes i columnes,
* Compte de Gmail, ya tal.
* Captures de pantalla:
    * Fetes a Firefox amb [Page Saver WE].(https://addons.mozilla.org/en-US/firefox/addon/pagesaver-we/)
    * Reescalades amb un action de Photoshop.
* [Buffer](https://buffer.com/app) té compte gratuït que permet schedule de fins a 10 tuits. Fent servir la versió pro per poder tenir buffer il·limitat.


## Com repartir l'esforç?

Proposta:

1. Particionar els canals a seguir: un encarregat de seguir el twitter, un altre els RSS, etc.
1. Particionar en el temps, establint un calendari on s'hi apuntin voluntaris per cobrir diferents períodes.
1. Anar omplint un document compartit (o el buffer).
1. Un bot/cron que cada dia agafi el llistat d'entrades, n’extregui les X primeres, i les pengi en format tuit (generant la captura de forma automàtica), envii el mail i els tregui de la llista de pendents.

La “única” feina que tindríem és la de vigilar que el document d’entrades mai quedi buit. No estaria malament tenir una web, a github pages mateix, on es pugui buscar entre les entrades ja enviades i un formulari on enviar-ne però igual això ja seria per una 2a fase.
