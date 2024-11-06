# SOLID Principes
1. **Single Responsibility** Principle
2. **Open/Closed** Principle
3. **(Liskov's) Substitution** Principle
4. **Interface Segregation** Principle
4. **Dependency Inversion** Principle

Deze principes zorgen ervoor dat sterke koppeling over het algemeen voorkomen wordt. Leer [hier](../koppeling-en-cohesie/koppeling-en-cohesie.md) meer over kopeling.


## Single Responsibility
De cohesie van de module is zo hoog dat het enkel één doel heeft. Dit zorgt ervoor dat dus een module ook maar één reden heeft om te veranderen.


## Open/Closed
- **Open for extension**
- **Closed for modification**

Veranderingen binnen code maken waar andere code al afhankelijk van is kan voor problemen zorgen. Daarom zorgen we ervoor dat code uitbreidbaar is (kan nieuwe requirements vervullen)
zonder dat bestaande code verandert hoeft te worden. 


## (Liskov's) Substitution 
Afgeleide klassen moeten gebruikt kunnen wordt net zoals hun basis klasse. 


## Interface Segregation
Zorg ervoor dat klassen alleen interfaces implementeren, als deze ze daadwerkelijk gaan implementeren. Als dat gebeurt is het van belang de interfaces op te delen. Dit is vergelijkbaar
met het eerste principe: **Single Responsibility**. **Interfaces moeten één doel beschrijven.**


## Dependency Inversion
Men zou afhankelijk moeten zijn van abstracties (interfaces/abstract classes), niet van concrete implementaties. Hierdoor zijn modules minder gekoppeld aan elkaar, de concrete 
implementaties zouden namelijk omgewisseld kunnen worden.
