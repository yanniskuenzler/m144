### Verlustfreie Komprimierung
#### 2.
Bitsequenz in Bild umwandeln. (Zahlenfolge gegeben & max 7 mal gleiche Farbe hintereiander = 3 Bit)
<br>
010 100 011 110 010 010 010 010 010 010 010 010 010 110 010 110 010 010 010 010 010 010 010 010 001
<br>
2   4   3   6   2   2   2   2   2   2   2   2   2   6   2   6   2   2   2   2   2   2   2   2   1
![Pixelart](./img_pixelart_a_komprimierung.png)

#### 3. Erstellen sie die LZW-Codierung für das Wort «ANANAS» und überprüfen sie mit der Dekodierung ihr Resultat. Danach versuchen sie den erhaltenen LZW-Code «ERDBE<256>KL<260>» zu dekomprimieren.
| Schritt | Zeichenkette | Gefunden | Gespeichert | Temporärer Wörterbucheintrag |
| ------- | ------------ | -------- | ----------- | ---------------------------- |
| 1       | **A**NANAS       | A        | A           | AN -> 256                    |
| 2       | A**N**ANAS       | N        | N           | NA -> 257                    |
| 3       | AN**AN**AS       | AN       | 256         | ANA -> 258                   |
| 4       | ANAN**A**S       | A        | A           | AS -> 259                    |
| 5       | ANANA**S**       | S        | S           | \-                           |