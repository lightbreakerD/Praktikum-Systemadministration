# Aufgabe 1: Installation eines Betriebssystems
In dieser Aufgabe gilt es ein Unix-Betriebssystem zu installieren, das für den Rest des Praktikums als Basis für die Bearbeitung aller weiteren Aufgaben dienen soll.
## Einleitung
Schreiben wir zuletzt
## Verbindung mit dem Host Server
Wir unterscheiden hier zwischen zwei Server, dem Praktikum Server oder der Host Server und die Virtual Machines (VM's). Auf dem Host Server laufen mehrere VM's, die den jeweiligen Praktikum teams gehören.

Um unsere VM's zu erstellen, müssen wir also zuerst auf den Hostserver zugreifen, um dort unsere VM's initial zu installieren. So greifen wir auf den Host Server zu:

`ssh <tum-kennung>@psa.in.tum.de`

Danach müssen wir unser Passwort eingeben
Nun starten wir vncserver, damit wir auf die GUI des Hostservers zugreifen können

`vncserver`

Nachdem wir ein passwort festlegen, bekommen wir folgende Rückmeldung:

*New 'X' desktop is psarbg2:18*

18 in dem Fall wäre dann unsere Display Nummer die wir uns merken, und können nun mit dem RealVNC Viewer auf die GUI des Hostservers zugreifen, indem wir folgende Adresse verwenden:

`psa.in.tum.de:18`

![Alt text](<Screenshot 2024-04-21 at 21.45.10.png>)

Nun können wir die Virtualbox Applikation starten, in unserem Terminal

`VirtualBox`

## VM Erstellen mithilfe von dem vorgegebenen Template
Hier gehen wir nun auf den Button "Import" und importieren das VM template für unser Praktikum:

<img src="image.png" width="100">

![Alt text](image.png)

Das template befindet sich unter 

*/opt/psa/data/ISOs VMs/PSA Template.1GB.ova*

Hier wäre es nun wichtig die richtige Mac Adress Policy auszuwählen

![Alt text](<Screenshot 2024-04-21 at 21.55.10.png>)

Wir können wenn nötig auch die anzahl an benötigten **CPU's und RAM** erhöhen.

Als Name für unsere VM wählen wir 

`vmpsateam10-01 bzw. vmpsateam10-02`

**ill finish this tmr evening**
