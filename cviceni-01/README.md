# Cvičení 1

Tady nějaká změna.
Tady změna 2.
Zkusíme si vytvořit jednoduchou aplikaci v Reactu zcela z nuly. Zatím React použijeme pouze tak, jak jsme se učili, a nebudeme používat nic pokročilejšího.

1. Ve své složce, kde si vytváříš projekty pro tento kurz, si pomocí `create-czechitas-app` vyrob nový projekt. Nazvi ho třeba `vizitka`.

1. Pomocí `npm run start` v terminálu zkus projekt spustit, abyses přesvědčila, že všecno správně funguje.

1. Generátor `create-czechitas-app` je dobrý pomocík a vytvořil nám jednoduchou vzorovou aplikaci. My ji nyný ale nepotřebujeme, takže smažeme kompletně obsah souboru `index.jsx`. Soubor v projektu ponechej, jen vymaž všechno, co je v něm napsané.

1. Do souboru `index.jsx` vlož následující kód:

   ```jsx
   import React from "react";
   import { render } from "react-dom";

   render(
     <div className="container">
       <header>
         <h1>Jméno Příjmení</h1>
       </header>
       <main>
         <p>Něco málo o mně.</p>
       </main>
     </div>,
     document.querySelector("#app")
   );
   ```

1. Zkus v nadpisu stránky změnit svoje jméno a podívej se do prohlížeče, zda se změna projevila.

1. Vylepši stránku tak, že obsah JSX uložíš do samostatné proměnné uvnitř `index.jsx` a tuto proměnnou pak pak použiješ ve funkci `render`.

1. Vytvoř dvě další proměnné - do jedné ulož svoje jméno, do druhé ulož text s krátkým popisem o sobě. Použij tyto proměnné uvnitř JSX místo napevno zadaného jména v nadpisu a místo textu v odstavci.

1. Pomocí `import` připoj do stránky soubor `style.css`. V CSS souboru vytvoř třídu `description` a nastav v ní `font-style` na hodnotu `italics`. Pomocí `className` přidej tuto třídu na odstavec s textem o tobě.
