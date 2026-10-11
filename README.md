# Taiwan-Reiseatlas

Weiterentwicklung der bestehenden statischen Anwendung mit **22 Übernachtungen in der unveränderten Uhrzeiger-Rundreise**. Keine zusätzliche Veröffentlichung aktiviert.

## Dateien
- `index.html`: Einstieg, Robots-Metadaten unverändert streng (`noindex, nofollow, noarchive, nosnippet, noimageindex` für robots, googlebot, bingbot).
- `style.css`: Responsives Layout.
- `data.js` und `stops/*.js`: acht Stopps, 75 Sehenswürdigkeiten und 49 Tagesausflugskandidaten ohne konkrete Reisezeitangaben; grobe Klima-, Reisezeit-, Attraktivitäts- und Verkehrsangaben.
- `app.js`: Leaflet/OpenStreetMap mit Ortsmarkern, thematischen Filtern, Dossiers, Google-Maps-Fotolinks, Fahrrad- und Kite-Hinweisen.
- `gallery.js`: Pro Ziel eine direkt eingebundene Galerie mit bis zu vier automatischen Wikimedia-Commons-Suchergebnissen. Erst beim Scrollen geladen; Bilddateiseiten verlinken Urheber und Lizenz. Keine Garantie, dass jedes Suchbild das Ziel zeigt.
- `extras.js` und `extras-ui.js`: sieben optionale weitere Reiseorte mit empfohlenen Nächten, Klimaorientierung, ÖPNV-Hinweisen, Fotogalerien und braunen Kartenmarkern. Die Originalroute ist unverändert; beispielhafte Erweiterung auf 28 Nächte.
- `robots.txt`: **unverändert**, insbesondere AI-Crawler-Sperren.

## Nutzung
`index.html` öffnen oder die vorhandene GitHub-Pages-Konfiguration nutzen. Statische HTML/CSS/JS-Dateien, kein Backend, kein API-Key, keine Cookies, kein eigenes Tracking. Die externe Leaflet-Bibliothek, OSM-Kacheln und die Wikimedia-Commons-API/Bildserver benötigen Internet und übertragen technische Abrufdaten.

## Recherche- und Qualitätsgrenzen — laufende Recherche
- Die geografischen Koordinaten, Besuchsdauern und Reisezeitbereiche sind Näherungen, nicht vollständig vor Ort verifiziert. Die Reisezeiten der Listen sind bewusst breite Orientierungswerte und **keine konkret geprüften ÖPNV-Verbindungen**; besonders letzte Rückfahrt und Feiertagsfahrplan prüfen. Der Link zum Tourismusportal ist keine Einzelquellenbelegung für das jeweilige Ziel.
- 2027-Öffnungszeiten, Verbindungen, Preise, Windprognosen und Spot-Freigaben sind nicht bestätigt.
- Januar-Temperaturen sind gerundete historische Orientierungsspannen, keine Stationsauswertung oder Wettervorhersage; Niederschlag, Sonnenstunden und Wassertemperatur müssen vor konkreter Entscheidung tiefer recherchiert werden.
- Taroko: massive Erdbebenschäden seit April 2024; nur teilweise zugänglich, Hauptschlucht nicht als sicher planbaren Ausflug voraussetzen. Nationalparkmeldungen lesen.
- Kitesurfen: aufgeführte Küstenabschnitte sind **Prüfgebiete, keine gesicherten Start-/Landeplätze**. Gerade im Wintermonsun böige Windverhältnisse, Brandung, Hindernisse, Schutzgebiete und Rettungsmöglichkeiten lokal prüfen.
- Fahrradstrecken als grobe Varianten, Verleih und TRA-Radmitnahme individuell prüfen.
- Geplante Reiseroute und Aufenthaltsnächte nicht geändert.

## Wesentliche amtliche Quellen und Live-Abfragen
- Taiwan Tourism Administration: https://eng.taiwan.net.tw/
- Central Weather Administration: https://www.cwa.gov.tw/eng/
- Taiwan Railway: https://www.railway.gov.tw/tra-tip-web/tip?lang=EN_US
- Taiwan High Speed Rail: https://en.thsrc.com.tw/
- Taiwan Tourist Shuttle: https://www.taiwantrip.com.tw/
- Taroko National Park: https://www.taroko.gov.tw/en/
- Radverkehr: https://eng.taiwan.net.tw/m1.aspx?sNo=0029976
- OpenStreetMap: https://www.openstreetmap.org/copyright

## Qualitätssicherung
HTML-Metadaten, Dateireferenzen, Anzahl Stopps und Nächte sowie Ergebnisdateien nach Commit überprüfen. Es erfolgte kein vollständiger Browser-, Endgeräte- oder Fahrplantest. Weitere Detailverifikation je Einzelziel empfohlen.