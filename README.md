# KSN
Sampledatei downloaden: https://lehrer.bulme.at/~nr/Schule/KSN/radio.dat (Samplerate 5 MHz, Mittenfrequenz des Empfängers: 91 MHz)
Mit gnuradio einen FM-Radioempfänger bauen, anstelle der Hardware File Source - Block einfügen. Hinweis: Das Sample enthält mehrere Radiosignale; verwende die Blöcke Multiply und Signal Source mit veränderbarer Frequenz +/- 2.5 MHz nach der File _Source, um den gewünschten Radiosender in die Mitte des Spektrums zu schieben. Vor dem Demodulator soll ein Tiefpass (Grenzfrequenz ca. 40 kHz) eingefügt werden, zur Trennung der Signale.
Audiosignal über die Soundkarte wiedergeben
Visualisieren des Eingangssignales mittels frequency sink und waterfall sink
Github-Repository KSN anlegen, dort das File mit dem Flowgraphen (*.grc) hochladen. README.md anlegen, dort eine kurze Beschreibung inkl. Screenshot des Visualisierungen und des Flowgraphen einfügen.
