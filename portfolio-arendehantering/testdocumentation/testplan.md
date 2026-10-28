# Testplan – Fiktivt ärendehanteringssystem

## 1. Syfte
Syftet är att beskriva hur grundläggande funktioner i ett fiktivt ärendehanteringssystem skulle testas innan en release.

## 2. Testobjekt
En webbaserad vy där en handläggare kan:
- visa en lista över ärenden
- söka efter ärenden via ärende-ID
- filtrera ärenden efter status
- öppna ett ärende och läsa dess sammanfattning

## 3. Testunderlag och antaganden
Det finns inget verkligt system eller officiellt kravdokument i detta portfolio-projekt. Följande krav är skapade enbart för övningen:
- **REQ-001:** Ärendelistan visar ärende-ID, rubrik och status.
- **REQ-002:** Sökning på ett befintligt ärende-ID visar matchande ärende.
- **REQ-003:** Sökning på ett okänt ärende-ID visar ett tydligt meddelande om att inget ärende hittades.
- **REQ-004:** Statusfiltret visar endast ärenden med vald status.
- **REQ-005:** Detaljvyn visar samma ärende-ID och status som i listan.
- **REQ-006:** Tom sökning ska inte orsaka ett fel i gränssnittet.

## 4. Omfattning
### Ingår
- grundläggande funktionstestning
- positiva och negativa scenarier
- kontroll av visad information
- testning av sökning och statusfilter
- enkel kontroll av felmeddelanden

### Ingår inte
- autentisering och behörigheter
- integrationer med externa system
- prestanda- och belastningstestning
- säkerhetstestning
- tillgänglighetstestning
- testning av en verklig produktionsmiljö

## 5. Teststrategi
Testfallen prioriteras efter verksamhetspåverkan:
- **Hög:** centrala funktioner som sökning och korrekt visning av ärendeinformation
- **Medel:** statusfilter och tom sökning
- **Låg:** ytterligare visningsdetaljer som inte påverkar kärnflödet

Testningen skulle genomföras manuellt i en testmiljö. För varje testfall dokumenteras faktiskt resultat och status först efter att testet har körts.

## 6. Testmiljö
Ej tillämpligt ännu. Ingen applikation har kopplats till testdokumentationen. Vid framtida exekvering ska webbläsare, version, testmiljö och testdatum dokumenteras.

## 7. Startkriterier
- testunderlag och testdata är tillgängliga
- testmiljön är åtkomlig
- testversionen är identifierad

## 8. Avslutskriterier
- samtliga prioriterade testfall har körts
- avvikelser har dokumenterats
- kvarstående fel och risker har sammanställts

## 9. Risker
- Kraven är förenklade och inte förankrade i verkliga verksamhetsbehov.
- Utan en faktisk applikation går det inte att verifiera testfallen.
- Testdata är syntetisk och täcker inte alla möjliga kombinationer.

## 10. Leverabler
- testplan
- testfall i CSV-format
- testdata i JSON-format
- exempel på felrapport
