# Mutterikotelo 3D

Näytöttömän RTK-mittakepin elektroniikkakotelon ("mutteri") 3D-malli selaimessa:
pyöritys, zoomaus ja osien näyttö (alaosa, yläosa, komponenttien tilavaraukset).

Verkossa: https://maxpain12345678.github.io/mutteri-3d/

Avaa paikallisesti:

    python3 -m http.server 8106
    # http://localhost:8106/

three.js 0.128 ladataan CDN:stä (jsdelivr), joten sivu tarvitsee nettiyhteyden.
`ala.json`, `yla.json` ja `komponentit.json` on muunnettu kotelon STL-tiedostoista
14.11.2026. Parametrinen lähde (OpenSCAD) on erillisessä keppi-projektissa.
