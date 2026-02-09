
# 📖 Bibliai Óra (Bible Clock)

**"Minden percben egy üzenet – A pontos idő és az örök ige találkozása."**

A **Bibliai Óra** egy minimalista, de funkciókban gazdag Android alkalmazás, amely az aktuális időt (óra:perc) használja kulcsként a Szentírás felfedezéséhez. 

---

## ✨ Főbb Funkciók

### 🕒 Az Idő Üzenete (Főképernyő)

* **Dinamikus Ige-keresés:** Az applikáció minden percben megkeresi azokat az igéket, ahol a fejezet és a vers megegyezik a pontos idővel (pl. 12:05-kor a 12:5-ös versek jelennek meg).
* **Személyre szabott esztétika:** A háttérben saját fotók jelennek meg, melyekhez az UI intelligens kontrasztkezeléssel (scrim/shadow) igazítja a szöveget.
* **Widget támogatás:** Interaktív widget a kezdőképernyőre és a zárolt képernyőre, hogy egy pillantás alatt látható legyen a perc igéje.

### 📚 Biblia Olvasó & Böngésző

* **Teljes Biblia:** Károli Gáspár fordítása alapján böngészhető könyvek és fejezetek.
* **Haladási Napló:** Integrált SQLite (Room) adatbázis segítségével követheted, a Biblia hány százalékát olvastad már el.
* **Helyjelző:** Az app automatikusan emlékszik, melyik fejezetnél tartottál utoljára.

### 🔍 Keresés & Random Ige

* **Univerzális Kereső:** Keresés igehelyre vagy kulcsszavakra a teljes szövegben.
* **Random Generátor:** Egyetlen gombnyomásra véletlenszerűen sorsolt igék a nap bármely szakában.

### 💾 Személyes Interakciók (Adatbázis funkciók)

* **Kedvencek & Jegyzetek:** Épületes igék mentése saját megjegyzésekkel kiegészítve.
* **Imalista:** Saját imakérések és hálák vezetése, melyek összeköthetők kedvenc igékkel.
* **Keresési Előzmények:** Gyors visszatérés a korábban vizsgált témákhoz.

---

## 🛠 Technikai Részletek

* **Nyelv:** [Kotlin](https://kotlinlang.org/)
* **UI Architektúra:** XML (ConstraintLayout) a maximális rugalmasságért.
* **Adatbázis:** [Room Persistence Library](https://developer.android.com/training/data-storage/room) (SQLite alapokon).
* **Adatforrás:** Offline JSON alapú Biblia-adatbázis.
* **Dizájn:** Figma alapú prototípus, letisztult, "zen" hangulatú felület.

---

## 🎨 Dizájn Koncepció

Az alkalmazás a **Glassmorphism** és a modern sötét mód elemeit ötvözi. A hangsúly az olvashatóságon és a képi világon van.

> **[Link a Figma tervhez - Hamarosan!]**

---

## 🚀 Telepítés & Futtatás

1. Klónozd a tárolót:
```bash
git clone https://github.com/felhasznalonev/biblia-ora.git

```

2. Nyisd meg az **Android Studio**-ban.
3. Várd meg, amíg a Gradle szinkronizáció befejeződik.
4. Futtasd egy fizikai eszközön vagy emulátoron (API 26+ ajánlott).

---

## 📝 Készítette

* **Tóth Levente** - *Ötlet és Fejlesztés*
