# háttér

Reszponzív, magyar nyelvű háttérkép-galéria. Nincs szükség buildre vagy API-kulcsra: az `index.html` közvetlenül megnyitható böngészőben. A fotók az Unsplashről töltődnek be, ezért használatukhoz internetkapcsolat szükséges.

## GitHub Pages publikálás

1. Hozz létre egy üres GitHub repository-t.
2. Töltsd fel a repository gyökerébe az `index.html` és a `README.md` fájlt.
3. A repository **Settings → Pages** oldalán válaszd a **Deploy from a branch** lehetőséget, majd a `main` ágat és a `/(root)` mappát.
4. Mentés után a GitHub Pages által megadott címen elérhető lesz az oldal.

## Kereshető képek bővítése

Az `index.html` fájlban található `wallpapers` listához adhatsz új képeket. Minden elemhez add meg az Unsplash-kép azonosítóját, a címet, a kategóriát és a kereshető kulcsszavakat (`tags`).
