# Testprojekt: Ärendehantering

Ett litet portfolio-projekt som visar hur jag strukturerar manuell testning av ett fiktivt ärendehanteringssystem.

> **Viktigt:** Detta är ett självständigt övningsprojekt med påhittade krav och testdata. Det är inte ett riktigt myndighetssystem och innehåller ingen verklig personinformation.

## Syfte
Visa exempel på:
- testplanering och avgränsning
- testfall utifrån krav
- positiva och negativa testscenarier
- testdata i JSON-format
- enkel felrapportering
- riskbaserad prioritering

## Scenario
En handläggare använder ett ärendehanteringssystem för att söka fram ärenden och kontrollera deras status. I detta projekt utgår testningen från ett fiktivt kravunderlag.

## Projektstruktur
```text
portfolio-arendehantering/
├── README.md
├── testdocumentation/
│   ├── testplan.md
│   └── testcases.csv
├── testdata/
│   └── cases.json
└── bug-reports/
    └── BUG-001-example.md
```

## Så använder du projektet
1. Läs `testdocumentation/testplan.md` för omfattning och teststrategi.
2. Gå igenom `testdocumentation/testcases.csv`.
3. Kontrollera att testdata i `testdata/cases.json` täcker relevanta scenarier.
4. Läs `bug-reports/BUG-001-example.md` för ett exempel på strukturerad felrapportering.

## Status
Detta är en dokumentationsbaserad första version. Testfallen är **designade**, inte körda mot en verklig applikation. Resultat ska inte anges som godkända eller underkända förrän de faktiskt har exekverats.

## Möjliga nästa steg
- Lägg till en liten demoapplikation.
- Automatisera utvalda UI-testfall med Playwright.
- Lägg till API-testning.
- Kör tester automatiskt via GitHub Actions.

## Kompetenser som demonstreras
Testdesign, kravtolkning, testdata, testdokumentation, negativ testning och felrapportering.
