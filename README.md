# Composer playground

- Je krijgt een bestand project met een `composer.json` file.
- Hiervoor ga je eerst de dependencies installeren met composer.
- Daarna laadt je de `autoload.php` (de autoloader) in uit de `vendor` map en ga je de ingeladen packages in je code gebruiken.

---

## Setup
1. Fork deze repository
2. Clone JOUW repository naar je computer
3. Open de map in je favoriete editor (probeer PHPStorm eens, dat geeft je veel hulp!)
4. Ga in een terminal venster naar de nieuwe map
5. Installeer de dependencies met: `composer install`

## Opdracht 

- Er zijn twee PHP bestanden.  
- In het PHP bestand: `create_qrcode.php` maak je een QR Code (je gebruik hiervoor het geïnstalleerde package: `codeitnowin/barcode`) 
- De QR Code sla je op als `qrcode.png`
- Als dat is gelukt ga je in `read_qrcode.php` de QR-Code decoderen (met de package: `khanamiryan/qrcode-detector-decoder`)
- De tekst uit de (gedecodeerde) QR Code zet je op het scherm.

**Het gaat hierbij om:**

- Het gebruik van `composer`
- Inladen van de autoloader van Composer.
- Lezen van documentatie en uitproberen code voorbeelden.
- De code werkend proberen te maken.
- Werken met OOP code, classes, namespaces etc. etc!


## Aan de slag

Nu ben je klaar om de opdracht te maken:

* Open `create_qrcode.php` en lees de comments en doe de opdrachten.
* Als `create_qrcode.php` werkend hebt en de QR-Code hebt gemaakt, ga je verder met `read_qrcode.php`.

*Veel succes!*

---

### Links naar de gebruikte packages en documentatie:

Genereren QR Codes: 
- [CodeItNow Barcode & QrCode Generator](https://github.com/codeitnowin/barcode-generator)  
Composer package: `codeitnowin/barcode`

Lezen / decoderen QR Codes:  
- [QR code decoder / reader for PHP](https://github.com/khanamiryan/php-qrcode-detector-decoder/)  
Composer package: `khanamiryan/qrcode-detector-decoder`

---

Voorbeeld QR Code:

![Voorbeeld](voorbeeld_qrcode.png)


 




