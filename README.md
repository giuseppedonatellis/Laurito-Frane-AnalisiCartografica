# Comune di Laurito – Carta delle tipologie di frane

## Descrizione del progetto  
Questo progetto ha come obiettivo la creazione di una carta tematica che rappresenta le frane presenti nel territorio comunale di Laurito (SA). I dati sono stati ottenuti attraverso il servizio WMS del portale GN del Ministero dell’Ambiente e integrati con informazioni geografiche locali. L’elaborazione è avvenuta in ambiente QGIS, dove le frane cartografate sono state sovrapposte alla base georiferita del territorio comunale.

## Obiettivo dell’esercitazione  
- Creare una carta dei fenomeni franosi mediante servizio WMS ufficiale.  
- Riportare le frane cartografate sulla base georiferita del territorio comunale.  
- Esportare una mappa in formato A4 (JPG, TIFF o PDF) contenente tutti gli elementi cartografici:  
  - Freccia del nord  
  - Barra di scala  
  - Legenda  
  - Coordinate  

## File principali  

### Layer vettoriali
- Poligoni_frane-Laurito.shp, Poligoni_frane-clip-Laurito.shp  
  → Poligoni delle frane mappate nel territorio comunale.

- Laurito.shp  
  → Confine amministrativo del Comune di Laurito (usato come base e per il clipping dei dati frana).

### Layer WMS  
- Servizio cartografico WMS:  
  https://gn.mase.gov.it/portale/servizio-di-consultazione-wms  
  → Utilizzato per visualizzare i fenomeni franosi ufficiali sul territorio nazionale.

### Progetto QGIS  
- Giuseppe Donatellis_step2.qgz  
  → Progetto completo con:
  - Layer poligonali delle frane con simbologia tematica per tipologia.
  - Layer base georiferito del comune.
  - Layer satellitare (opzionale).
  - Composizione cartografica pronta all'esportazione.

### Output finale  
- Mappa A4 in formato .jpg, .tiff o .pdf con:  
  - Titolo  
  - Freccia del nord  
  - Barra di scala  
  - Legenda tipologica  
  - Coordinate e griglia  
  - Scala fissa per coprire l’intera area comunale

## Coordinate di riferimento (CRS)  
- EPSG:32633 – WGS 84 / UTM zona 33N

## Software utilizzato  
- QGIS 3.30.x o superiore  
- Servizio WMS del portale GN  
- Plugin per composizione cartografica

## Flusso operativo  

1. Collegamento al WMS ufficiale: importazione del servizio tramite URL WMS.  
2. Creazione layer delle frane: digitalizzazione o importazione dei poligoni da shapefile.  
3. Clipping dei dati frana sul confine comunale.  
4. Applicazione della simbologia per tipologia di frana.  
5. Composizione della mappa con layout: titolo, legenda, coordinate, freccia nord e barra di scala.  
6. Esportazione della carta finale in formato A4 (JPG/TIFF/PDF).

## Risultati e applicazioni  
- Carta tematica che rappresenta le tipologie di frane presenti nel territorio comunale.  
- Strumento utile per studi ambientali, pianificazione del rischio, urbanistica e protezione civile.

## Autore  
Giuseppe Donatellis  
Corso GIS e Cartografia Geotematica – Università degli Studi di Napoli Federico II

## Suggerimenti per utilizzo futuro  
- Integrare la carta con altri tematismi (es. uso del suolo, litologia, pendenze).  
- Utilizzare la mappa come base per valutazioni di rischio idrogeologico o progettazione territoriale.  
- Pubblicare i dati su un sistema WebGIS per consultazione pubblica o amministrativa.

## Accesso alla visualizzazione della mappa

https://comfy-banoffee-40c2c3.netlify.app/

## Accesso ai dati
https://drive.google.com/drive/folders/1w9gsVwVgrx1lzWPR0EMGUzJvc4rbGnEV?usp=drive_link
