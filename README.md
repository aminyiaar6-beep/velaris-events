# Velaris Events · web

Web publicada: **https://velaris-events-sl.netlify.app**

Aquest projecte està connectat a Netlify. **Qualsevol canvi que guardeu aquí es publica sol a la web en un o dos minuts.**

## Què hi ha a cada fitxer

| Fitxer | Què és |
|---|---|
| `index.html` | Tota la web: textos, packs, preus, viatges i el formulari |
| `gracies.html` | Pàgina que surt després d'enviar el formulari (només si el navegador no té JavaScript) |
| `img/` | Totes les fotos i el logo |

## Com canviar un text o un preu

1. Obriu `index.html` i cliqueu el **llapis** (✏️, «Edit this file») a dalt a la dreta.
2. Premeu **Ctrl + F** i busqueu el text que voleu canviar (per exemple `2.100 €` o `Pack Plata`).
3. Canvieu només el text, sense tocar res del que hi ha entre `<` i `>`.
4. Cliqueu **«Commit changes…»** (botó verd), escriviu què heu canviat (ex: «Canvio preu casament plata») i torneu a clicar **«Commit changes»**.
5. Al cap d'un o dos minuts, recarregueu la web amb **Ctrl + Shift + R**.

## Com canviar una foto

1. Entreu a la carpeta `img/`.
2. **Add file → Upload files** i pugeu la foto nova **amb el mateix nom** que la que voleu substituir (ex: `cas-plata.webp`). Ha de ser en format `.webp`; si teniu un `.jpg`, digueu-li a Claude que us la canviï.
3. **Commit changes**.

Noms de les fotos: `hero` (portada), `logo`, `cas-plata`, `cas-or`, `cas-diamant`, `inf-plata`, `inf-or`, `inf-diamant`, `nado-or`, `nado-diamant`, `adults`, `soltera`, `jubilacio`, `empresa`, `pinta1`, `pinta2`, `pinta3`, `inflables`, `escuma`, `foto2`, `foto3`, `italia`, `espanya`, `franca`, `indonesia`, `regneunit`, `portugal`, `finlandia`.

## Si alguna cosa es trenca

Cada canvi queda guardat. A Netlify (o aquí, a **History** de cada fitxer) es pot tornar a una versió anterior. No toqueu el formulari (`<form name="sollicitud-event" …>`): és el que envia les sol·licituds a **velariseventss@gmail.com**.
