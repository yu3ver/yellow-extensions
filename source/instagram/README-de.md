Instagram 0.8.5
===============
Instagram-Fotos einbinden.

<p align="center"><img src="instagram-screenshot.png?raw=true" width="795" height="836" alt="Bildschirmfoto"></p>

## Wie man ein Foto einbindet

Erstelle eine `[instagram]`-Abkürzung. 

Die folgenden Argumente sind verfügbar, alle bis auf das erste Argument sind optional:
 
`Id` = mitlere Teil eines [Instagram](https://www.instagram.com)-Links, z.B. `https://www.instagram.com/p/BISN9ngjV2-/?taken-by=rick_ande`  
`Theme` = Fotothema, momentan nur `light`  
`Stil` = Fotostil, z.B. `left`, `center`, `right`  
`Width` = Fotobreite, Pixel oder Prozent  
`Height` = Fotohöhe, Pixel oder Prozent  

## Beispiele

Foto einbinden:

    [instagram BISN9ngjV2-]
    [instagram BISN9ngjV2- light - 500]
    [instagram BISN9ngjV2- light right 500]

## Einstellungen

Die folgenden Einstellungen können in der Datei `system/extensions/yellow-system.ini` vorgenommen werden:

`InstagramStyle` = Fotostil, z.B. `left`, `center`, `right`  

## Installation

[Erweiterung herunterladen](https://github.com/datenstrom/yellow-extensions/raw/master/zip/instagram.zip) und die Zip-Datei in dein `system/extensions`-Verzeichnis kopieren. Rechtsklick bei Safari.

## Entwickler

Datenstrom. [Hilfe finden](https://datenstrom.se/de/yellow/help/).

<p>
<a href="README-de.md"><img src="https://raw.githubusercontent.com/datenstrom/yellow-extensions/master/source/help/language-de.png" width="15" height="15" alt="Deutsch">&nbsp; Deutsch</a>&nbsp;
<a href="README.md"><img src="https://raw.githubusercontent.com/datenstrom/yellow-extensions/master/source/help/language-en.png" width="15" height="15" alt="English">&nbsp; English</a>&nbsp;
</p>
