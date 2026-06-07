# 360° Rundgang mit Raumwechsel

Diese Version nutzt Pannellum mit mehreren Szenen.

## Dateien

- `index.html`
- `projekt1.html`
- `style.css`
- `360-bilder/`

## Bilder hochladen

Lade in GitHub in den Ordner `360-bilder` diese drei Bilder hoch:

- `eingang.jpg`
- `raum1.jpg`
- `raum2.jpg`

Danach öffnest du `projekt1.html`.
Dort kannst du über Hotspots zwischen den Räumen wechseln.

## Weitere Räume hinzufügen

In `projekt1.html` kannst du im JavaScript-Teil unter `scenes` weitere Räume ergänzen.

Beispiel:

```javascript
raum3: {
  title: "Raum 3",
  type: "equirectangular",
  panorama: "360-bilder/raum3.jpg",
  hotSpots: [
    {
      pitch: -2,
      yaw: 180,
      type: "scene",
      text: "Zurück zu Raum 2",
      sceneId: "raum2"
    }
  ]
}
```

## Hotspot-Positionen

- `yaw` = links/rechts im Bild
- `pitch` = hoch/runter im Bild

Wenn der Punkt nicht an der richtigen Stelle ist, ändere die Zahlen.
