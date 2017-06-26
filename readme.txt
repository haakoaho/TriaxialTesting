Main
Starter programmet, funger som en peker for de funksjonelle VIene. 
ConvertToSpreadsheet
Tar en 1D array av tall, konverterer dette til en ND array av tall som strenger, som kan skrives ut til regneark på skjerm.
findCalibrationFactor
Du setter deformasjonen og trykker på mål for å finne tilhørende voltverdi, når du er ferdig, må du lagre kalibreringsfaktorene til en fil.
Dette kan endres ved å trykke på DAQ assistant. 
splitInput
Array inn er en 1D array som deles i fire arrays med en array med element 0,4,8 en med 1,5,9 også videre
splitInput2 
Array inn er en 1D array som deles i to arrays med en array med element 0,2,4 også videre og neste med element 1,3,5 også videre. 
Measure
kjører en måling spesifisert av setTestProcedure med kalibreringsfaktorene funnet med findCalibrationFactor. Den finner amplituden for AIene og ganger med kalibreringsfaktor.
Lag en tekstfil, og velg denne som sti. Resultatene lagres underveis i løpet av filen.På input rate, må du sette et fornuftig tall så det ikke går for fort, da får du feilmelding. 
på samples to read, må du sette nok samples slik at du får en fornuftig bølge. Du ser hvor mye du sampler med å se på grafen. 
Test
brukes ikke til noe, og vil bli slettet når programmet ikke lenger er i utviklingsfasen. 
PCI 6014
Se IO kart for å finne ut hva som er AIer og diverse. AI0 har hatt tendens til å få en ustabil verdi med å koble direkte på AO0. Av erfaring viser det seg at man må sette den ved siden av (34) til jord (4) for at det skal virke.
Håkon Hoff
haakoaho@stud.ntnu.no