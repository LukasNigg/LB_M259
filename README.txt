Beschreibung des Datensatzes:

In meinem ausgewähltem Datensatz geht es um Schachspiele, die auf der Online-Plattform https://lichess.org/ gespielt wurden. Die Tabelle beinhaltete ursprünglich insgesamt 17 Spalten.
Ich habe allerdings einige Spalten gelöscht, weil man damit keine Zusammenhänge erkennen kann.
Ausserdem bestand die Spalte time_increment zuerst aus zwei Werten mit einem Plus-Zeichen dazwischen. Ich habe für die Bereinigung die beiden Werte aufgetrennt und das Plus-Zeichen
entfernt. Um die Tabelle noch weiter zu bereinigen, habe ich alle kategorischen Daten durch Zahlen ersetzt.


Analyse des Datenschutzes:

Ich habe die Spalten white_id und black_id entfernt, da sie Benutzernamen der Spieler enthielten. Alleine mit dem Benutzernamen weiss man normalerweise nicht, welche echte Person damit
gemeint ist, aber man könnte die Namen vergleichen und erkennen, welches die gleiche Personen sind. Somit sind die Daten nun vollständig anonym. Der Ersteller des Datensatzes hat
sich wahrscheinlich auch darauf geachtet, dass sonst keine persönlichen Daten wie z.B. E-Mail-Adresse des Accounts angegeben waren.