### Fix/Mod für max. Lautstärke PCB's 1.0 & 1.1 ###
(Du brauchst diesen nicht für Platinen ab Version 1.2)

| Schritt | Einfacher Fix/Mod v1.0 oder v1.1    | Ich verwende diese Variante für beide Versionen, da ich ohne die Keramikkondensatoren keine Störgeräusche oder Brummen über den kleinen 3-Watt-Lautsprecher höre.     |
|---|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | ![](images/Bodge1.1-01.jpg)  | Kunststoff vorsichtig oberhalb des VCC-Pins am DFPlayer Mini abschneiden.                                                                                                           |
| 2 | ![](images/Bodge1.1-02.jpg)  | Beim Löten am DFPlayer Mini besteht die Gefahr, winzige SMD-Kondensatoren oder -Widerstände zu beschädigen. Halte Abstand und erhitze den Pin, bis du ihn aus der Platine und dem Header ziehen kannst. Danach den restlichen Kunststoff unterhalb von VCC entfernen. |
| 3 | ![](images/Bodge1.1-03.jpg)  | Das Durchgangsloch mit einer Entlötpumpe (oder notfalls Klebeband – riskant!) säubern.                                                                                              |
| 4 | ![](images/Bodge1.1-04.jpg)  | Prüfe danach, ob keine SMD-Bauteile auf Ober- oder Unterseite verschoben oder abgelöst wurden. Das Loch sollte frei sein.                                                             |
| 5 | ![](images/Bodge1.0-01.jpg)  | Die 3V3-Durchkontaktierung mit etwas Kapton- oder Isolierband abdecken.                                                                                                             |
| 6 | ![](images/Bodge1.0-02.jpg)  | Ein ca. 25 mm langes Stück hitzebeständigen Draht abisolieren. Ein Ende von unten durch den DFPlayer Mini führen und verlöten. Dann den DFPlayer Mini auf die CC5x12-Platine löten. |
| 7 | ![](images/Bodge1.0-03.jpg)  | Das andere Drahtende durch das 5V-Loch des Erweiterungs-Headers führen. Einen 220 µF-Elko durch das 5V- und das benachbarte GND-Loch stecken und verlöten.                          |
| 8 |  ![](images/Bodge1.0-04.jpg) | Der fertige Bodge ermöglicht maximale Lautstärke (30) über den internen 3W-Verstärker des DFPlayer Mini.                                                                              |

| Schritt | Fix/Mod v1.1 mit Keramikkondensatoren | Keramikkondensatoren helfen, Störgeräusche auf der Platine zu reduzieren.                                                  |
|------|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| 1-4  | wie oben beschrieben.         |                                                                                                                                        |
| 5    | ![](images/Bodge1.1-05.jpg)  | Ein kurzes Stück hitzebeständigen Draht und ein Bein eines 104-Kondensators von unten einführen und verlöten.                          |
| 6    | ![](images/Bodge1.1-06.jpg)  | Die 3V3-Durchkontaktierungen mit Kapton- oder Isolierband abdecken.                                                                    |
| 7    | ![](images/Bodge1.1-07.jpg)  | DFPlayer Mini vorsichtig montieren und das andere Bein des 104-Kondensators mit GND verbinden. Beide verlöten.                         |
| 8    | ![](images/Bodge1.1-08.jpg)  | Nach dem Löten und Kürzen der Beinchen sollten die 3V3-Löcher frei bleiben.                                                            |
| 9    | ![](images/Bodge1.1-09.jpg)  | Die Beinchen eines 220 µF-Elkos abwinkeln und in die 5V- und GND-Löcher des Erweiterungs-Headers stecken.                              |
| 10   | ![](images/Bodge1.1-10.jpg)  | VCC-Draht abisolieren und einen 105-Kondensator mit in das Loch stecken, sodass er Kontakt zum VCC-Draht hat. Alles zusammen verlöten. |
| 11   | ![](images/Bodge1.1-11.jpg)  | Fertiger Fix/Mod an der 5V-Stromversorgung.                                                                                            |
| 12   | ![](images/Bodge1.1-12.jpg)  | Fertiger Fix/Mod am DFPlayer Mini.                                                                                                     |

**Teste deine Verbindungen!**
