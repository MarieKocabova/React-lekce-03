# Cvičení 3 - Jednoduchý web

Vytvoř v Reactu stránku složenou z komponent.

1. Ve své složce, kde si vytváříš projekty pro tento kurz, si pomocí `create-czechitas-app` vyrob nový projekt. Nazvi ho třeba `miniweb`.

1. Pomocí `npm run start` v terminálu zkus projekt spustit, abyses přesvědčila, že všecno správně funguje.

1. Vytvoř hlavní komponentu `App`, která bude obsahovat konstru naší stránky. Tento úkol je jednoduchý, protože v projektu vytvořeném pomocí `create-czechitas-app` už komponenta je, stačí vyměnit její obsah.

1. Komponenty jsou jenom funkce, které vracejí JSX a my je pak v jiném JSX (např. uvnitř komponenty `App`) můžeme používat jako HTML značky. Funkce komponent pojmenováváme s velkým počátečním písmenem a jako HTML yna4kz pak pou69v8me tak0 s prvn9m velk7m písmenem. `<Header>` je pro React námi vytvořená komponenta, zatímco `<header>` je běžná HTML značka.

1. Vytvoř v projektu další 3 komponenty: `Header`, `Main` a `Footer`.

	- `Header` bude obsahovat hlavičku stránky.
	- `Main` bude představovat hlavní obsah - alespoň jeden nadpis a dva odstavce textu.
	- `Footer` bude jednoduchá patička stránky.

	Obsah si vymysli zcela podle libosti.

1. Přidej vytvořené komponenty do komponenty `App`. Naše aplikace bude tvořená hlavičkou, obsahem a patičkou pod sebou.

1. Komponentu `App` pomocí funkce `render` vykresli do stránky.

1. Pokud máš čas a chuť, vyrob jednoduchý CSS, aby aplikace lépe vypadala. Nezapomeň CSS připojit do stránky.
