# Keys Tutor

Web-App (PWA, iPad-optimiert), mit der Anfänger Akkorde für Lobpreislieder lernen – mit Fokus auf flüssige Akkordwechsel (Voice Leading).

Live: https://olivergentina.github.io/keys-tutor/

## Prototypen

- **[Kamera-Test](kamera-test.html)** – AR-Overlay im Kamerabild: Zieltasten mit Fingernummern, Handerkennung per MediaPipe Hand Landmarker, Hinweis bei falscher Taste.
  - Kamera starten (oder Video der Hände laden), Tastenbereich einstellen, vier Ecken der Tastatur antippen, Akkordfolge eingeben (z. B. `G D Em C`, deutsche Namen wie H, Fis, Es gehen auch).
  - Braucht Internet (MediaPipe von cdn.jsdelivr.net, Modell von storage.googleapis.com).
  - Erkennt, über welcher Taste ein Finger liegt, nicht den Tastenanschlag.
- **[Papier-Klaviatur](papier-klaviatur.pdf)** – A4 quer, C4 bis G5 in Originalgröße, zum Testen ohne Keyboard. In 100 % drucken; in der App linke Taste C4 und 12 weiße Tasten einstellen.
