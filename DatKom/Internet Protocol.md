---
aliases: []
tags:
- DatKom
---
## Aufgaben
- Bereitstellung weltweit eindeutiger Adressen
	- IPv4: 32 Bit, IPv6: 128 Bit
	- Hierarchische Struktur
- Definiton von Verarbeitungs/Weiterleitungsregeln samt eines zugehörigen Paketformats
	- Header mit Kontrollinformationen
	- Maximale Paketgrößte: 64 kByte (in der Praxis: 1500 Byte)

### Subnetze
- Einige Bits der Host-Adresse werden als Netzwerk-ID genutzt
- Eine Subnetz-Maske identifiziert die Bits, die zur Identifizierung des Netzes genutzt werden
- Router ermitteln durch Kombination einer IP-Adresse und einer Subnetz-Maske, in welches Teilnetz ein Paket geschickt werden muss
- 