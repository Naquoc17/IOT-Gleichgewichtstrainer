# Gleichgewichtstrainer Projekt

## Über das Projekt
Dieses Projekt wurde im Rahmen des Moduls „Internet of Things – Smart Sensor Systems“ im Wintersemester 2023/24 entwickelt. Ziel ist es, einen innovativen Fitnesstrainer zu erstellen, der zwei Hauptfunktionen bietet: **„Don’t move“** und **„Keep your balance“**. Das Projekt verwendet das Calliope mini Mikrocontroller-Board und die MakeCode-Entwicklungsumgebung.

### Hauptfunktionen
1. **Don’t Move**  
   - Der Spieler muss stillhalten, ohne sich zu bewegen.
   - Jeder Fehler führt zu einem Punktabzug.
   - Die beste erreichte Zeit wird gespeichert.

[Video anschauen: Don’t Move](./laborbericht-AnhQuocNguyen-1397466/dont%20move.mp4)

2. **Keep Your Balance**  
   - Der Spieler hält das Gleichgewicht in einer beliebigen Position.
   - Fünf Schwierigkeitsstufen mit unterschiedlichen Toleranzwinkeln und Reaktionszeiten.
   - Warnsignale bei Überschreiten des Toleranzwinkels.

[Video anschauen: Keep your balance](./laborbericht-AnhQuocNguyen-1397466/keep%20your%20balance.mp4)

| Schwierigkeitsstufe | Toleranzwinkel (°) | Reaktionszeit (s) |
| ------------------- | ------------------ | ----------------- |
| Noob                | 20–60              | 5                 |
| Athletic            | 20–50              | 4                 |
| Champion            | 15–30              | 3                 |
| Legend              | 10–25              | 2                 |
| God-like            | 5–15               | 1                 |

## Hardware
Das Projekt basiert auf dem **Calliope mini** Mikrocontroller-Board, ausgestattet mit:
- **Sensoren**: Beschleunigungssensor, Gyroskop, Magnetometer, Temperatur- und Lichtsensor.
- **I/O**: 5x5 LED-Matrix, programmierbare Tasten, Lautsprecher.
- **Kommunikation**: Bluetooth, USB, Funk.
- **Schnittstellen**: Grove-Ports, Bananenstecker-Anschlüsse.

## Software
- **Entwicklungsumgebung**: Microsoft MakeCode.
- **Programmiersprache**: JavaScript.
- **Simulator**: Unterstützt das Testen von Programmen vor der Ausführung.

### Code-Struktur
1. **„Don’t move“**  
   - Flussdiagramm-basierte Logik.
   - Präzise Bewegungserkennung und Zeitmessung.
2. **„Keep your balance“**  
   - Schwierigkeitsstufen-Setup.
   - Reaktion auf Bewegungsabweichungen in Echtzeit.

## Ergebnisse
- Die Funktionen wurden erfolgreich implementiert und getestet.
- Präzise Erkennung von Bewegungen und Einhaltung der Schwierigkeitsstufen.
- Effektiver Einsatz zur Verbesserung der Körperspannung und Balance.

## Fazit
Der Gleichgewichtstrainer zeigt, wie Mikrocontroller-Technologie effektiv für Fitness- und Bildungszwecke genutzt werden kann. Das Projekt demonstriert die Vielseitigkeit des Calliope mini und die Benutzerfreundlichkeit von MakeCode.

---

### Autor
**Anh Quoc Nguyen**  
Student, Fachbereich Informatik & Ingenieurwissenschaften  
Frankfurt University of Applied Sciences  

### Betreuung
Prof. Dr. Bergbauer


