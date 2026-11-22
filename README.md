# MiniGames

A MiniGames a saját készítésű, ingyenes mini játékaink gyűjteményének és letöltőoldalának projektje.

## Játék hozzáadása
Az `index.html` fájlban található `games` listához adj új elemet:
- `id`: egyedi azonosító
- `name`: játék neve
- `category`: kategória
- `icon`: emoji vagy ikon
- `description`: rövid leírás
- `status`: például „Fejlesztés alatt”
- `downloadUrl`: a feltöltött játékfájl relatív útvonala, például `./downloads/jatek.zip`

A letöltés gomb csak akkor jelenik meg, ha a `downloadUrl` mező ki van töltve. A kész játékokat a `downloads/` mappába töltsük fel, és csak saját vagy terjesztésre engedélyezett fájlokat tegyünk közzé.

## Jelenlegi állapot
Az oldal és a kategória-/keresőfelület elkészült. A mintakártyák fejlesztés alatt álló játékötletek; tényleges letölthető játékfájl még nincs feltöltve.
