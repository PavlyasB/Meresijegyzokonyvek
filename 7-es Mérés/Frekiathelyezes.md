# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Pavlyás Bence  
**A mérés tárgya:** Antennák teljesítményének és jelminőségének összehasonlítása  
**A mérés száma:** 7. mérés  
**A mérés dátuma:** 2024. 12. 12 

**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 Labor  

---

## 1. Mérés célja  
A mérés célja három különböző típusú antenna, az **Iskra P20**, az **ISKRA P2845** és az **IKUSI FLASHD C48** teljesítményének összehasonlítása, valamint a jelszint és jelminőség (MER - Modulation Error Ratio) vizsgálata három különböző frekvencián (522 MHz és 730 Mhz).

---

## 2. Alkalmazott mérőeszközök és készülékek  

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| Antenna                             | Philips     |    SDV5228    |
| Programozható antennaerősítő-szűrő  | Johansson   | 8202          |
| Antenna                             | Iskra       | P20, P2845    |
| Antenna                             | IKUSI       | FLASHD C48    |
| Spectrum Analizátor                 | Metek       | HDD           |

---

### 3. **Mérési helyszín és környezet**
- **Antenna magassága**: 2 m
- **Környezet jellemzői**: V3 labor
- **Adó távolsága**: 15 m

---

## 4. Antennák teljesítménye különböző frekvenciákon

| Frekvencia (MHz) | Antenna          | Jelszint (dBm) | MER (dB) | Bitsebesség (Mbps) |
| ---------------- | ---------------- | -------------- | -------- | ------------------ |
| **730 MHz**      | Iskra P20        | -61.8          | 24.6     | 8.2 – 8.6          |
|                  | ISKRA P2845      | -58.8          | 26.3     | 8.6 – 9.6          |
|                  | IKUSI FLASHD C48 | -58.5          | 27.0     | 8.4 – 9.2          |
| **522 MHz**      | Iskra P20        | -59.0          | 26.6     | 8.2 – 9.2          |
|                  | ISKRA P2845      | -52.8          | 33.2     | 8.2 – 10.0         |
|                  | IKUSI FLASHD C48 | -52.6          | 30.0     | 7.8 – 9.2          |


---

## 5. Értékelés

### Jelszint
Az **ISKRA P2845** antenna mutatta a legmagasabb jelszinteket minden frekvencián, különösen a 33. csatornán (570 MHz), ahol -52,8 dBm-es eredményt produkált. Az **IKUSI FLASHD C48** szintén magas jelszintet ért el, míg az **Iskra P20** antenna a leggyengébb jelszinteket mutatta, különösen a 706 MHz-es frekvencián (-64.8 dBm).

### Jelminőség (MER)
Az **ISKRA P2845** antenna kiemelkedett a modulációs hibaarány (MER) tekintetében is, a legmagasabb értéket a 33. csatornán érte el (33.2 dB). Az **IKUSI FLASHD C48** stabil jelminőséget biztosított minden frekvencián, míg az **Iskra P20** a 706 MHz-en jelentős jelminőség romlást mutatott (19.5 dB).

### Bitsebesség
A bitsebesség értékei az **ISKRA P2845** antennánál voltak a legjobbak, különösen a 570 MHz-es csatornán, ahol akár 10 Mbps is elérhető volt. Az **IKUSI FLASHD C48** antenna szintén magas bitsebességet biztosított a nagyobb frekvenciákon, míg az **Iskra P20** gyengébb teljesítményt mutatott a magasabb frekvenciákon.

---

## 6. Következtetés
Az **ISKRA P2845** antenna a legjobb teljesítményt nyújtotta mind a jelszint, mind a jelminőség és bitsebesség tekintetében, különösen a közepes frekvenciatartományban (570 MHz). Az **IKUSI FLASHD C48** stabil és megbízható választás, míg az **Iskra P20** csak alacsonyabb frekvenciákon javasolt használatra.

---

## 7. Javaslatok
Az **ISKRA P2845** antenna javasolt elsődleges használatra, mivel minden frekvencián magasabb jelszintet és jobb jelminőséget biztosított. Amennyiben költséghatékonyabb megoldás szükséges, az **IKUSI FLASHD C48** is megfelelő választás lehet. Az **Iskra P20** csak alacsonyabb frekvenciákon javasolt, ahol még kielégítő teljesítményt nyújt.

---

## 8. P-20 Képek:
<details>
    <summary>Kattins a részletekért</summary>

    **522hz Mért Képek:**
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/1.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/2.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/3.jpg"/>
---

    **730MHz Mért Képek**
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/4.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/5.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/6.jpg"/>
---



</details>

<br>

## 9. P-2845 Képek:
<details>

    <summary>Kattins a részletekért</summary>

    **522hz Mért Képek:**
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/7.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/8.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/9.jpg"/>
---

    **730MHz Mért Képek**
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/10.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/11.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/12.jpg"/>
---

  

</details>

<br>

## 10. FlashHD C-48 Képek:
<details>
    <summary>Kattins a részletekért</summary>

    **522Mhz Mért Képek:**
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/13.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/14.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/15.jpg"/>
---

    **730MHz Mért Képek**
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/16.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/17.jpg"/>
    <br>
    <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/7-es%20M%C3%A9r%C3%A9s/K%C3%A9pek/18.jpg"/>
---


</details>


<br>




**Aláírás:**  

**Dátum:** 
