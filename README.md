# ER model (entity-relationship model)

## Aufgaben für jedes ER-Modell

### Softwareschmiede
Die Firma Softwareschmiede entwickelt kundenspezifische Programme. Sie entwickelt Software für verschiedene Kunden. Jeder Kunde kann ein oder mehrere Programme kaufen. Jedes Programm wird individuell für den Kunden angefertigt. Jeder Kunde hat eine Anschrift und eine Kontoverbindung (IBAN, BIC). Das Programm hat eine Beschreibung und einen Mitarbeiter, der es erstellt und pflegt. Der Mitarbeiter hat einen Namen, eine Qualifikation (Beruf) und eine Kontoverbindung.

### Bank
Die Geld Bank beschäftigt mehrere Kundenberater. Jeder Berater kann mehrere Kunden betreuen. Ein Kunde wird von einem Berater betreut. Die Kunden verfügen über ein oder mehrere Konten bei der Geld Bank. jedes Konto hat einen Saldo (Kontostand). Jeder Kunde und Berater hat einen Vor und Nachnamen. Die Konten können Sparbücher, Girokonten oder Kreditkonten sein.

### Großhandel
Entwerfen Sie für einen Großhändler ein Datenbankmodell. Berücksichtigen Sie dabei folgende Punkte:
* Ein Kunde hat eine Anschrift (Straße, Ort, PLZ, Ansprechpartner)
* Ein Kunde kann einen Rabatt (3%, 5%, 10%) bekommen.
* Die Rabattstufe ist an einem minimalen (Jahres) Umsatz gekoppelt.
* Eine Ware hat eine Bezeichnung und BestellNr
* Eine Ware ist der Kategorie A, B oder C zugeordnet.
* Ein Kunde kann verschiedene Artikel (Waren) kaufen

### Spedition 1
Für die Spedition Müller fahren verschiedene Personen. LKW dürfen nur Personen mit der Klasse C fahren. LKW mit Anhänger benötigen die Klasse CE. Andere Personen dürfen ggf. Flurförderfahrzeuge lenken. Jede Fahrerin und jeder Fahrer hat eine Adresse und Kontodaten (fürs Gehalt). Eine Fahrerin / ein Fahrer kann eine ADR Schulungsbescheinigung (Gefahrgut) haben. Dies wird bei der Eintragung zum Führerschein vermerkt. Die Spedition stellt feste Touren zusammen. Jede Tour wird von einer Fahrerin / einem Fahrer bedient. Auf manchen Touren wird Gefahrgut gefahren. Eine Tour beinhaltet mehrere Güter und bedient einen Kunden. Jeder Kunde hat eine Adresse und Kontodaten.

### Spedition 2
Die Spedition Müller ändert ihre Tourplanung:
Jede Tour wird nun von mindestens einer Fahrerin / einem Fahrer bedient. Eine Tour beinhaltet mehrere Güter und bedient einen bis drei Kunden. Auf manchen Touren wird Gefahrgut gefahren. Die übrigen Punkte sind gegenüber der Aufgabestellung „Spedition 1“ nicht verändert.
