## **Nodes**

**id**

- Personen → Initialen von Vor- und Nachnamen + Jahr, in dem Preis gewonnen wurde (UL25, UL90)
- Institute → Abkürzung der Institution (LMU, …)
- Preise → Nummerierung (1,2,...)

**name**

- Personen → erst Vorname, dann Nachname, kein Zweitname, kein Dr. oder Prof. Titel (Bspw. Volker Haucke) 
- Institute → Name der Institution (Bspw. Universität Bremen, Ludwig Maximilians Universität München) 
- Preis → offizieller Name, ohne Bindestriche und mit allem (Bspw. "Deutscher Psychologie-Preis der Deutschen Gesellschaft für Psychologie" wird zu "Deutscher Psychologie Preis der Deutschen Gesellschaft für Psychologie") 
- Nicht den Gottfried Leibniz Preis eintragen!
- Nur alles was Preis heißt (keine Medaillen etc.)

**Geburtsjahr**

- Nur für Personen
- Bspw. 1965

**Jahr**

- Jahr in dem Wissenschaftler*innen den Leibnizpreis gewonnen haben
- Nur bei Personen, bei den anderen leer lassen
  
**geschlecht**

- 1 = weiblich
- 2 = männlich 
- 3 = divers
  
**type**

- 1 = Personen 
- 2 = Institute 
- 3 = Preise 

**alter_lp_gewonnen**

- Alter in dem Jahr, in dem der Leibnizpreis gewonnen wurde
- Rechnung des Jahres, unabhängig vom Geburtsmonat 

## **Edges**

**from** 
- id Personen

**to** 
- id Institution oder Preis

**Jahr**
- Jahr in dem Wissenschaftler*in gewonnen hat (nur bei Preisen, bei Institutionen nichts)

**Zeitpunkt** 
- Nur bei Preisen 
- 1 = Gewinn eines Preises vor und im selben Jahr wie der Leibniz Preis
- 2 = Gewinn eines Preises nach Leibniz Preis 
