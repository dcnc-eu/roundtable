# Organisationsform

Organisationen, die autarke Teams etablieren wollen, haben diverse Topologien zur Auswahl.

Eine vielfältiger Überblick im Kontext von DevOps findet sich z.B. bei den [DevOps Topologies](https://web.devopstopologies.com/).
Die Orientierung gestaltet sich jedoch schwierig. Der Austausch der Firmen im Roundtable hat ergeben, dass verschiedene dieser Topologien - mit unterschiedlichem Erfolg - erprobt wurden.

## Idealbild

Ein empfehlenswertes Idealbild könnte wie folgt aussehen:

![DevOps Topology](devops-topo.svg)

* **Dev** - Produkt-Team mit Fokus auf Umsetzung/Bereitstellung von Business-Funktionalität. Klassisch sind dies Software-Entwickler ohne besonderen Betriebs- oder Infrastrukturhintergrund.
* **DevOps** - Mitglieder des Produkt-Teams, die neben der Software-Entwicklung auch Infrastruktur-Tätigkeiten und Betrieb übernehmen. Idealerweise besteht das Produkt-Team ausschließlich aus diesem Profil, da dies jedoch utopisch ist, sollte eine ausreichende, mindestens jedoch redundante Personenanzahl je Team vorhanden sein. Produkt-Teams dürfen und sollen zur Plattform beitragen.
* **CCoE** (Cloud Center of Enablement) - Eine Gruppe von Cloud-Experten, die zwar dem Plattform-Team angehören, aber als Berater allen Teams mit Rat und Tat zur Seite stehen. Ihre primäre Aufgabe ist die Unterstützung der Produkt-Teams in der Umsetzung von cloudbasierten Lösungen und des Aufbaus der DevOps-Rollen in jedem Team.
* **Plattform** - Dediziertes Team, das den Produkt-Teams die sichere Verwendung der Cloud zugänglich macht. Dies erreichen sie u.a. dadurch, dass sie Werkzeuge für wiederkehrende Herausforderungen bereitstellen und allgemeine Qualitätsanforderungen in der Plattform verankern. Hierzu gehören typischerweise Aufgaben wie:
  * Accountverwaltung
  * Ausübung von Governance
  * Zentrale Kostenkontrolle
  * Betrieb zentraler Dienste
  * Bereitstellung von allgemeingültigem Tooling
Ein wichtiger Aspekt ist, dass die Plattform ein offenes, erweiterbares, kollaboratives System darstellt. Die Plattform ist die Basis, auf der die Produkt-Teams arbeiten, nicht die Grenze innerhalb der sie arbeiten.

## Evolution

Da die meisten Organisationen sich erst zum Idealbild hin entwickeln müssen, bedarf es Strategien, die diese Entwicklung unterstützen.
Der Wechsel in eine DevOps-Organisationsform unter Verwendung von Cloud-Angeboten und -Technologien ist ein Prozess, der aktiv gefördert werden muss.

Im Bestreben um autarke wertstromorientierte Produkt-Teams (also Teams, die ihr Produkt selbst designen, umsetzen, betreiben und pflegen) muss das Produkt-Team als Einheit, und nicht nur als Summe seiner Team-Mitglieder betrachtet werden. Besonders im Hinblick auf den Betrieb des Software-Systems ist es unabdingbar, dass Wissen breit genug verteilt ist und es keine starke Abhängigkeit zu einer Person oder der Plattform gibt.

Die Grundlagen für das Nutzen von Cloud-Angeboten werden durch ein Plattform-Team gelegt.
Dieses sollte jedoch in Kooperation mit den Produkt-Teams den kleinsten gemeinsamen Nenner ermitteln und bereitstellen, also die für alle Produkt-Teams identische Basis.
Darauf aufbauend sollte sich die Plattform im Laufe ihrer Nutzung durch die Produkt-Teams nach Bedarf weiterentwickeln.
Das proaktive Bauen einer Plattform und das dann notwendige Anpassen - entweder der Plattform an die Produkt-Teams, oder der von den Produkt-Teams gebauten Lösungen an die Plattform - verursacht hohe Reibungsverluste und hemmt die Effizienz.

Zu Beginn der Einführung von DevOps im Produkt-Team liegt eine Einschätzung der Reife des Teams in Hinblick auf DevOps-Themen (also Infrastrukturaufgaben und Betrieb). Diese Einschätzung sollte durch das Team selbst erfolgen, unterstützt durch Experten (wie z.B. dem CCoE), die als Katalysatoren dienen. Hierzu eignen sich standardisierte Fragenkataloge oder Formate wie ein Assessment-Center oder eine Incident-Simulation.
Neben den notwendigen technischen Kenntnissen und Fähigkeiten ist der Wille zu DevOps der wichtigste Faktor für den Reifegrad jedes Produkt-Teams.

Effizienzsteigernd in der Einführung von DevOps in Produkt-Teams ist auch der Austausch der Produkt-Teams untereinander, um eine Schwarmintelligenz zu bilden.
Leider passiert dies in den wenigsten Fällen selbständig.
Daher empfehlen wir die Aufgabe der gezielten Förderung und Moderation bewusst und gezielt aufzuhängen.

Für einen nachhaltigen Erfolg ist die ganzheitliche Erfahrung des Betriebs im Produkt-Team entscheidend. Es konnte eine Steigerung der Qualität festgestellt werden, sofern Produkt-Teams ihre Lösungen selbst betreiben mussten.
