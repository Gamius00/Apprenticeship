# Dokumentation – Autorisierter Penetrationstest meiner Webseite

### 1 Einleitung

Ziel dieses Projekts war es, meine eigene Webseite einem grundlegenden Penetrationstest zu unterziehen, um Schwachstellen frühzeitig zu erkennen und die Sicherheit zu erhöhen.
Getestet wurden ausschließlich Systeme, die ich selbst betreibe und für die ich die Erlaubnis habe.

### Verwendete Tools:

Kali Linux (Testumgebung)

Nmap (Port- und Service-Scanning)

Burp Suite (Analyse des HTTP/HTTPS‑Verkehrs, Proxy, einfache Tests)

Browser-Entwicklertools

ggf. Server‑Logs

### 2. Testumgebung

Hardware/OS:

Kali Linux (VM)

Browser: Firefox

Domain: schurig.tech

### 2. Vorgehensweise

**Ziel:** Dienste, Technologien und Angriffsfläche identifizieren.

Nmap-Scan

Durchgeführt wurde ein Port-Scan, um offene Ports und laufende Dienste zu ermitteln:

nmap -sV schurig.tech

Beobachtungen:

Offene Ports: z. B. 80 (HTTP), 443 (HTTPS)

Keine weiteren unnötigen Ports offen (positiv)

2.2 Analyse des Webverkehrs (Burp Suite)

Burp Suite wurde als Proxy im Browser eingerichtet, damit der gesamte Browserverkehr durchs Tool geleitet wird.
Dabei war gut zu erkennen, dass sich in meinem E-Mail Form (https://schurig.tech/contact) ein honeypot befindet.
Dieser ist dazu gedacht um Spambots zu verhindern.

**Ergebnis:**

Es wurden meinerseits keine Schwachstellen erkannt, welche eine Bedrohung darstellen.