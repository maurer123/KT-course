# Fragebogen: Wort-Entropie (word_dictionary.py)

Nach dem Ausführen von `word_dictionary.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

Analyze the file:  /home/christopher/kommunikationstechnologie/KT-course/lab_suite/labs/01_04_Datenkompression/submissions/sidedata/sampletext.txt
Total number of words:     123
Number of different words: 92

-------Table of words:-----------------------------------------
                            the | cnt=  8    p=0.065   H=3.943 bit/word   H_av=0.256 bit/word
                            And | cnt=  5    p=0.041   H=4.621 bit/word   H_av=0.188 bit/word
                           city | cnt=  4    p=0.033   H=4.943 bit/word   H_av=0.161 bit/word
                            its | cnt=  4    p=0.033   H=4.943 bit/word   H_av=0.161 bit/word
                             it | cnt=  4    p=0.033   H=4.943 bit/word   H_av=0.161 bit/word
                            The | cnt=  3    p=0.024   H=5.358 bit/word   H_av=0.131 bit/word
                        eternal | cnt=  3    p=0.024   H=5.358 bit/word   H_av=0.131 bit/word
                           woke | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                           from | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                        slumber | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                             of | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                             We | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                              A | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                          sleep | cnt=  2    p=0.016   H=5.943 bit/word   H_av=0.097 bit/word
                             To | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         serene | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         sounds | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         sirens | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             No | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            one | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          knows | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            how | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       happened | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             Or | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           when | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            yet | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            did | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           knew | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             in | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            our | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         hearts | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            Our | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          world | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          could | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            not | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             be | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          saved | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           self | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                      fulfilled | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       prophecy | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            now | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          we're | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           ones | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           left | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           with | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          ruins | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         dreamt | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          final | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             It | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          dream | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       Concrete | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          bones | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                        breathe | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                        Beating | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          heart | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         ‘nеath | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       pavement | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            Thе | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         silver | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         fields | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          below | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         geyser | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       flooding | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          lands | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          Black | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                        murmurs | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          death | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          light | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          where | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       dreamers | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          never | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       sleeping | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           lies | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                         before | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             me | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            can | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           only | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          stand | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                          guard | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             As | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             is | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                        passing | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                        through | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             On | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                            way | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           into | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                       darkness | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             So | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           goes | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             on | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                             so | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
                           went | cnt=  1    p=0.008   H=6.943 bit/word   H_av=0.056 bit/word
-----------------------------------------------------------------

Average Entropy H = 6.267 bit/word
Total Entropy of 123 words H=770.810 bit (97 bytes)
Size of text file: 654 bytes


---

**2. Deine Kommentierung**

- Wie unterscheidet sich die Wort-Entropie von der Zeichen-Entropie (entropy1.py)?  

  Die durchschnittliche Wort-Entropie beträgt 6,267bit/Wort, im Vergleich war die Entropie pro Zeichen 4,435bit/Zeichen. Das liegt daran, dass jetzt ganze Wörter als Symbole betrachtet werden und da viele Wörter nur einmal im Text vorkommen (97 Wörter bei 123 Wörtern gesamt), ist die Redundanz kleiner, also die Entropie pro Wort höher.

- Was sagt die Entropie in Byte im Vergleich zur tatsächlichen Dateigröße aus?  
  Die berechnete Gesamtentropie ist 97 byte, die Dateigröße 654 byte, das heißt, die Datei könnte auf eine viel kleinere Größe komprimiert werden wenn man eine optimale Kodierung verwendet. Bei entropy1.py war die Gesamtentropie 356 byte.
