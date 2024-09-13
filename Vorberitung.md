---
tags:
  - Abschluss
  - Übung
---
# Orga
**Termin:** Mo (9:30 - 14:00), Fr (9:00 - )

# 2024-09-06
## Themen
- SQL
- IPv6 & IPv4
- VPN
- Firewall
- VLANs
- Switching
- WLAN
- AD / User Managment
- DNS
- Cloud
- RAID / JBOD
- Backup (Archive Bild)
- Routings
- Malware und Prevention
- Storage
- VMs (Hypervisors)
- WISO (BGP)
	- Procura
	- Unternehmens Formen
	- Markt arten
	- Dienst- / Werksvertrag
	- Berufsbildungs- & Mutterschutzgesetz
		- Berufsausbildungsschutz 
	- Wettbewerbsrecht
	- Kündigungsschutz
	- GANT
	- Netzplan
	- 
- POE
- CSMA CD/CA
- Netz Topologie
- Verschlüsselung


## Prio
1. Networking
	- IPv6
	- Routing
	- VLANs
	- Firewall
	- Switching
	- Netz Topologie
	- DNS
2. WISO
3. SQL
2. Storage
3. RAID 
4. Backup


# Networking
## IPv6
IPv6 wird in Hexadecimal (basis 16). 0-9 A-F
Die Länge einer IPv6 sind 128b mit 16b blöcken (4 Charakter), trennung mit :

| 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  | 13  | 14  | 15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | A   | B   | C   | D   | E   | F   |
### Präfix
Standard ist das Präfix 64b lang.
#### Standard
**Internet**
Präfix: *2001:0db8*

**Link-Local**
Präfix: *fe80::/10*
Präfix wenn nicht ins Internet geroutet wird (Local)

**Unique-Local**
Präfix: *fc00::/7*
Für IPv4 ähnliche Local Adress aufbau

**Mulitcast**
Präfix: *ff00::/8*
Senden eines Packets an mehrer definierte Endgeräte


### Kürzen
- 75f5:0826:018b:31d9:1575:cd7a:be86:76aa

**Einmal 0 Segment kürzen**: 
75f5:0826:**0000**:31d9:**0000**:cd7a:be86:76aa
-> 75f5:0826:**0**:31d9:**0**:cd7a:be86:76aa

**Zwei oder mehr aneinander 0 Semente kürzen**
75f5:0826:**0000:0000:0000**:cd7a:be86:76aa
-> 75f5:0826::cd7a:be86:76aa
*Hinweis:* Kann Nur einmal gemacht werden

**Eine 0 im Segemnt kürzen**
75f5:**0**826:0000:0000:0000:cd7a:be86:76aa
-> 75f5:**826**:0000:0000:0000:cd7a:be86:76aa

### Subnetting 