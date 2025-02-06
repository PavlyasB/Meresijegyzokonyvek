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

---

## 5. Lemco Portok Beállítása:
- **Bemenet 1:** Multiplex B, csatorna 35  
- **Bemenet 2:** Miskolci Városi TV, csatorna 41  
- **Bemenet 3:** Multiplex A, csatorna 45  
- **Bemenet 4:** Multiplex E, csatorna 48  
<details>

  <summary>Kép megtekintése</summary>

  ![Portok](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/input1-3.png)     
  
  ![Portok](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/input4.png) 

</details>

## 6. Lemco IP Beállítások:
- **IP cím:** 192.168.1.200  
- **Bejelentkezés:** Felhasználó: admin / Jelszó: 12345  
- **IPTV Stream Cím:** 239.1.1.1-39  

## 7. Router Beállítások:
- **Router elérés:** 192.168.50.1 -> 192.168.1.1  
- **Router Bejelentkezés:** Felhasználó: admin / Jelszó: admin12345678  
- **SSID beállítás:** PSSWRD-IPTV, Jelszó: 12345678  
- **LAN Proxy Beállítás:** 8888  
- 
|Router Portjai                       |        | Sebesség |
| ----------------------------------- | ----------- | ------------- |
| LAN1                                | LEMCO CONTROL| 1Gbps        |
| LAN2                                | -           | -             |
| LAN3                                | LEMCO IP STREAM | 1Gbps     |
| LAN4                                | Set-Top-Box  | 100Mbps      |

## 8. A portok a tv adásokra átlettek állítva 
<details>

  <summary>Kép megtekintése</summary>

  ![tsout](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/tsout.png)       

</details>


## 9. Tesztelések Eredményei képekkel:
<details>

  <summary>Kép megtekintése</summary>

  ![teszt1](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/VLC.png)      
  
  ![teszt2](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/vlc2.png)   

    ![teszt3](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/2.PNG)       
  
  ![teszt4](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/3.PNG)      

    ![teszt5](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/4.PNG)     
  
  ![teszt6](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/IPTV/K%C3%A9pek/fdgfgdh.png)   

</details>




**Aláírás:** Pavlyás Bence  
**Dátum:** [2025.02.03]
