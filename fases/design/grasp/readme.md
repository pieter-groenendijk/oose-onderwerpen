# GRASP
_General Responsibility Assignment Software Patterns_

Vijf principes die een rol spelen in effectief designen van OO systemen. Het zijn richtlijnen om verantwoordelijkheden
zo te vertellen dat dit lage koppeling, hoge cohesie volgt.

## Creator
De verantwoordelijkheid van klassen creeëren moet horen bij de klasse over wanneer en hoe zulke gemaakt kunnen worden.

## Information Expert
Een verantwoordelijkheid moet horen bij de klasse die over de benodigde informatie beschikt. hoge cohesie, lage koppeling.

## Low Coupling
Klasses moeten zo weinig mogelijk dependencies van elkaar hebben. 

## High Cohesion
De verantwoordelijkheden moeten nauw verwant zijn aan de klasse waarin ze staan.

## Controller
De verantwoordelijkheid van het behandelen van system events of activiteiten coördineren moeten horen bij een _controller_
klasse. Dit is dan een _facade_.

![](assets/controller.png)

De controller is het object wat een _system operation_ als eerst ontvangt en coördineert, na de UI laag.