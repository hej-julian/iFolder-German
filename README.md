# iFolder

Ein kleines Tool, mit dem man die Symbole von macOS-Ordnern im Browser anpassen kann. Eine einzige HTML-Datei, sofort einsatzbereit.

## Funktionen

- Anpassung der Farbsymbole für Ordner und der Hintergrundfarbe bei „Ordner mit Dateien“
- Zwei integrierte Grafikbibliotheken:
  - **Symbole**: Tabler Icons, Hunderte von allgemeinen Symbolen, nach Kategorien durchsuchbar
  - **Marken**: Eine Auswahl von über 350 Simple Icons-Markensymbolen, die acht große Kategorien abdecken: Entwicklung / Design / Soziales / Medien & Unterhaltung / Cloud & KI / Produktivität / Einkauf & Lifestyle / Browser & Systeme
- „Markenfarben verwenden“ mit einem Klick: Nach Auswahl einer Marke werden automatisch die offiziellen Farben angewendet (z. B. GitHub-Schwarz, Figma-Rot, Claude-Braun-Orange); jederzeit kann wieder auf benutzerdefinierte Farben umgeschaltet werden
- Unterstützung für Farbpipette, Farbkarte und voreingestellte Paletten
- Export als PNG/SVG, direkt in macOS verwendbar („Informationen anzeigen → auf das Symbol in der oberen linken Ecke ziehen“)

## Verwendung

Laden Sie dieses Repository herunter und doppelklicken Sie auf `index.html`, um es im Browser zu öffnen. Kein Build und keine Installation von Abhängigkeiten erforderlich.

Wenn Sie einen lokalen Vorschaudienst benötigen, können Sie eine der folgenden Optionen wählen:

```bash
# Python
python3 -m http.server 8099

# Node
npx serve .
```

Rufen Sie anschließend `http://localhost:8099` auf.

## Browser-Kompatibilität

Empfohlen werden die neuesten Versionen von Chrome, Safari und Edge. Für Mobilgeräte angepasst.

## Technischer Stack

- Reines HTML / CSS / natives JavaScript, eine einzige Datei
- [iro.js](https://iro.js.org/) – Farbauswahl
- [Tabler Icons](https://tabler.io/icons) – Symbol-Icon-Bibliothek (MIT)
- [Simple Icons](https://simpleicons.org/) – Marken-Icon-Bibliothek (CC0-1.0), Icon-Daten sind in `index.html` eingebunden, keine Internetverbindung erforderlich

## Lizenz

MIT

Markennamen und Logos sind Eigentum ihrer jeweiligen Inhaber; iFolder dient lediglich als grafisches Darstellungswerkzeug und stellt keine Billigung oder Zugehörigkeit zu einer Marke dar.
