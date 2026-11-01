# WCAG Audit 

Doe een WCAG audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

De instructies van deze opdracht staan in [WIKI](https://github.com/fdnd-task/wcag-audit/wiki).


### Geteste website & Screenshot
De geteste website is **[YoungLA Europe](https://youngla.com)**. Dit is een populaire, internationale lifestyle- en sportkledingwebshop die zich richt op fitnesskleding en streetwear voor zowel heren als dames. De homepage toont drukke productgrids met diverse collecties, maatknoppen en dynamische carrousels.

---
Ik heb een WCAG audit gedaan van YOUNGLA website gedaan

### Lighthouse Accessibility Testresultaat
<img width="1470" height="956" alt="Scherm­afbeelding 2026-11-01 om 23 17 37" src="https://github.com/user-attachments/assets/e2e6f283-3f5b-4a96-b3b4-dcce11a7f5f2" />

<img width="590" height="295" alt="Scherm­afbeelding 2026-11-01 om 23 18 48" src="https://github.com/user-attachments/assets/ff2ed557-2199-4357-8a87-6ceb82688726" />

---

### Samenvatting van de testbevindingen
Uit de 5 uitgevoerde audits zijn de volgende belangrijkste knelpunten naar voren gekomen:

- Visueel contrast: Teksten op actie-badges (zoals "SALE") hebben te weinig contrast met hun achtergrond, wat ze slecht leesbaar maakt.
- Toetsenbord-blokkade: De uitklapmenu's voor kledingcategorieën openen alleen met een muis-hover en zijn onbereikbaar via de Tab-toets.
- Voorleesfouten: Screenreaders lezen vreemde codes voor bij de kleurselectie (zoals "[x] Black Wash") in plaats van bruikbare knoppen.
- Ontbrekende labels: Het invoerveld voor de nieuwsbrief mist een officiële naam in de code, waardoor hulpsoftware het doel van het veld niet begrijpt.
- Koppenhiërarchie: De volgorde van de koppen springt onlogisch door elkaar, waardoor blinde gebruikers het overzicht op de pagina verliezen.

Voor de volledige documentatie, codevoorbeelden en gedetailleerde oplossingen per audit kun je de uitgebreide pagina's bekijken in de 

(https://github.com/mikahartono007/wcag-audit/wiki/WCAG-audit-van-youngla-website)


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
