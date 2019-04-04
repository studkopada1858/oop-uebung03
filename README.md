_Übungsaufgabe zur Veranstaltung [Programmieren 2](https://hsro-wif-oop.github.io) im [Bachelorstudiengang Wirtschaftsinformatik](https://www.th-rosenheim.de/technik/informatik-mathematik/wirtschaftsinformatik-bachelor/) an der [Hochschule Rosenheim](http://www.th-rosenheim.de)._


# Generics

In dieser Übung überarbeiten wir die Datenstrukturen _Stack_ und _Set_ aus den letzten beiden Übungen um sie _generisch_ zu implementieren.


## Teilaufgabe 1: Stack

Gegeben ist die Musterlösung aus [Übung 1](https://github.com/hsro-wif-oop/uebung01), welche einen Stack für `char` implementiert.

- Modifizieren Sie das Interface `Stack` sowie die Klasse `StackImpl` so, dass sie generisch sind.
- Ändern Sie anschließend den Testcase `StackTest` so, dass die generischen Klassen verwendet werden.

> Hinweis: Der Testcase `PalindromTest` kann unverändert übernommen werden, sollte allerdings erfolgreich sein.


## Teilaufgabe 2: Set

Gegeben ist die Musterlösung aus [Übung 2](https://github.com/hsro-wif-oop/uebung02), welche ein Set für `String` implementiert, sowie die Klasse `Duplikate`, welche Wörter findet, welche mindestens zwei mal vorkommen.

- Modifizieren Sie das Interface `Set` sowie die Klasse `SetImpl` so, dass sie generisch sind.
- Ändern Sie anschließend den Testcase `SetTest` so, dass die generischen Klassen verwendet werden.
- Modifizieren Sie nun die Klasse `Duplikate` und `DuplikateTest` so, dass die generischen Klassen verwendet werden.

> Hinweis: Verwenden Sie zunächst das Interface `Comparable`.
> Welche Änderungen müssten Sie machen, um stattdessen mit einem `Comparator` zu arbeiten?
