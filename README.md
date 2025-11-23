# Die Elektronische Patientenakte (EPA)

Dieses Repository enthält eine fachliche Analyse der Elektronischen Patientenakte (ePA)
im Rahmen meiner Ausbildung zum Fachinformatiker. Die Arbeit behandelt das zentrale
Lösungsziel der ePA, untersucht die verarbeiteten medizinischen Daten sowie deren
Datenfluss, Speicherort und Zugriffsrechte.

## 1.0.	Das Lösungsziel der EPA
Die Elektronische Patientenakte ist eine Digitale Form der Patientenakte, welche 
zur Erleichterung der Zusammenarbeit von Ärzten / Krankenkassen dienen soll. Diese ermöglicht eine Zentrale Datensammlung.

## 2.0 	Welche Daten verarbeitet die EPA
Die EPA verarbeitet Medizinische Daten bspw. ärztlichen Befunde, 
Medikamentenlisten und andere Medizinische Diagnosen welche relevant für die Krankenkassen und Ärzte sind. 

### 1.	Datenarte
Medizinische Daten (Streng Vertraulich)
### 2.	Datenfluss
Die Daten werden von dem jeweiligen Arzt / Krankenkasse an die Krankenkasse versendet, welche diese Daten dann im ePA-Datenspeicher verschlüsselt abspeichern. 
### 3.	Speicherort
Die Daten, werden auf einem zentralen Server in Deutschland gespeichert. 
Dort werden die Patientendaten persistent gespeichert.
### 4.	Zugriffsrechte
Die Zugriffsrechte, werden ausschließlich von dem Nutzer verwaltet, dieser kann gewisse Zugriffrechte an die Krankenkasse und an den jeweiligen Arzt erteilen oder verweigern.

<img width="492" height="320" alt="Screenshot 2025-11-22 204405" src="https://github.com/user-attachments/assets/742577a7-523c-4fdd-953e-00abdbad7ce6" />
 
## 3. Welche der 3 Schutzziele bewerten Sie für die verarbeiteten Daten als besonders relevant?
Für die Elektronische Patientenakte sind alle dieser drei Schutzziele besonders relevant. Bezogen auf die Verarbeitung sehr vertraulicher Daten,
welche ein hohes Schutzziel besitzen, ist die Vertraulichkeit besonders relevant. 
Die Vertraulichkeit der Daten muss gewährleistet werden da die Daten, welche bei der Verwendung Elektronischen Patientenakte verarbeitet werden,
dem Datenschutz unterliegen. Somit auch der DSGVO.
Diese regelt die Verarbeitung personenbezogener Daten in der EU. 
Auch die Integrität der Daten spielt bei der Verarbeitung eine große Rolle. Da sichergestellt werden muss, dass die Daten welche verarbeitet werden, weder manipuliert noch gestohlen werden können.

## 4. Für welche der 6 Schadensszenarion sehen sie einen hohen oder sehr hohen Schutzbedarf? ([Schadenszenario](https://johannesloetzsch.github.io/LF11b/analyse.html#schadensszenarien))

Einen besonders hohen Schutzbedarf

## 5.  Welche der 47 Elementaren Gefährdungen sind aus ihrer Sicht für das Beispiel besonders relevant? ([BSI-Gefährdungen](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/IT-GS-Kompendium/Elementare_Gefaehrdungen.pdf?__blob=publicationFile&v=4))
Einige dieser Gefährdungen sind besonders relevant und sollten bei dem Verarbeiten der Daten berücksichtigt werden. 
Ich liste hier 3 Beispiele auf, welche ich als besonders relevant erachte: 

### 0.19 Offenlegung schützenswerter Informationen

Diese Gefährdung ist besonders gefährlich für das Verarbeiten der Personenbezogenen und in diesem Fall Risikodaten. 
In dieser steht geschrieben „*Werden schützenswerte Informationen offengelegt, kann dies schwerwiegende Folgen für eine Institution haben. Unter anderem kann der Verlust der Vertraulichkeit zu folgenden negativen Auswirkungen für eine Institution führen.*“

Dies kann dazu führen, dass geschützte medizinische Daten, zu missbräuchlichen Zwecken genutzt werden können. Bspw. Den Verkauf 
an Unternehmen. Diese können dann aufgrund dieser gezielten Profile erstellen.
	
### G 0.18 Fehlplanung oder fehlende Anpassung

Diese Gefährdung ist besonders relevant aufgrund der Digitalisierung der Patientenakte. 
Diese muss ausreichend vor Cyberangriffen geschützt sein, da Sicherheitslücken zu dem Diebstahl (G 0.16) oder Verlust (G 0.17) von Daten führen könnten, und dies ein hohes Sicherheitsrisiko darstellt. 
"*Es können Schwachstellen entstehen, wenn bei der Planung eines IT-Verfahrens ungeeignete Übertragungsprotokolle ausgewählt werden.*“

### G 0.22 Manipulation von Informationen

Auch diese Gefährdung ist ein wichtiger Punkt, welcher beachtet werden sollte. 
Es muss sichergestellt werden, dass keine manipulation der Daten möglich ist, da diese die Integrität der Daten verletzen würde und dazu führen könnte, dass die Patienten aufgrund falscher Daten falsche Medikamenten, Behandlungen unterzogen werden. 


