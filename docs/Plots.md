# **🏡 Plots auf Lemonlight**
Plots sind abgegrenzte Bereiche, in denen du ungestört bauen kannst. Dein Grundstück ist vor Zerstörung und Diebstahl durch andere Spieler geschützt – solange du ihnen nicht die nötigen Rechte gibst.


## **📐 Beanspruchung**
- **/p auto**  
    Teleportiert dich zu einem freien Plot und beansprucht es direkt (Kosten: **5.000 Coins** pro Plot).
- **/p claim**  
    Kaufe das Plot, auf dem du stehst, wenn es noch frei ist (Kosten: **5.000 Coins** pro Plot).

## **🛠️ Spieler-Verwaltung**
- **/p add \[Spieler\]**  
    Fügt einen Spieler als Mitglied hinzu. Dieser kann **nur interagieren, wenn du online bist**.
- **/p remove [Spieler]**  
    Entfernt einen Spieler als Mitglied.
- **/p trust \[Spieler\]**  
    Fügt einen Spieler als vertrauenswürdiges Mitglied hinzu. Dieser kann **immer interagieren, auch wenn du offline bist**.
- **/p untrust [Spieler]**  
    Entfernt einen Spieler als vertrauenswürdiges Mitglied.
- **/p setowner [Spieler]**  
    Übertrage das Eigentum an deinem Plot an einen anderen Spieler.
- **/p deny [Spieler]**  
    Verbietet einem Spieler den Zugang zu deinem Plot.
- **/p undeny [Spieler]**  
    Gibt einem Spieler wieder den Zugang zu deinem Plot.
- **/p kick [Spieler]**  
    Kickt einen Spieler von deinem Plot.

## **🛠️ Verwaltung**
- **/p info**  
    Zeigt dir Infos zum Plot, auf dem du stehst.
- **/p v \[Spieler\] \[Plot Nummer\]**
	Teleportiere dich zum Plot eines anderen Spielers.
- **/p h**
    Teleportier dich zu deinen Homepunk in der Plotwelt.
- **/p clear**  
    Leert das Plot komplett. Achtung: Alle Items gehen verloren!
- **/p delete**  
    Löscht das Plot. Du bist danach nicht mehr der Besitzer.
- **/p middle**  
    Teleportiere dich zum Mittelpunkt deines Plots.
- **/p sethome**
    Setzt den Spawnpunkt des Plots an die Stelle, an der du stehst. Dies ist auch der Spawnpunkt für jeden der sich zu diesem Plot teleportiert. 
- **/p alias \[Name\]**  
    Vergib einen individuellen Namen für dein Plot.
- **/p setdescription \[Text\]**  
    Füge eine Beschreibung zu deinem Plot hinzu.
- **/plot merge**  
    Verbinde mehrere benachbarte Plots zu einem großen Plot. Siehe [[#🔗 Plot Mergen]]
    Kosten: **40.000 Coins pro Verbindung**
    Verfügbar ab Rang: **Arbeiter**
- **/p setbiom \[Biom\]**  
    Ändere das Biom deines Plots.
    Verfügbar ab Rang: **Konstrukteur**
- **/p setflag \[Flag\] \[true/false\]**  
    Ändere die Plot-Flags.
    Verfügbar ab Rang: **Architekt**


## **🔗 Plot Mergen**
Mit **/plot merge** kannst du mehrere benachbarte Grundstücke zu einem großen Plot verbinden. So hast du mehr Platz zum Bauen und kannst deine Grundstücke zusammenlegen.
### **📋 So funktioniert es**
- Stehe auf dem Plot, den du vergrößern möchtest.
- Gib den Befehl ein, z. B.:  
    /plot merge n (um den Plot nördlich mit deinem aktuellen Plot zu verbinden)
- Möglich sind die Richtungen: **n** (Norden), **e** (Osten), **s** (Süden), **w** (Westen)
- Mit /plot merge all verbindest du alle angrenzenden Plots in alle Richtungen

### **💰 Kosten & Bedingungen**
- **Mergen ist ab dem Rang „Arbeiter“ möglich.**
- **Für jedes Mergen fallen 40.000 Coins als Gebühr an**
- **Maximale Anzahl der zusammenlegbaren Plots richtet sich nach deinem Rang:**
  - Arbeiter: bis zu 4 Plots
  - Konstrukteur: bis zu 5 Plots
  - Architekt: bis zu 6 Plots
  - Meister: bis zu 7 Plots
  - Legende: bis zu 9 Plots
- Die Plots müssen **benachbart** und in die angegebene Richtung angrenzend sein.
- Du musst **alle betroffenen Plots besitzen** oder die entsprechenden Rechte darauf haben.

## **💰 Plots verkaufen & kaufen**
Plots können für Coins verkauft werden und gekauft von anderen Spieler für den gesetzten Betrag gekauft werden.

- **/p flag price \[Betrag\]**  
    Setzt den Verkaufspreis für dein Plot. Andere Spieler können es dann kaufen.
- **/p buy**  
    Kaufe das Plot, auf dem du stehst, wenn es zum Verkauf steht.
## **🏳️ Plot-Flags und ihre Freischaltung**
Spieler können ab bestimmten Rängen folgende Plot-Flags ändern, um das Verhalten innerhalb ihrer Grundstücke zu steuern:

- **pvp**: Erlaubt oder verbietet PvP auf dem Plot. Verfügbar ab dem Rang **Architekt**.
- **pve**: Erlaubt oder verbietet PvE auf dem Plot. Ebenfalls ab Rang **Architekt** nutzbar.
- **explosion**: Erlaubt oder verbietet Explosionen (zum Beispiel TNT) innerhalb des Plots. Auch diese Flag ist ab dem Rang **Architekt** freigeschaltet.

**Hinweis:** Andere Flags sind serverseitig voreingestellt und können von Spielern nicht geändert werden!