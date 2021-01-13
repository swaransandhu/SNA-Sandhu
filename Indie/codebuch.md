# Datensatz Pretest Indie-Kollaborationen #
Codebuch Stand 2021-13-01   
erstellt von Gruppe Indie (ss502@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.rm (Codierung der Datensätze)

## Ursprung und Datenerhebung
Wir haben den Datensatz durch Internetrecherche erfasst.

Das Netzwerk ist ein *ungerichtetes one-mode Akteursnetzwerk*.

# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   
codiert nach Anfangsbuchstaben der Künstler_innen und Bands, jede ID entspricht einer Künster_in oder Band

**weight**  
Beziehungsstärke 
3 = Feature (Gemeinsamer Song),  
0 = gemeinsam auf der Bühne gestanden (Support/Vorband)
--> Evtl. dritte Beziehung = gemeinsames Label

# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten. 

**Anzahl Personen**
Anzahl der Bandmitglieder

**Musiklabel**
Aktuelles und frühere Musiklabel der Band oder der Künster_in.

##

