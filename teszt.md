# Teszt

Név: Patocskai Erik

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
Egy commit előkészíti a fájlt a push-oláshoz. A staging are-ban lévő fájlokban a változásokat jegyezhetjük le benne. Amég nem push-oljuk, lokálisan tárolja az adatokat, majd pusholás után a távoli szerveren is meg fog jelenni. Bármikor átállhatunk bármelyik commit-ra.

1. Mi a különbség a `fetch` es `pull` git parancsok között?
A git fetch megmutatja a különbségeket a lokálisan tárolt és a szerveren tárolt branch között. Nem módosítja a lokális fájlokat.
A pull letölti a változásokat a távoli repóból és módosítja a lokális fájlokat is.

1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
-Untracked
-Tracked
-Unstaged
-Staged
-Modified
-Unmodified

1. Hogyan jutunk egy másolathoz egy repóról?
Git clone paranccsal tudunk egy helyi másolatot készíteni.

1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
Ilyenkor conflict-ok keletkeznek. Addig nem tudjuk push-olni a fájlt, amég ezeket fel nem oldottuk. Ilyenkor át kell nézni az egész fájlt és el kell döntenünk mely változásokat tartjuk meg. Ha feloldottuk az összeset, push-olhatjuk a fájlt.

1. Mi az a `HEAD` és mi a jelentősége?
A HEAD megmutatja, hogy éppen melyik commit-on állunk a branch-en. Alapértelmezetten a HEAD a legutolsó commit.

1. Mi a célja a branch-elésnek?
Hogy ne mindenki egy branch alatt dolgozzon és átláthatóbb legyen a szoftverfejlesztés.
A feature-öknek külön branchet tudunk adni, így kevesebb lesz a conflict-ok száma is.

1. Hogyan lehet összehasonlítani file-ok változásait, mire tudjuk még ezt a kimenetet használni?
Git status-szal tudom megnézni
A git diff paranccsal tudjuk megnézni a fájlon, commit-okban, branch-esn történt változásokat.


1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?
Git log-gal ki tudom listázni az összes eddigi commit-ot. Ennek segítségével látjhatjuk ki milyen feature-ön dolgozott, mit és mikor módosított az adott fájlon. Ha valami eltört a fájlban, a git log segítségével vissza tudunk állni egy előző commit-ra, ahol még működött minden.

1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
Git status



commit feeeb71f881e0edcff76d51722e85e880231a59d
