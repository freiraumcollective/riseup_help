@title = 'Riseup wechselt zu verschlüsseltem Speicher für Emails als Antwort auf rechtliche Anfragen.'
@nav_title = 'Canary'
@toc = false

_16. Februar 2017_

Nach Ausschöpfung aller rechtlichen Optionen hat Riseup vor kurzem enschieden, zwei verdeckten FBI-Anordnungen ("warrants") des FBI nachzukommen, anstatt Widerstand gegen die Vollstreckung zu leisten (was zur Inhaftierung von Riseup-Vögeln und/oder Auflösung der Organisation Riseup geführt hätte). Der erste Befehl betraf die öffentliche Adresse eines internationalen DDoS-Erpresserrings. Der zweite richtete sich gegen ein Konto, das Erpressungssoftware ("ransomware") nutzte, um Geld zu erpressen.

Erpressung ist eindeutig ein Verstoß sowohl gegen den Wortlaut als auch den Sinn des sozialen Vertrags \[1\], den wir mit unseren Nutzer_innen schließen: Wir halten euch den Rücken frei, solange ihr nicht ausbeuterische, frauenfeindliche, rassistische oder hetzerische Ziele verfolgt.

Es gab eine „Maulkorb-Anordnung“ („gag order“), die es uns bis jetzt verboten hat, auch nur die Existenz der Befehle offenzulegen. Dies ist auch der Grund, weshalb wir unseren „Canary“ \[2\] nicht aktualisieren konnten.

Wir haben Maßnahmen ergriffen, um sicherzustellen, dass Riseup nie wieder Zugang zum Klartext von Emails hat, die ein_e Nutzer_in gespeichert hat. Von heute an werden alle neuen Riseup-Email-Accounts mit einem persönlich verschlüsselten Speicher auf unserem Server ausgestattet, der nur für euch zugänglich ist. In der nahen Zukunft werden wir damit beginnen, alle bestehenden Accounts in dieses neue System zu überführen (für technische Details siehe \[3\]).

Um es absolut deutlich zu machen: diese Art der Verschlüsselung ist keine „Ende-zu-Ende“-Verschlüsselung eurer Nachrichten. Mit dem neuen System von Riseup werdet ihr auch weiterhin dem Server vertrauen müssen, wenn ihr eingelogt seid. Für eine volle „Ende-zu-Ende“-Verschlüsselung müsst ihr, wie zuvor, ein Mailclient nutzen der OpenPGP unterstützt (und nicht webbasiert ist).

Wir arbeiten daran, im kommenden Jahr ein verständlicheres „Ende-zu-Ende“-Verschlüsselungsystem einzuführen, aber bis das fertig ist, setzen wir persönlich verschlüsselten Speicherplatz ein.

Solidarische Grüße,<br>
Die Vögel Riseup

Fragen

F: Seid ihr von Strafverfolgungsbehörden kompromittiert?
A: Nein. Wir haben niemals die Installation von Hardware- oder Software-Überwachungsystemen in einem der von uns kontrollierten Systeme gestattet; die Strafverfolgungsbehörden haben unsere Server nicht mitgenommen; und hatten niemals Zugriff auf diese. Wir würden eher aufhören Riseup zu sein, bevor wir das zuließen.

F: Könnte die Regierung euch nicht zwingen, das zu sagen?
A: Erzwungene Aussagen sind im US-Rechssystem sehr selten. Üblicherweise finden sie nur im Bereich des Verbraucherschutz statt, wo die Regierung erfolgreich Aussagen erzwungen hat (z.B. verpflichtende Warnungen vor Zigaretten). Wie dem auch sei, nein, sie zwingen uns nicht, irgendetwas zu sagen.

F: Warum habt ihr euren „Canary“ nicht aktualisiert?
A: Im Winter 2016 wurde der „Canary“ nicht rechtzeitig aktualisiert. Der „Canary“ war so breit angelegt, dass jeder Versuch, einen neuen herauszugeben, ein Verstoß gegen die „Gag-Order“ bzgl. der Ermittlung gegen ein DDoS-Erpresserring und eine Ransomware-Operation gewesen wäre. Dies ist nicht wünschenswert, weil es, wenn eine Reihe von kleineren Dingen passiert, dazu führt, dass die Nutzer_innen annehmen müssen, etwas großes sei passiert.

F: Warum erwähnt der neue „Canary“ nicht „Gag Order“, FISA-Gerichtsanordnungen, National Security Letters usw.?
A: Unsere ursprüngliche „Canary“-Strategie hat unseren Nutzer_innen geschadet, indem es sie unnötig in Aufruhr versetzt hat, als kleinere Dinge passiert sind. Ein „Canary“ soll den Nutzer_innen ernsthafte Bedrohungen signalisieren, doch es besteht die Gefahr, dass den Nutzer_innen falsche Dinge vermittelt werden oder ohne guten Grund allgemeine Furcht und Verwirrung gestiftet wird. Der aktuelle „Canary“ ist auf bedeutende Ereignisse beschränkt, die die Sicherheit der Nutzer_innen von Riseup gefährden könnten.

* \[1\]: https://riseup.net/tos
* \[2\]: https://riseup.net/canary
* \[3\]: https://0xacab.org/riseuplabs/trees