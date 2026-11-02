# Vestigia

Installazione generativa — sensori di movimento e computer vision
Nicolò Bulegato, 2026

## Come aprire il progetto

1. Estrarre il contenuto del file ZIP in una cartella qualsiasi
2. Verificare che nella cartella siano presenti **entrambi** questi elementi:

   * `vestigia\_presentazione.html`
   * la cartella `media/` (contiene immagini e video)
3. Aprire il file `vestigia\_presentazione.html` con un doppio click: si apre automaticamente nel browser predefinito
4. Non è richiesta alcuna connessione internet: il sito funziona interamente in locale

## Contenuto della cartella `media/`

* Fotogrammi del canvas accumulato in modalità diurna (sfondo arancione, vestigia blu)
* Fotogrammi del canvas accumulato in modalità notturna (sfondo blu, vestigia arancioni)
* Registrazione video di una sessione di monitoraggio in tempo reale

## Stack tecnico

Python · OpenCV · RTSP (telecamera IP) · rilevamento tramite background subtraction ·
HTML/CSS/JavaScript per la presentazione

