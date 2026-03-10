# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

Enter the string to compute Huffman Code Tree: ---------------------------------------------------------
Dictionary of Characters with char frequency:       {'A': 5, 'M': 1, 'D': 1, 'H': 1, 'R': 4, 'I': 1, 'B': 1, 'V': 2, 'L': 1, 'K': 1, 'J': 1}
Dictionary converted into a list:                   dict_items([('A', 5), ('M', 1), ('D', 1), ('H', 1), ('R', 4), ('I', 1), ('B', 1), ('V', 2), ('L', 1), ('K', 1), ('J', 1)])
List of characters sorted to descending frequency:  [('A', 5), ('R', 4), ('V', 2), ('M', 1), ('D', 1), ('H', 1), ('I', 1), ('B', 1), ('L', 1), ('K', 1), ('J', 1)]
Huffman Code Dictionary:                            {'D': '0000', 'M': '0001', 'I': '0010', 'H': '0011', 'R': '01', 'A': '10', 'V': '110', 'L': '11100', 'B': '11101', 'J': '11110', 'K': '11111'}

 Char | Huffman code 
----------------------
 'A'  |          10
 'R'  |          01
 'V'  |         110
 'M'  |        0001
 'D'  |        0000
 'H'  |        0011
 'I'  |        0010
 'B'  |       11101
 'L'  |       11100
 'K'  |       11111
 'J'  |       11110


**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  
  Die ausgegebenen Huffmann-Codes zeigen, welche Codewörter jedem Zeichen der Eingabe zugeordnet worden sind. 

- Warum haben häufigere Zeichen kürzere Codewörter?  
  
  Häufigere Zeichen haben kürzere Codewörter, damit die Gesamtlänge der codierten Nachricht minimiert wird. 
