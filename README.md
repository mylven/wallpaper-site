# Lumora

Reszponzív, magyar nyelvű háttérkép-galéria Lumora néven. Nincs szükség buildre vagy API-kulcsra: az `index.html` közvetlenül megnyitható böngészőben. A nyílt licencű képeket az Openverse nyilvános keresője gyűjti össze több tucat forrásból, köztük a Flickr, a Wikimedia Commons és múzeumi gyűjtemények kínálatából. A kiemelt fotók az Unsplashről származnak. Az internetkapcsolat szükséges.

## GitHub Pages publikálás

1. Hozz létre egy üres GitHub repository-t.
2. Töltsd fel a repository gyökerébe az `index.html` és a `README.md` fájlt.
3. A repository **Settings → Pages** oldalán válaszd a **Deploy from a branch** lehetőséget, majd a `main` ágat és a `/(root)` mappát.
4. Mentés után a GitHub Pages által megadott címen elérhető lesz az oldal.

## Keresés és képlicencek

Írj be bármilyen témát a keresőmezőbe, válassz kategóriát vagy próbálj ki egy népszerű keresést. A képarány (fekvő, álló, négyzet), a képforrás és a rendezés is szűrhető. A kereső oldalanként 20 képet tölt be, és további oldalakon lapozható. Néhány gyakori magyar kifejezés automatikusan angol keresőkifejezésre fordul.

A keresés az Openverse API-t használja, amely nyíltan licencelt, többek között Creative Commons és közkincs képeket indexel különböző forrásokból. A képek licence és alkotója eltérő lehet; ellenőrizd az egyes képek előnézetében a forrásoldalt és a licencet, mielőtt felhasználnád őket. A **Eredeti kép** hivatkozás megnyitja a forrás nagy felbontású fájlját.

## Kiemelt képek bővítése

Az `index.html` fájlban található `wallpapers` listához adhatsz új Unsplash-képeket. Minden elemhez add meg a képazonosítót, a címet, a kategóriát és a kereshető kulcsszavakat (`tags`).
