Main
Starter programmet, funger som en peker for de funksjonelle VIene. 
ConvertToSpreadsheet
Tar en 1D array av tall, konverterer dette til en ND array av tall som strenger, som kan skrives ut til regneark p� skjerm.
findCalibrationFactor
Du setter deformasjonen og trykker p� m�l for � finne tilh�rende voltverdi, n�r du er ferdig, m� du lagre kalibreringsfaktorene til en fil.
Dette kan endres ved � trykke p� DAQ assistant. 
splitInput
Array inn er en 1D array som deles i fire arrays med en array med element 0,4,8 en med 1,5,9 ogs� videre
splitInput2 
Array inn er en 1D array som deles i to arrays med en array med element 0,2,4 ogs� videre og neste med element 1,3,5 ogs� videre. 
Measure
kj�rer en m�ling spesifisert av setTestProcedure med kalibreringsfaktorene funnet med findCalibrationFactor. Den finner amplituden for AIene og ganger med kalibreringsfaktor.
Lag en tekstfil, og velg denne som sti. Resultatene lagres underveis i l�pet av filen.P� input rate, m� du sette et fornuftig tall s� det ikke g�r for fort, da f�r du feilmelding. 
p� samples to read, m� du sette nok samples slik at du f�r en fornuftig b�lge. Du ser hvor mye du sampler med � se p� grafen. 
Test
brukes ikke til noe, og vil bli slettet n�r programmet ikke lenger er i utviklingsfasen. 
PCI 6014
Se IO kart for � finne ut hva som er AIer og diverse. AI0 har hatt tendens til � f� en ustabil verdi med � koble direkte p� AO0. Av erfaring viser det seg at man m� sette den ved siden av (34) til jord (4) for at det skal virke.
H�kon Hoff
haakoaho@stud.ntnu.no