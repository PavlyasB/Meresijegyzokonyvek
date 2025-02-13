# Jegyzőkönyv

## Téma: Amplitúdómoduláció vizsgálata a GRF-1300A trénerrel
**Név**: [Pavlyás Bence]  
**Dátum**: 2025. február 13.

---

## 1. Bevezetés  
Az amplitúdómoduláció (AM) vizsgálata egy fontos feladat a távközlési rendszerek és RF (rádiófrekvenciás) kommunikációs technológiák megértéséhez. A feladat célja az AM jel spektrumának elemzése, a jelszint, a sávszélesség és a modulációs mélység mérésével. A vizsgálatot a GRF-1300A RF és kommunikációs tréner segítségével végeztük el.

---

## 2. Használt eszközök  
- **GRF-1300A RF és kommunikációs tréner**

<details>

  <summary>Kép megtekintése</summary>

  <img src="https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/GRF-1300A.jpg.webp" width="300" >

</details>

- **GSP-730 Spektrumanalizátor**

<details>

  <summary>Kép megtekintése</summary>

  ![gsp](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/GSP-730.webp)

</details>

- **HMO-1002 Digitális tárolós oszcilloszkóp**


<details>

  <summary>Kép megtekintése</summary>

  ![hmo](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/HMO-1002.jfif)

</details>

---

## 3. Előkészítés  
A következő lépéseket végeztük el a mérés előtt:
1. **Csatlakozás**: A GRF-1300A RF tréner RF kimenetét csatlakoztattuk a GSP-730 spektrumanalizátor RF bemenetéhez. Az oszcilloszkópot az amplitúdómodulációs jel megfigyelésére használtuk.
2. **Kezdeti beállítások**: A GRF-1300A tréneren az alábbi beállításokat végeztük el:
   - Vivőfrekvencia: 880 MHz
   - Moduláló jel: 100 kHz szinuszjel
   - Modulációs mélység: 100%

---

## 4. Mérési feladatok és eredmények

### 4.1. Első mérés: 880 MHz vivőfrekvenciával, 100 kHz moduláló jellel és 100% modulációs mélységgel

- **Spektrumanalizátor mérés**:
   - A spektrum elemzése alapján a fő vivőfrekvencia 880 MHz volt. A spektrumban a két oldalcsúcs (frekvenciaváltás) és a vivőfrekvencia körüli jelszintek jól láthatóak voltak.
   - **Jelszint**: A spektrumanalizátor szerint a jelszint értéke -10 dBm volt a vivőfrekvencián.
   - **Sávszélesség**: A sávszélesség 200 kHz volt, amely megfelelt az elvárt értéknek 100% modulációs mélység esetén.
   - **Modulációs mélység**: Az 100%-os modulációs mélységet a spektrum és az oszcilloszkópon mért értékek is megerősítették.
   
- **Oszcilloszkópos mérés**:
   - A moduláló jel amplitúdóját az oszcilloszkópon mértük.
   - **Moduláló jel szintje (Vpp)**: A mért érték 1 Vpp volt.

<details>

  <summary>Kép megtekintése</summary>

  ![1](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/SCR00.bmp)

</details>

<details>

  <summary>Kép megtekintése</summary>

  ![2](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/TA01.png)

</details>
   
---

### 4.2. Második mérés: 900 MHz vivőfrekvenciával, 500 kHz moduláló jellel és 63% modulációs mélységgel

- **Spektrumanalizátor mérés**:
   - A vivőfrekvencia 900 MHz-ra módosult, és a moduláló jel 500 kHz lett.
   - **Jelszint**: A spektrumanalizátor mérése alapján a jelszint -8 dBm-ra emelkedett a vivőfrekvencián.
   - **Sávszélesség**: A sávszélesség 250 kHz-re nőtt, mivel a moduláló jel frekvenciája is nagyobb lett.
   - **Modulációs mélység**: A spektrum és oszcilloszkóp mérése alapján a modulációs mélység 63%-nak felelt meg.

- **Oszcilloszkópos mérés**:
   - A moduláló jel amplitúdóját ismét az oszcilloszkóppal mértük.
   - **Moduláló jel szintje (Vpp)**: A mért érték 1.2 Vpp volt.

<details>

  <summary>Kép megtekintése</summary>

  ![3](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/SCR01.bmp)

</details>


<details>

  <summary>Kép megtekintése</summary>

  ![4](https://raw.githubusercontent.com/PavlyasB/Meresijegyzokonyvek/refs/heads/main/AM-Mod/kepek/TA02.png)

</details>



---

## 5. Következtetés

A mérés során az amplitúdómoduláció (AM) jellemző paraméterei – jelszint, sávszélesség, modulációs mélység és moduláló jel szintje – sikeresen dokumentálásra kerültek. Az AM spektrumot a spektrumanalizátor segítségével elemeztük, és az oszcilloszkóppal mértük a moduláló jel amplitúdóját.

- Az első mérés 880 MHz vivőfrekvencián és 100 kHz moduláló jellel 100%-os modulációs mélységgel jellemzően stabil jelszintet és sávszélességet eredményezett.
- A második mérés 900 MHz vivőfrekvencián és 500 kHz moduláló jellel, 63%-os modulációs mélységgel mutatta a frekvencia és modulációs mélység hatását a jelszintre és sávszélességre.

A mérési eredmények alapján az AM jel vizsgálata és jellemzése sikeresen megvalósult.

---

**Aláírás**  
Név: [Pavlyás Bence]   
Dátum: 2025. február 13.