# Anne-Will-Netzwerk-Laura-Ott
 Gästeliste der Talkshow von Anne-Will aus dem Jahr 2022 mit dem Thema Ukraine (für die Folgen 500 bis 503)

 # Datensatz Anne Will #
Codebuch Stand 2026-11
erstellt von Laura Ott (lo034@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe Daten zu den Gästen der Talkshow Anne Will erhoben, die in den Folgen 500 bis 503 erschienen sind.

Das Netzwerk ist ein *bi-modales gerichtetes Netzwerk*. Es wurden zwei getrennte Fragen erhoben:

**Projektarbeitsnetzwerk work**  
1a) Wer ist in welchen Folgen aufgetreten?
1b) Welchen Parteien gehören die Gäste an?


# EDGE-Attribute

**id**  
eindeutige Codierung des Knoten  

**relation**
Welche Art der Zugehörigkeit?
1=Sendegast
2=Parteizugehörigkeit


# NODE-Attribute  
  
**from**  
Gast

**to**
Parteigast od. Talkshowfolge

**type**
1 Person, 2 Organisation




