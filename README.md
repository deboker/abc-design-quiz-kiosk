# ABC Design Quiz Kiosk

Webová aplikácia pre dotykový kiosk na veľtrhoch. Návštevník odpovie na šesť otázok, vyplní kontaktné údaje a odošle ich tímu ABC Design. Súčasťou aplikácie je interný prehľad odpovedí s exportom do CSV. Po nečinnosti sa kvíz automaticky vráti na úvodnú obrazovku.

**Živá aplikácia:** [abc-design-quiz-kiosk.web.app](https://abc-design-quiz-kiosk.web.app/)

## Použité technológie

| Oblasť | Technológia | Využitie |
| --- | --- | --- |
| Používateľské rozhranie | React 19, TypeScript | Obrazovky kvízu a správa stavu aplikácie |
| Zostavenie aplikácie | Vite 8 | Vývojový server a produkčný build |
| Formulár | React Hook Form | Kontaktný formulár a kontrola vstupov |
| Animácie | Framer Motion | Prechody a pohyb prvkov |
| Ukladanie dát | Firebase Cloud Firestore | Odpovede a kontaktné údaje |
| Hosting | Firebase Hosting | Zverejnenie zostavenej aplikácie |
| Štýly | CSS | Rozloženie a vzhľad pre dotykové ovládanie |

## Ako funguje

1. Návštevník spustí kvíz a odpovie na otázky.
2. Vyplní kontaktný formulár a potvrdí súhlas so spracovaním údajov.
3. Aplikácia uloží odpovede do Cloud Firestore.
4. Interný prehľad umožňuje zobraziť záznamy a exportovať ich do CSV.

Produkčná verzia sa zostavuje príkazom `npm run build` a publikuje na Firebase Hosting príkazom `firebase deploy --only hosting`.

Tento GitHub repozitár je určený len pre README s opisom projektu. Zdrojový kód aplikácie tu nie je zverejnený.
