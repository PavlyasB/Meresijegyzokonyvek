# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Pavlyás Bence  
**A mérés tárgya:** Frekvencia vs. moduláció mérés


**A mérés száma:** 4. mérés  
**A mérés dátuma:** 2024. 11. 5  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 Labor 

---

# Mérési Jegyzőkönyv

## 1. Mérés Célja
A mérés célja a **Johansson 8202 DVB-T modulátor** működésének megismerése, konfigurációjának tesztelése, valamint a METEK HD spektrum- és jelszintanalizátor használatával a modulátor által generált jel paramétereinek mérése. A mért paraméterek: **jelszint**, **bitsebesség**, **MER (Modulation Error Rate)**.

---

## 2. Használt Eszközök

| Eszköz                     | Típus                       | Funkció                                           |
|----------------------------|-----------------------------|---------------------------------------------------|
| Johansson 8202             | DVB-T modulátor            | Bitsebesség és jelminőség vizsgálata              |
| RF kábel                   | Koaxiális kábel            | Modulátorok és spektrumanalizátor összekötése     |
| Metek HDD                  | Spektrum/jelszint analizátor| Frekvencia, moduláció, sávszélesség, jelszint, MER és bitsebesség mérése |

---

## 3. Beállítások
- **Frekvencia**: 594 MHz  
- **Sávszélesség**: 8 MHz  
- **Modulációs típusok tesztelése**:  
  - QPSK  
  - 16QAM  
  - 64QAM  

---

## 4. Mérési Eredmények
Az alábbi táblázatban összefoglaljuk a mérések eredményeit különböző modulációs beállítások mellett.

| **Moduláció** | **Jelszint [dBm]** | **Bitsebesség [Mbps]** | **MER [dB]** |
|---------------|---------------------|------------------------|--------------|
| QPSK          | -12.5 dBm          | 3.3 - 4.9 Mbps        | 39.9 dB      |
| 16QAM         | -12.4 dBm          | 6.2 - 9.6 Mbps       | 35.8 dB      |
| 64QAM         | -14.2 dBm          | 13.7 - 14.6 Mbps      | 40.0 dB      |

---

## 5. Lépések
1. **Modulátor konfigurációja**:
   - A Johansson 8202 DVB-T modulátoron beállítottuk a kívánt frekvenciát (594 MHz) és a sávszélességet (8 MHz).  
   - A modulációs típusokat egyesével módosítottuk: QPSK, 16QAM, 64QAM.

2. **Jel vizsgálata METEK HD analizátorral**:
   - Az RF kábellel csatlakoztattuk a METEK HD spektrum/jelszint analizátort a modulátor kimenetéhez.  
   - Minden egyes modulációs típus esetén elvégeztük a jelszint, bitsebesség és MER mérést.  

---

## 6. Következtetések
- A mérés során megfigyelhető volt, hogy a moduláció típusának növelésével (QPSK → 64QAM) a bitsebesség jelentősen nőtt, miközben a **MER érték** változásai nem mutattak egyértelmű tendenciát.  
- A mérések a DVB-T elméleti követelményeinek megfelelő eredményeket adtak.

---

## 7. Megjegyzések
- A méréseket stabil környezeti feltételek mellett végeztük, zavarforrásoktól mentes helyiségben.  
- Az adatok alapján a különböző modulációs technikák közötti különbségek jól megfigyelhetőek voltak.

---


## 8. Diagramm
- Mérési Diagramm
<img src="https://github.com/PavlyasB/Meresijegyzokonyvek/blob/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/1"/>


---

## 9. Záró Összegzés


---

## 10. Mért Képek

<details>
<summary>Kattins a részletekért</summary>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/2.jpg"/>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/3.jpg"/>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/4.jpg"/>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/5.jpg"/>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/6.jpg"/>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/7.jpg"/>

<br>

<img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/4-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/8.jpg"/>

<br>



<br>

</details>

**Aláírás:** Pavlyás Bence

**Dátum:** 2024. 11. 5.
