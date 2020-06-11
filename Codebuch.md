
## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.rm (Codierung der Datensätze)

## Ursprung und Datenerhebung

Das Netzwerk ist ein *ungerichtetes two-mode Akteursnetzwerk*. 
Es wurden der Typ, das Geschlecht, Alter, die Studienrichtung, die Anzahl der gewonnenen Pulitzer-Preise in den Jahren 2014-2019 und die Nationalität erhoben. Zusätzlich wurden die Twitter-Accounts der Gewinner untersucht, um mögliche Beziehungen zu erforschen.


# EDGE-Attribute

**id** <br>  
(eindeutige Codierung des Knoten)   

**weight**  <br> 
Beziehungsstärke <br>
3 = Kollegen in einer Organisation  <br>
2 = Kooperation <br>
1 = Twitter-Follower <br>  


# NODE-Attribute  
  
**id**  <br> 
Identische ID wie aus der edgelist zur Identifikation der Knoten. 


**type** <br> 
1 = Person <br>
2 = Institution <br> 


**sex**  <br>     
1 = männlich   <br>
2 = weiblich <br>
3 = divers <br>
  
**age** <br>    
1 = unter 30 Jahre <br>
2 = 30-39 Jahre <br>
3 = 40-49 Jahre <br>
4 = 50-59 Jahre <br>
5 = über 60 Jahre <br>

**study** <br>     
1 = journalism and writing <br>
2 = politics <br>
3 = history <br>
4 = other <br>
  
**prices**<br>    
Anzahl der gewonnen Pulitzer-Preise von 2014-2019  
  
**nationality** <br>    
1 = USA   <br>
2 = Germany<br>
3 = other   <br>

**twitter** <br>
1 = ja <br>
2 = nein <br> 
##
