
## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.rm (Codierung der Datensätze)

## Ursprung und Datenerhebung

Das Netzwerk ist ein *ungerichtetes two-mode Akteursnetzwerk*. 
Es wurden der Typ, das Geschlecht, Alter, die Studienrichtung, die Anzahl der gewonnenen Pulitzer-Preise in den Jahren 2014-2019 und die Nationalität erhoben.


# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   

**weight**  
Beziehungsstärke 
3 = Kollegen in einer Organisation  
2 = Kooperation
1 = Twitter-Follower  


# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten. 


**type**
1 = Person
2 = Institution 


**sex**      
1 = männlich   
2 = weiblich
3 = divers
  
**age***    
1 = unter 30 Jahre
2 = 30-39 Jahre 
3 = 40-49 Jahre
4 = 50-59 Jahre
5 = über 60 Jahre

**study**    
1 = journalism and writing
2 = politics
3 = history
4 = other
  
**prices**    
Anzahl der gewonnen Pulitzer-Preise von 2014-2019  
  
**nationality**    
1 = USA   
2 = Germany
3 = other   

**twitter**
1 = ja
2 = nein
##
