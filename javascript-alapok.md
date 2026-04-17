# JavaScript alapok

A JavaScript egy programozási nyelv, amelyet leggyakrabban weboldalakon használnak interaktív működéshez. Segítségével kezelhetünk eseményeket, módosíthatjuk a HTML-t, és logikát adhatunk az alkalmazásokhoz.

## Miről szól ez az oldal?

Ez az összefoglaló a legfontosabb JavaScript alapokat mutatja be röviden:

- változók
- adattípusok
- feltételek
- ciklusok
- függvények
- tömbök és objektumok
- DOM kezelés
- eseménykezelés

## Mi az a JavaScript?

A JavaScript a böngészőben és szerveroldalon is futtatható nyelv. Böngészőben például gombkattintásokat kezelhetünk vele, vagy dinamikusan változtathatjuk az oldal tartalmát.

### Példa

```js
console.log("Hello JavaScript!");
```

## Változók

A változókban adatokat tárolunk. JavaScriptben leggyakrabban a `let` és a `const` kulcsszavakat használjuk.

### Példa

```js
let nev = "Anna";
const eletkor = 25;

console.log(nev);
console.log(eletkor);
```

## Adattípusok

A JavaScript több alapvető adattípust ismer, például szöveget, számot és logikai értéket.

### Példa

```js
let szoveg = "alma";
let szam = 42;
let igazHamis = true;

console.log(typeof szoveg);
console.log(typeof szam);
console.log(typeof igazHamis);
```

## Feltételek

A feltételekkel eldönthetjük, hogy egy adott helyzetben melyik kódrészlet fusson le. Erre gyakran az `if` szerkezetet használjuk.

### Példa

```js
let homerseklet = 18;

if (homerseklet > 20) {
  console.log("Meleg van");
} else {
  console.log("Nincs meleg");
}
```

## Ciklusok

A ciklusokkal ismétlődő feladatokat hajthatunk végre. Az egyik legismertebb a `for` ciklus.

### Példa

```js
for (let i = 1; i <= 3; i++) {
  console.log("Lépés:", i);
}
```

## Függvények

A függvények újrahasznosítható kódrészek. Paramétereket fogadhatnak, és visszaadhatnak eredményt.

### Példa

```js
function koszones(nev) {
  return "Szia, " + nev + "!";
}

console.log(koszones("Péter"));
```

## Tömbök

A tömbök több érték tárolására alkalmasak egyetlen változóban. Hasznosak listák kezelésére.

### Példa

```js
let gyumolcsok = ["alma", "körte", "szilva"];

console.log(gyumolcsok[0]);
console.log(gyumolcsok.length);
```

## Objektumok

Az objektumok kulcs-érték párokban tárolják az adatokat. Gyakran használjuk összetartozó adatok rendezésére.

### Példa

```js
const felhasznalo = {
  nev: "Kata",
  kor: 30,
  aktiv: true
};

console.log(felhasznalo.nev);
console.log(felhasznalo.kor);
```

## DOM kezelés

A JavaScript képes módosítani a weboldal elemeit. Ezt a DOM-on keresztül érjük el.

### Példa

```html
<p id="uzenet">Eredeti szöveg</p>
```

```js
document.getElementById("uzenet").textContent = "Új szöveg";
```

## Eseménykezelés

Eseménykezeléssel reagálhatunk például kattintásra vagy billentyűleütésre.

### Példa

```html
<button id="gomb">Kattints</button>
```

```js
document.getElementById("gomb").addEventListener("click", function () {
  alert("Rákattintottál a gombra.");
});
```

## Összefoglalás

A JavaScript alapjai közé tartoznak:

- változók
- adattípusok
- feltételek
- ciklusok
- függvények
- tömbök
- objektumok
- DOM kezelés
- eseménykezelés

Ezekre épül a legtöbb webes JavaScript alkalmazás.

## Következő lépés

Ha tágabb kontextus kell hozzá, nézd meg a [Web fejlesztés](web.md) oldalt is.
