### Aufgaben

##### 2. Wandeln sie die folgende Dezimalzahl ohne Taschenrechner in die entsprechende Binärzahl um: 911
1110001111

##### 3. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Dezimalzahl um: 10110110
182

##### 4. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Hexadezimalzahl um: 1110'0010'1010'0101
E2A5

##### 5. Der Addierer einer ALU erhält für Zahl-A: 1101'1001 und für Zahl-B: 0111'0101. Was wird man als Resultat erhalten? Erklären sie!
- Zahl A: 217
- Zahl B: 117
- Ergebnis: 334 -> Dataoverflow!

##### 6. Sie analysieren mit den Network-Sniffer Wireshark ihren Network-Traffic. Sie haben in OSI-Layer3 unter anderem folgende Bitkombination herausgelesen: 1100 0000 . 1010 1000 . 0100 1100 . 1101 0011 - Was bedeuet dies? Beantworten sie diese Frage möglichst umfassend.
192.168.76.211 -> IPv4

##### 7. Nun wurde ihre Neugier geweckt und sie untersuchen erneut ihr Netzwerk mit Wireshark, diesmal aber den  OSI-Layer2 und finden unter anderem folgende Bitkombination: 1011 1110 - 1000 0011 - 1000 0101 - 1101 0101 - 1110 0100 - 1111 1110 Was bedeuet dies? Beantworten sie diese Frage möglichst umfassend.
BE:83:85:D5:E4:FE -> IPv6

##### 8. In einer LINUX-Shell (Terminal) entdecken sie folgende Programmzeile: chmod 751 CreateWeeklyReport - Was bedeuet dies? Beantworten sie diese Frage möglichst umfassend.
751 -> Bei einer Berechtigung gibt es immer drei Gruppen, die angegeben werden. Der Eigentümer, der Gruppe und die restlichen.
- 7: Eigentümer - 1 + 2 + 4 (Execute + Write + Read)
- 5: Gruppe - 1 + 4 (Execute + Read)
- 1: Sonstige - 1 (Execute)

##### 9. Dimensionieren sie für den Matterhorn-Express, wo insgesamt 107 Gondeln die Touristen von Zermatt auf den Trockenen-Steg befördern, die Codebreite des Binärcodes für die Kabinenzählung. Und wenn sie schon dabei sind, gleich noch dies: Auf dieselbe Art möchte der Betreiber die Anzahl Touristen pro Tag ermitteln. Die Bahn ist täglich maximal 12 Stunden in Betrieb und die Förderleistung der Bahn wird mit maximal 2800 Personen pro Stunde angegeben.
7 Bit genügen

##### 10. In der Arithmetisch-Logischen Unit (ALU) ihres 8Bit-Mikrokontrollers steht im Register-1 (8 Bit-Speicherzelle) der binäre Wert 1001 1110 und im Register-2 (8 Bit-Speicherzelle) der binäre Wert 1100 1101. Beim nachfolgenden Ausführungsschritt sollen die beiden Werte mathematisch addiert (ADD) werden und das Resultat in Register-3 (8 Bit-Speicherzelle) gespeichert werden. Welche Bitkombination erwarten sie nach der Durchführung der ADD-Operation im Register-3? Begründen sie ihre Antwort.
- Register 1: 1001 1110 -> 148
- Register 2: 1100 1101 -> 205
- Ergebnis: 353 -> Speicher zu klein (erwarteter Wert: 1111 1111)

##### 11. Ihr Arbeitsspeicher, der übrigens ähnlich aufgebaut ist, wie der Autosilo aus Aufgabe 16, hat eine Kapazität von 4kiB. Wie viele Bit werden darin gespeichert? (Hinweis: 1kiB=1024B)
1B = 8b -> 8 * 1024 * 4 = 32'768

##### 12. Sie untersuchen einen Arbeitsspeicher mit 12-Bit-Adress- bzw. 16-Bit-Datenbus.Welche Speicherkapazität in kiB besitzt dieser? Wie lautet die Speicheradresse des ersten Datenbytes und wie die Speicheradresse des letzten Datenbytes?
(2^12) * 2 = 8192 -> Die Speicherkapazität beträgt 8kiB.

##### 13. Zwei Geräte sind mit einer seriellen Leitung und zusätzlichem Taktsignal verbunden. Das Taktsignal beträgt 1MHz. Wieviele Bytes können damit pro Sekunde übertragen werden? Wieviele Bytes pro Sekunde könnten übertragen werden, wenn die Verbindung der beiden Geräte nicht seriell, sondern 8 Bit-parallel wäre?
