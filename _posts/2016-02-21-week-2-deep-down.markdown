---
layout: post
title:  "Week 2: Deep down"
date:   2016-02-21 17:57:00 +0100
categories: algemeen
---
Het is nog geen week geleden, maar toch is er alweer een hoop werk verzet. Te beginnen met het blog, deze is vanaf heden te bereiken via [blog.made2pay.com](http://blog.made2pay.com "Blog"). Sharing is caring!

En dan de app; deze week ben ik bezig geweest met het helder krijgen van wat onderlinge relaties. Bijvoorbeeld hoe producten tot bestellingen aan elkaar gerelateerd zijn, en wat dit betekent voor de statistieken. Het is een belangrijk onderdeel van de app, hiermee wordt namelijk bepaald hoe je de database en relaties daarvan moet inrichten. Hier had ik van te voren al over nagedacht, maar al doende bleek dat niet alle situaties voldoende gecovered waren. Geen probleem uiteraard, al was het een uitdaging om een oplossing te vinden waar ik een goed gevoel bij had. Het probleem was wanneer een product verwijderd werd, ik dit product in de achtergrond (dus niet zichtbaar voor de gebruiker) moest bewaren om bij de statistieken de juiste informatie te kunnen laten zien. Of ik moest bepaalde details van een product dubbel opslaan, zodat ik i.i.g. de benodigde informatie tot mijn beschikking had bij afgehandelde bestellingen. Eigenlijk is de oplossing een combinatie van beide opties geworden. Ik sla de naam van het product + de prijs nogmaals op bij de bestelling en hou een referentie naar het product bij. Mocht het product verwijderd worden, zijn de cruciale gegevens nog aanwezig. Mocht het product nog bestaan, kan ik hier eventueel logica op uitvoeren. Ook leent deze opzet zich goed om de prijs bij het aanslaan aan te passen.

In mijn eerste blogpost gaf ik al aan dat in de nieuwe versie gedeeltelijk betalen & het hernoemen van een rekening toegevoegd worden. Maar ook het geven van kortingen hoort in dat rijtje, net als ondersteuning voor meerdere printers. Je kan dan bijv. zelf een bar of keuken printer toekennen aan een product, zo ben je zelf in control en niet meer gelimiteerd aan een enkele keuken- en/of bonnenprinter. Maar ook kan je bij het bekijken van de statistieken naast de datum ook de tijd aangeven. Zo kan je nog beter inzicht krijgen van de omzet van een feest of evenement. Zo staat ook op de planning om de integratie van Payleven te verbeteren, en wellicht iZettle als pin provider toe te voegen.

Hieronder zie je een filmpje van de huidige versie, met het hernoemen van een rekening en gedeeltelijke betalingen (zie transactions):
<iframe width="560" height="315" src="https://www.youtube.com/embed/Niu5U5tcuEs" frameborder="0" allowfullscreen></iframe>
Misschien lijkt het nu net op de m2p app van twee jaar geleden [filmpje](https://youtu.be/XLyKQ2-R3bk) maar nu de database structuur vrijwel helemaal helder is, gaat de rest erg hard.

Aankomende week ga ik het beheerdersmenu weer toevoegen en ga ik starten met de statistieken. Wellicht dat ik hier direct mooie grafieken aan toevoeg, het is nu namelijk mogelijk om op bestellingsniveau de statistieken terug te zoeken. Hierdoor gaan er heel wat mooie deuren open!

Dit was hem voor vandaag, nog een fijne zondag!

Heeft u vragen, op- of aanmerkingen? U kunt altijd bij ons terecht via [info@made2pay.com](mailto:info@made2pay.com "email"), [twitter](https://twitter.com/made2pay "@made2pay") of [facebook](https://www.facebook.com/made2pay "Made2pay").

Ik hou u op de hoogte!

Niels Koole, eigenaar en ontwikkelaar van Made2pay
