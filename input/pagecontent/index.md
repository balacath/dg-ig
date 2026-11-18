<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis dokumentiert Arzneimittelallergien von Patientinnen und Patienten mit FHIR. Die Angaben umfassen den Allergiestatus, den auslösenden Stoff, die Kritikalität und mögliche Reaktionen. Dadurch kann eine Notfallstation die Allergieinformationen zuverlässig auswerten.
### Scope

Dieses Implementation Guide basiert auf CH Core AllergyIntolerance und definiert Regeln zur standardisierten Dokumentation von Arzneimittelallergien in der Schweiz. Es umfasst den klinischen Status, Allergiecodes, die Kritikalität, den Beginn, die erfassende Fachperson und allergische Reaktionen. Andere Allergiekategorien und Erkrankungen sind nicht Teil dieses Implementation Guides.

### Artefakte

- **FHIR-Profil:** Arzneimittelallergie basierend auf CH Core AllergyIntolerance.
- **Invariante:** Bestätigte Allergien müssen mindestens eine Reaktion dokumentieren.
- **FHIR-Beispiel:** Penicillinallergie der Patientin Anna Muster mit dokumentierter Hautreaktion.

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): TODO
* [Titel eures Beispiels](AllergyIntolerance-TODO_Name.html): TODO

<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

**Erstellt von:** Athi

**Hochschule:** ZHAW – Zürcher Hochschule für Angewandte Wissenschaften

**Modul:** Data Standards in Healthcare, HS26

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
