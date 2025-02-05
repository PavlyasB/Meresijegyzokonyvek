# Jegyzőkönyv - Távközlési technikus vizsgafeladat

**Vizsgázó neve:** [Pavlyás Bence]  
**Vizsgaidőpont:** [2025.02.03]  
**Feladat:** DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása  
**Időtartam:** 120 perc

---

## 1. Eszközök ellenőrzése
- **Antenna:** ISKRA P-20 Logper
- **Fejállomás:** LEMCO SCL-824CT
- **Set-top box:** MAG IPTV
- **Mérőműszer:** METEK HDD digitális TV jelmérő
- **Hálózati eszközök:** [Switch HP Procurve 2312 J4817A /ASUS RT-AX58U]

---

## 2. Antenna beállítása
- **Antenna típusa:** Iskra P-20 Logper
- **Mérési eszközök:** Iránytű, dőlésszögmérő, METEK HDD mérőműszer
- **Jelerősség:** 52 dBuV  
- **Irány:** Dél-nyugat [233°]  
- **Polarizáció:** Horizontális

---

## 3. Kábelezés és fejállomás beállítása
- **Antenna és fejállomás összekapcsolása:** Koaxiális kábel, jelosztó
- **Fejállomás beállításai:** DVB-T multiplexek hozzárendelése

---

## 4. IPTV stream beállítása
- **IPTV Set-top box beállítások:** Multicast IP címek : 239.1.1.1 - 239.1.1.40
- **IPTV stream stabilitásának ellenőrzése:** [Eredmény]

---

## 5. Jelszintmérés
- **Antenna mérések:**  
  - Jelszint: [dBμV]
  - Jelminőség: [SNR - dB]
- **Fejállomás után mérések:**  
  - IPTV stream: [Stabilitás, csomagvesztés]

---

## 6. Hálózati tesztek
- **iPerf3:** [Sávszélesség eredmények]
- **Wireshark:** [Csomagfigyelés]

---

## 7. Összegzés
A routerben az SSID-t átállítottam 'IPTV'-re a jelszót pedig '12345678'-ra.
Az admin bejelentkezést átállítottam hogy a felhasználónév legyen 'admin' a jelszó '12345678'.
A suili hálózata 100Mbps így a routernek a le és feltöltése 93Mbps.
|Router Porjati                  | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| LAN1                                | LEMCO CONTROL| 1Gbps        |
| LAN2                                | -           | -             |
| LAN3                                | LEMCO IP STREAM | 1Gbps     |
| LAN4                                | Set-Top-Box  | 100Mbps      |



**Aláírás:** Pavlyás Bence  
**Dátum:** [2025.02.03]
