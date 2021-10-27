# Client-side device caching

<img src="../../images/client-side.png"/>



Device caching is een tweede vorm van client-side caching, naast [browser caching](./browser.md). Device caching maakt het mogelijk om data lokaal op te slaan, op het device van de eindgebruiker. Aangezien Digipolis geen native applicaties voor Windows of OSX bouwt, focust dit document zich op **mobile** devices. Wanneer en hoe kan je cachen op een Android of iOS device?

Client-side device caching is interessant wanneer

* de te cachen data **uniek** is voor de eindgebruiker.
* data ook **offline** geraadpleegd moet kunnen worden.
* de te cachen data zeer weinig veranderd.

Bijvoorbeeld userprofile data, of chat sessies lenen zich goed tot device caching.

## Afwegingen

Zowel Android als iOS bieden verschillende opties aan om data al dan niet tijdelijk te persisteren.
De juiste keuze maken kan op basis van volgende factoren:

* Privacy
* APK Size
* Snelheid
* Complexiteit (kost)
* Resource gebruik (memory etc.)
* Schema (SQL vs. NoSQL)

## Android

### Text-file databases

* Room (SDK wrapper over SQLite)
* SQLDelite (SDK wrapper over SQLite)
* SQLite
* Realm (NoSQL)

### Shared Preferences

### Internal storage

## iOS

### NSCache

### URLCache

### Core Data

### File System

### 