# Jegyzőkönyv - Távközlési technikus vizsgafeladat - DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása

**Vizsgázó neve:** [Pavlyás Bence]  
**Vizsgaidőpont:** [2025.02.03]  
**Feladat száma:** B tétel  
**Időtartam:** 120 perc

---

### 1. Előkészületek (10 perc)

Ellenőriztem az összes szükséges eszközt, és biztosítottam a megfelelő munkakörnyezetet. Az adótorony adatbázisából (fmdx.hu) sikeresen kiválasztottam az Miskolc, Avasi adótorony megfelelő multiplex frekvenciáit és adási paramétereit.

---

### 2. Antenna felszerelése és beállítása (30 perc)

Beltéri antennát választottam, és optimálisan elhelyeztem a V3 labor egyik megfelelő vételi pontján. Az antenna beállítása során iránytűt és dőlésszögmérőt használtam az adótorony irányába történő pontos állításhoz. A METEK HDD mérőműszer segítségével végeztem el a finomhangolást.

---

### 3. Kábelezés, mérési pontok kialakítása és jel bevezetése a fejállomásba (25 perc)

Koaxiális kábelt és jelező osztót használtam az antenna és a fejállomás összekapcsolásához. A jelet a megfelelő bemeneti pontokra osztottam el a fejállomásba, biztosítva, hogy minden fogható multiplex bekerüljön a rendszerbe. A jelet a villamos 3 laborba vezettem, hogy az IPTV hálózaton keresztül továbbítható legyen.

---

### 4. Fejállomás beállítása és IPTV stream konfigurálása (25 perc)

Minden bemenetre megfelelő DVB-T multiplexet rendeltem hozzá. A szabadon fogható DVB-T jelet feldolgoztam, és IP streamre konvertáltam. A multicast IP tartományt sikeresen konfiguráltam, és az IPTV Set-top-box (MAG IPTV) hálózati kapcsolatát is beállítottam. A csatornák megfelelő listázása és a csatornakeresés elindítása után a stream megfelelően működött.

---

### 5. Jelszintmérés és dokumentáció (30 perc)

Elvégeztem a szükséges méréseket és dokumentációkat:

- **Antenna mérések:**  
  - Spektrum analizátor képe  
  - Jelszintek: [Adott értékek]  
  - Jelminőség: [Adott értékek]  
  - Antenna pozíciók és szögek: [Megfelelő értékek]  
  - Polarizáció: [Megfelelő beállítás]  
  - Multiplex adatok: [Frekvencia, szimbólumráta, FEC]  
  - Időjárási körülmények: [Hőmérséklet, szélsebesség]

- **Fejállomás után mérések:**  
  - Multicast IP címek ellenőrzése: [Megfelelően konfigurálva]  
  - IPTV stream stabilitásának mérése: [Stabilitás megfelelő]  
  - Hálózati késleltetés és csomagvesztés vizsgálata: [Eredmények]  
  - Stream adatok rögzítése: [Rögzítve]  

A mérési eredményeket az alábbiak szerint rögzítettem a jegyzőkönyvben:

- **Jelerősség:** [dBμV]  
- **Jel-zaj viszony (SNR):** [dB]  
- **Bit Error Rate (BER):** [Adott értékek]  
- **Modulation Error Ratio (MER):** [dB]  
- **Csillapítás:** [dB]  
- **Lock állapot:** [ ] Igen [ ] Nem  
- **Hőmérséklet és időjárási körülmények:** [Adott értékek]  
- **Multiplex adatok és frekvenciák:** [Adott értékek]  

A rendszer megfelelő működése biztosított.

---

### 6. Eszköztelepítés és hálózati tesztek

A szükséges IPTV vizsgálati eszközöket telepítettem a **winget** csomagkezelő segítségével. Az alábbi eszközöket sikeresen telepítettem:

- VLC  
- Wireshark (TShark)  
- FFmpeg  
- iPerf3  

A hálózati teljesítmény és multicast forgalom tesztelése megtörtént, a megfelelő eszközökkel és parancsokkal (iperf3, ping, traceroute, Wireshark).

---

**Jegyzőkönyv elkészítése és aláírása**

A szükséges mérési adatokat és dokumentációkat megfelelően rögzítettem, és aláírtam a jegyzőkönyvet.

**Aláírás:** Pavlyás Bence
**Dátum:** [2025.02.03]
