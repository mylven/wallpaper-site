# háttér

Reszponzív, magyar nyelvű háttérkép-galéria. Nincs szükség buildre vagy API-kulcsra: az `index.html` közvetlenül megnyitható böngészőben. A válogatott fotók az Unsplashről, a szabadon kereshető nagy felbontású képek pedig a Wikimedia Commons nyilvános API-ján keresztül töltődnek be, ezért internetkapcsolat szükséges.

## GitHub Pages publikálás

1. Hozz létre egy üres GitHub repository-t.
2. Töltsd fel a repository gyökerébe az `index.html` és a `README.md` fájlt.
3. A repository **Settings → Pages** oldalán válaszd a **Deploy from a branch** lehetőséget, majd a `main` ágat és a `/(root)` mappát.
4. Mentés után a GitHub Pages által megadott címen elérhető lesz az oldal.

## Keresés és képlicencek

Írj be bármilyen témát a keresőmezőbe, vagy válassz egy népszerű keresést. A keresés a Wikimedia Commons nagyméretű, folyamatosan bővülő fotóarchívumából kér le további nagy felbontású képeket, lapozható találatokkal. Néhány gyakori magyar kifejezés automatikusan angol keresőkifejezésre fordul, mivel az archívum fájlleírásainak többsége angol nyelvű. Internetkapcsolat szükséges.

A képek különböző szabad licencekkel érhetők el. Az előnézet az egyes képeknél feltünteti az alkotót, a Wikimedia Commons fájloldalát és az adott kép licencét. A nagy felbontású eredeti képet az **Eredeti kép** hivatkozás nyitja meg.

## Kiemelt képek bővítése

Az `index.html` fájlban található `wallpapers` listához adhatsz új Unsplash-képeket. Minden elemhez add meg a képazonosítót, a címet, a kategóriát és a kereshető kulcsszavakat (`tags`).
