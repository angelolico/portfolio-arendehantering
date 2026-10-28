# BUG-001 – Statusfilter visar ärenden med fel status

> **Exempelrapport:** Detta är en fiktiv rapport som visar formatet för en felrapport. Felet har inte upptäckts i eller verifierats mot en verklig applikation.

- **Miljö:** Ej specificerad – exempel
- **Prioritet:** Hög
- **Allvarlighetsgrad:** Major
- **Relaterat krav:** REQ-004
- **Status:** Exempel – ej verifierad

## Sammanfattning
Statusfiltret visar även ärenden som inte matchar den valda statusen.

## Förutsättningar
- Testdata innehåller minst ett ärende med status `Pågår` och ett med status `Väntar`.
- Ärendelistan är öppen.

## Steg för att återskapa
1. Öppna ärendelistan.
2. Välj `Pågår` i statusfiltret.
3. Granska statusen på samtliga visade ärenden.

## Förväntat resultat
Endast ärenden med status `Pågår` visas.

## Faktiskt resultat
I detta fiktiva exempel visas även ett ärende med status `Väntar`.

## Påverkan
Användaren kan få en missvisande bild av vilka ärenden som tillhör den valda statusen.

## Bilaga
Ingen skärmbild finns eftersom rapporten är illustrativ och inte kommer från en körd testning.
