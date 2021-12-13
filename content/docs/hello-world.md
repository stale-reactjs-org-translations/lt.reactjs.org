---
id: hello-world
title: Hello World
permalink: docs/hello-world.html
prev: cdn-links.html
next: introducing-jsx.html
---

Paprasčiausias React pavyzdys:

```js
ReactDOM.render(
  <h1>Labas, pasauli!</h1>,
  document.getElementById('root')
);
```

Jis atvaizduoja „Labas, pasauli!“ antraštę puslapyje.

[](codepen://hello-world)

Paspaudę viršuje esančią nuorodą, atidarysite internetinį teksto redaktorių. Nedvejokite ir pakeiskite kodą bei pažiūrėkite, kokį rezultatą išvysite ekrane. Dauguma puslapių šiame gide turi redaguojamus pavyzdžius.


## Kaip skaityti šį gidą {#how-to-read-this-guide}

Šiame gide nagrinėsime pagrindinius React aplikacijų kūrimo blokus: elementus ir komponentus. Juos įvaldžius, galėsite sukurti sudėtingas aplikacijas iš smulkių ir daugkartinio naudojimo gabalėlių.

>Patarimas
>
>Šis gidas skirtas žmonėms, kuriems patinka **mokytis pagrindus žingsnis po žingsnio**. Jeigu labiau mėgstate mokytis iš praktinių pavyzdžių, peržiūrėkite [praktinį gidą](/tutorial/tutorial.html). Abu šaltiniai gali pasirodyti vienas kitą papildantys.

Šis puslapis yra pirmasis teorinio gido skyrius, kuriame išmoksite React pagrindus. Nuorodos į visus skyrius pateikiamos puslapio dešinėje esančioje navigacijoje. Jeigu esate atsidarę šį puslapį mobiliąjame įrenginyje, pasiekti navigaciją galite paspaudę ekrano apatiniame dešiniame kampe esantį mygtuką.

Kiekvienas skyrius yra paremtas anktesniuose skyriuose pristatyta informacija. **Išmokti nemažai apie React galite perskaitę šio gido skyrius tokia tvarka, kokia jie yra pateikiami dešinėje esančioje navigacijoje.** Pavyzdžiui, po šio, kitas skyrius yra [„Įvadas į JSX“](/docs/introducing-jsx.html).

## Reikalingas žinių lygis {#knowledge-level-assumptions}

React yra JavaScript biblioteka, todėl yra būtinas JavaScript programavimo kalbos pagrindų mokėjimas. **Jeigu nesijaučiate pankankamai užtikrintai, rekomenduojame [peržvelgti JavaScript apžvalgą](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript), kuri geriau padės suprasti savo žinių lygį** ir neleis pasimesti skaitant šį gidą. Tai gali užtrukti nuo 30 min iki 1 valandos, tačiau nereikės jaustis, jog mokotės JavaScript programavimo kalbos ir React vienu metu.

>Pastaba
>
<<<<<<< HEAD
>Šis gidas pateikiamuose pavyzdžiuose retkarčiais naudoja naujesnią JavaScript sintaksę. Jeigu per paskutiniuosius kelis metus neteko naudoti JavaScript programavimo kalbos, [šie trys punktai](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) turėtų padėti su tuo lengviau susidoroti.
=======
>This guide occasionally uses some newer JavaScript syntax in the examples. If you haven't worked with JavaScript in the last few years, [these three points](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) should get you most of the way.
>>>>>>> 014f4890dc30a3946c63f83b06883241ddc9bc75


## Pradėkime! {#lets-get-started}

Žemiau, prieš pat puslapio pabaigą, rasite nuorodą į [kitą šio gido skyrių](/docs/introducing-jsx.html).


