# Koťata a kočky

Jednoduchá desková hra pro dva hráče na jednom počítači, inspirovaná deskovkou Boop. Celé je to jeden HTML soubor s vanilla JavaScriptem, bez závislostí a bez instalace.

## Spuštění

Stáhni `kotata-a-kocky.html` a otevři ho v prohlížeči. Hrajete střídavě na jednom PC.

## Pravidla

- Deska má 6×6 polí. Každý hráč (žlutý a šedý) začíná s 8 koťaty.
- Na tahu položíš kotě (nebo kočku, pokud nějakou máš v zásobě) na volné pole.
- Všech 8 sousedních kusů se odsune o jedno pole dál od nově položeného kusu, včetně tvých vlastních.
  - Položené **kotě** odsouvá jen koťata.
  - Položená **kočka** odsouvá koťata i kočky.
  - Kus, za kterým je obsazené pole, se nepohne.
  - Kus, který spadne z desky, se vrátí majiteli do zásoby.
- Řada 3 tvých kusů (i diagonálně, i kombinace koťat a koček) zmizí z desky a za každý z těch tří kusů dostaneš do zásoby jednu dospělou kočku.
- Pokud nemáš co položit, povýšíš jedno své kotě na desce na kočku a tu pak položíš.

## Konec hry

Vyhrává hráč, který:

- vytvoří řadu 3 koček, nebo
- má na desce všech 8 svých koček.

## Ovládání

Kliknutím vybereš, jestli kladeš kotě nebo kočku, a pak klikneš na volné pole.
