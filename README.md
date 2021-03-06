# SWE

Allgemeine Hinweise zum Programmentwurf
Abgabedatum: 28. August 2016, 23:59 Uhr

Dokument:
  Inhaltsverzeichnis                                                      
  Aufgabenstellung „as it is“ ohne Deckblatt
  Kapitelreihenfolge: (eigentliche Nummerierung beginnt individuell)
  
    1. Lastenheftanalyse (Fragen & Antworten)                              | FERTIG
      
    2. Use-Case-Diagramme                                                  | FERTIG
      
    3. AKD + Analysemuster                                                 | FERTIG
    
    4. Sequenzdiagramm                                                     | FERTIG
        
    5. Aktivitätsdiagramm                                                  | FERTIG
       
    6. EKD + Änderungen zum Analyseklassendiagramm + Entwurfsmuster        | FERTIG
        
    7. GUI-Entwurf                                                         | FERTIG
      
    8. Zustandsdiagramm oder RDB-Mapping                                   | FERTIG
    
    9. Pseudocode                                                          | FERTIG
      
    10. Besonderheiten                                                     | FERTIG
      
    
  Dateiformate:
  PDF, DOC(x), ODT (wenn zusätzlich Diagramme in Dateien: als ZIP packen)
  
  Dateinamen:
  PE-SWE1-2015_Hochzeitsplaner_<Name1>_<Name2>.[PDF | DOC(x) | ODT]


Offizielle Aufgabenstellung:

Einzelne Lastenheftpunkte sind bewusst offen gehalten. Denken Sie darüber nach, welche Informationen zusätzlich sinnvoll oder auch notwendig sind. Schauen Sie evtl. nach einzelnen Zusammenhängen im Inter-net nachDie Anwendung soll als eine Java-Applikationmit JDBC realisiert werden, die von beliebigen Rechnern aus gestartet wird. Dabei wird auf eine zentrale Datenbank zugegriffen, die auf einem Server läuft.

3.1Analyse Für die Analyse sind zu erstellen:
a)Analyse des Lastenhefts(Fragen und Antworten).
Auswahl von 5Lastenheftfunktionen (oder 4 LF und 1 LD (oder LL)).Fragen sorgfältig formulieren und ausführlich beantworten (Bewertung erfolgt proportional zur Kom-plexität der gewählten LFs).Zu beachten: die restlichen Lastenheftfunktionen müssen für ein sinnvolles Ergebnis beim Entwurf trotzdem beantwortet werden. Dies können Sie jedoch in „Ihrer persönlichen Kurzform“ abhandeln.Kennzeichnen Sie die von Ihnen gewählten Lastenheftfunktionen (Z.B. dezent grauoder farbighinter-legen, LF-Nummer in Fettschrift etc.)
b)Ein Use-Case-Diagramm der gesamten Anwendung incl. Beschreibung.
c)Eine Verfeinerung des Use-Case-Diagramms incl. Beschreibung. (nach Absprache)
d)Ein Analyse-Klassendiagrammincl. Beschreibung(Untersuchen Sie dabei den Einsatz geeigneter Analysemuster)

3.2Sequenzdiagramm und Aktivitätsdiagramm (Analyse oder Entwurf)
Erstellen Sie ein Sequenzdiagramm und ein Aktivitätsdiagramm (incl. Beschreibung) für zweider folgen-denSzenarios (ein AD für eingewähltesSzenario, ein SD für ein anderes gewähltes Szenario), welche das Anlegen jeweils einer Aktion beschreiben:
a)Aktion „Catering“anlegen.
b)Aktion „Trauung“ anlegen.
c)Aktion „Kirchliche Trauung“ anlegen.
d)Aktion „Unterhaltungsbeitrag“ anlegen.

Für beide Diagramme ist das jeweilige Szenario ausführlich zu entwickeln (Pseudocode). Es sind sämtli-che referenzierten Elemente zu berücksichtigen und es sollen jeweils mehrere beteiligte Personen zugeord-
net werden. In allen Fällen wird eine (noch) leere Datenbank angenommen. Denken Sie an geeignete Dia-grammverfeinerungen.

3.3ZustandsdiagrammErstellen Sie ein Zustandsdiagramm für eineHochzeitsveranstaltung(von Erstellung bis Löschung). 

3.4EntwurfAbzuliefern sind hier (alle Diagramme und GUIs jeweils mit Beschreibung):
a)Entwurfsklassendiagramm (Untersuchen Sie dabei den Einsatz geeigneter Entwurfsmuster)
b)GUI-Entwurf (CorelDRAW-Level), es müssen 1 –2 aussagekräftige Oberflächen sein

4.Vereinfachungenfür den Programmentwurf
1.Es muss nicht dafür gesorgt werden, dass auf dieselben Daten der Datenbank nicht gleichzeitig zugegriffen werden kann, d.h. es ist kein Locking-Mechanismus erforderlich. 
2.Eine Protokollierfunktion ist für die Anwendung nicht erforderlich (in der Realität natürlich schon!).
3.Ein Loginvorgang und eine Benutzerverwaltung müssenin den Klassendiagrammen nicht model-liert und später auch nicht implementiertwerden
4.Die Synchronisation der Daten muss bei der Implementierung nicht berücksichtigt werden.

P.S.:Kopieren Sie den Aufgabentext (d.h. ohne Frontseite) vollständig als erstes Kapitel „Aufgabenstel-lung“ an den Anfang Ihrer PE-Dokumentation und verwenden Sie den Aufgabentext zusätzlich als Rahmen für Ihre Lastenheftanalyse („ausfüllen“ mit Fragen und Antworten)

