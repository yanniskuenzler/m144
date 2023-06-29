### Theorie Symmetrische Veschlüsselung
#### Caesar Verschlüsselung (klassisch)
- basiert auf dem Alphabet (a, b, c, d, e..., y, z)
- Schlüssel wird festgelegt der aussagt, um wie viele Stellen die Buchstaben im Alphabet verschoben werden sollen
- Bsp: Schlüssel ist 4 -> A wird zu D
##### Caesar Entschlüsselung
- Botschaften, die mit der Caesar Veschlüsselung verschlüsselt wurden, können auf zwei Arten entschlüsselt werden
<br>
Bruteforce
<br>
Man probiert einfach jeden Schlüssel aus und schaut ob die Botschaft eine Sinn ergibt
<br>
Analyse
<br>
Es kann eine Analyse durchgeführt werden. Diese Möglichkeit bietet zum Beispiel das Tool "CrypTool" an. Es wird dann geschaut welcher Buchstaben am häufigsten vorkommt. Basierend auf der Annahme, dass das 'E' in der "echten" Sprache am meisten vorkommt, wird dann vermutet, dass dieser Buchstaben einem 'E' entspricht.

#### Vigenère Verschlüsselung (klassisch)
- benötigt ein Schlüsselwort und eine Buchstabentabelle
- ist der Schlüssel beispielsweise SECRET und das zu verschlüsselnde Wort ENIGMA lautet das verschlüsselte Wort: WRKXQT

#### AES Verschlüsselung (modern)
- dies ist eine Verschlüsselung, welche beispielsweise im Unterschied zu einer Caesar Verschlüsselung häufig in produktiven Projekten und Anwendugen zum Einsatz kommt