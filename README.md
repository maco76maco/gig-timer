# GIG TIMER 4.0

**Live Setlist & Stage Clock** – slovenská offline PWA pre kapely.

## Publikovanie na GitHub Pages

1. Na GitHube vytvor nový **verejný** repozitár, napr. `gig-timer`.
2. Nahraj **obsah tohto priečinka** priamo do koreňa repozitára (`index.html`, `sw.js`, `manifest.webmanifest`, obe ikony a `.nojekyll`). Nie samotný ZIP.
3. Otvor **Settings → Pages**. V časti **Build and deployment** vyber **Deploy from a branch**, vetvu **main** a priečinok **/(root)**; ulož.
4. Po nasadení otvor `https://TVOJE-MENO.github.io/gig-timer/` na Androide v Chrome.
5. V menu Chrome vyber **Inštalovať aplikáciu** (prípadne **Pridať na plochu**).
6. Pred prvým použitím v novej aplikácii importuj zálohu zo starej verzie (☁ ZÁLOHA → IMPORT).

## Dôležité

- **Pred prechodom exportuj zálohu** zo starej aplikácie. Úložisko lokálneho HTML a webovej PWA je oddelené.
- Údaje zostávajú uložené **lokálne v prehliadači**; GitHub ich neukladá ani nesynchronizuje. Pravidelne exportuj JSON zálohu.
- Screen Wake Lock vyžaduje HTTPS a podporovaný prehliadač. Ani potom nemusí byť vždy dostupný, napríklad pri šetrení batérie.
- Po prvom úspešnom načítaní a inštalácii by mala aplikácia fungovať offline. Pred koncertom to otestuj v režime lietadlo.
- Po úprave súborov v budúcnosti zvýš verziu `CACHE` v `sw.js`, aby sa obnovila offline cache.
- Pôvodný interný kľúč uložených dát a formát JSON záloh zostali zámerne nezmenené pre kompatibilitu.
