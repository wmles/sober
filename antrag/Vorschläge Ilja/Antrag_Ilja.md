*Welches Problem willst Du mit Deinem Projekt lösen?*

 - Polarisierung der Gesellschaft in Lager, die nicht sachlich miteinander diskutieren können. 
 - Sie scheint paradoxerweise durch die Vernetzung im Web noch verstärkt zu werden - statt besserem Zugang zur Ansicht anderer bilden sich Filterblasen, die die eigene Weltanschuung bestärken.
 - zu sehen in "shitstorms" in den "Sozialen Netzwerken" zutage, oder bei Kommentaren von Artikeln/Videos/Blogs. 
 - hohe emotionale Aufladung politischer Themen der letzten Jahre.
 - die Wirkung wird in der digitalen Welt erzeugt, kann aber auf andere Lebensbereiche zurückwiken -> Gewaltpotential.
 - Grund: Verlust der Übersicht durch zu viele Meinungsbeiträge, chronologische Sortierung unzweckmäßig -> psychische Filter zusätzlich zu den technischen.

*Wie wird Dein Projekt dieses Problem lösen?*  

Wir hoffen, dass man zur Lösung des Problems _auch_ durch technische Lösungen beitragen kann.  
Viele Diskussionen sind in der persönlichen Begegnung angenehmer und fruchtbarer. Aber auch der digitale Austausch aus der Ferne bietet neue Chancen und Möglichkeiten - die es optimal zu nutzen gilt!  
Das Konzept einer "Mind Map", die die Fülle der vorhandenen Argumente und deren Verknüpfungen übersichtlich darstellen soll, lässt sich im Digitalen besonders flexibel einsetzen; eine solche Übersicht lässt sich jederzeit erweitern und bequem speichern.  
Vorbilder der gelungenen Wissensanordnung im Internet sind Wikipedia und Stack Overflow. Beide versuchen "opinion-based"-Themen fernzuhalten. Diese Leerstelle soll unser Projekt adressieren. Als Vorbild kann die Idee von http://open.brabbl.com/ dienen, wobei eine Open-Source-Implementation die Hürden der breiteren Nutzung verringern würde.  
Durch eine geschickte Architektur sollen Probleme der "Sozialen Netzwerke" (Filterblasen) und der persönlichen Diskussion (vorschnelles Reinreden, Rechthabenwollen) umgangen werden. Dadurch können die Teilnehmer*innen einer Diskussion zu einem Konsens kommen oder auch eine gut verstandene Uneinigkeit sachlich und wertneutral stehen lassen.  

*Wer ist die Zielgruppe? Wie profitiert sie vom Projekt?*  

 1. Gruppen mit flacher Hierarchie (Firma, Verein, Schulklasse, ...), die zu einer gemeisam getragenen Entscheidung kommen müssen, und nicht wollen, dass die aktiveren und eloquenteren Redner*innen die anderen manipulieren können.  
 2. Betreiber*innen von Onlinemedien (Blogs etc.), für die Kommentarfuktion.  

Potentielle Nutzer*innen können:
 - den Dienst auf unserem Server ausprobieren bis sie sich eine Meinung über die Nützlichkeit gebildet haben.
 - unsere App in ihrem Projekt einbinden, falls dieses in einem python-framework geschrieben ist.
 - ein vorgefertigtes (standalone-)django-Projekt installieren (root-Server vorausgesetzt)
 - Komponenten (Konzept, css, js, Datenbanklayout) in eigenen Projekten übernehmen.

*Skizziere kurz die wichtigsten Meilensteine, die Du/Ihr im Förderzeitraum umsetzen willst/wollt.*

In der erste Phase muss ein ansprechend aussehendes Interface geschaffen werden, um vorhandene Argumente und ihre Verknüpfungen einzusehen, und neue Argumente einzutragen und zu schon vorhandenen in Beziehung zu setzen.  
Danach wird eine Möglichkeit der Bewertung von Argumenten (upvotes) und Verknüpfungen eingebaut.  
Die Software wird als Django-App zur Verfügung gestellt und zu testzwecken auf auf einem eigenen Server gehostet. Dann wird die Integration der App erleichtert und und ein Port auf Flask geschrieben, um den Nutzerkreis noch auszuweiten. 


