# Vorlage für die Bachelor Thesis für den Studiengang Sozialinformatik an der HS Fulda

Hier findet ihr eine Vorlage für eine Bachelor Thesis im Studiengang Sozialinformatik an der Hochschule Fulde.
Diese ist natürlich problemlos auf andere Studiengänge und/oder Hochschulen anpassbar.

Hierbei wurde sich zum einen an der Handreichung zum wissenscaftlichen Arbeiten des Fachbereichs Sozialwesen (https://www.hs-fulda.de/fileadmin/user_upload/FB_Sozialwesen/Studiengaenge/BASA-P/Handreichung_WissArbeiten_2013.pdf) orientiert.

Zum anderen an den Vorgaben zur digitalen Abgabe von Bachelor- bzw. Masterarbeiten der Hochschule Fulda (https://www.hs-fulda.de/studieren/mein-studium/studium-organisieren/digitale-thesen)

Dabei wurde darauf geachtet, dass das Ergebnis PDF/A-1b konform ist. Dies wurde mit folgenden Validator überprüft: https://www.pdf-online.com/osa/validate.aspx. Dabei ist es wichtig zu beachten, dass eingefügte Bilder keinen transparenten Hintergrund, oder sonstige transparente Bereiche, aufweisen.

In der Datei ``src/konfiguration.tex`` wird die Arbeit personalisiert. Die Autorendaten werden auch in die Meta-Daten der PDF aufgenommen.

In der Datei ``bachelorthesis.tex`` kann festgelegt werden, ob für jedes Kapitel eine eigene Datei genutzt werden soll (``src/chapter/kapitelname.tex``) oder ob lieber mit einer großen Datei gearbeitet werden soll (``src/inhalt.tex``). Die Vorlage verweist auf die Kapitel.

Über ``go.sh`` kann die Thesis in einer Shell gebaut werden.

Viel Spass damit!

SIn16
