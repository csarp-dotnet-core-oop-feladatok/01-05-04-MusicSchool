# 01-05-04-MusicSchool
Osztályhierarchia UML diagram alapján.
## Zeneiskola
Készítse el az UML diagram alapján az osztályok kódját!

![UML](https://github.com/csarp-dotnet-core-oop-feladatok/01-05-04-MusicSchool/blob/main/MusicScool.png?raw=true)

Az értékelés tulajdonságnál döntse el, milyen átlag esetén kap a diák jeles, jó, közepes, elgséges és elégtelen osztályzatot. 

A teszt kód:
```
Mark firstSemesterInstrument = new Mark("hangszer", 4);
Mark firstSemesterSolfeggio = new Mark("szolfézs", 5);
Mark secondSemesterInstrument = new Mark("hangszer", 3);
Mark secondSemesterSolfeggio = new Mark("szolfézs", 4);
SchoolCertificatePage firstSemester = new SchoolCertificatePage("első félév", firstSemesterInstrument, firstSemesterSolfeggio);
SchoolCertificatePage secondSemester = new SchoolCertificatePage("második félév", secondSemesterInstrument, secondSemesterSolfeggio);
SchoolCertificate joshepCertificate = new SchoolCertificate("József", firstSemester, secondSemester);
Console.WriteLine(joshepCertificate);
```
A teszt kód kimenete:
```
József éves értékelése.
A(z) első félév eredménye:
hangszer jegy:4
szolfézs jegy:5
Átlageredmény:4,5
Minősítés:kitünő
A(z) második félév eredménye:
hangszer jegy:3
szolfézs jegy:4
Átlageredmény:3,5
Minősítés:jeles
```
           
