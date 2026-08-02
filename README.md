# Grille Studio — parametrický generátor reproduktorových mriežok

Webový nástroj na návrh krytov reproduktorov potiahnuteľných látkou. Bež v prehliadači, nič sa neinštaluje, výstupom je binárne STL pre 3D tlač.

**Živá verzia:** https://miloskral.github.io/repromriezky/

## Čo to vie

Pôdorys kruh alebo obdĺžnik so zaoblenými rohmi. Mriežka zo šesťhranov, osemhranov so štvorcami v medzerách, alebo kruhov, s nastaviteľnou veľkosťou otvoru a hrúbkou mostíkov. Vyklenutie guľovým vrchlíkom alebo kužeľom, ktoré plynulo prechádza cez plný rámik až na vonkajšiu hranu. Vonkajšia hrana je zaoblená polovičnou elipsou, aby sa cez ňu látka prehla bez ostrého lomu.

Magnetové lôžka sa umiestnia po obvode rovnomerne, len na rovné hrany, alebo do rohov. Vrch lôžka kopíruje klenutie a je zapustený v doske, takže cez predok ani cez zaoblenie nepresvitá. Lôžko sa dozadu posunie len o toľko, koľko treba, aby kalíšok neprerazil prednú plochu. K dispozícii je aj export protikusu a vŕtacej šablóny pre ozvučnicu so zrkadlenými pozíciami magnetov.

## Presnosť siete

Sieť sa pred vyklenutím delí červeno-zeleným delením, konformne — bez T-uzlov, takže v STL nevznikajú trhliny. Dĺžka hrany sa počíta z tolerancie priehybu tetivy, takže plochá klenba sa delí menej než strmá a plochý profil sa nedelí vôbec. Prepad hornej plochy pod ideálnou klenbou je typicky pod 0,05 mm.

## Tlač a montáž

Jednotky sú milimetre, os +Z je predná klenutá strana. Tlač lícom nadol, bez podpier. Vôľa na priemer magnetu 0,2 mm pre lisovaný spoj, 0,4 mm ak lepíš. Pri spoji magnet ↔ magnet musia byť všetky magnety v kryte rovnakým pólom von a v ozvučnici opačným, inak sa kryt pri pootočení odpudí.

## Licencia

MIT — pozri [LICENSE](LICENSE).

---
Navrhol Miloš Kráľ
