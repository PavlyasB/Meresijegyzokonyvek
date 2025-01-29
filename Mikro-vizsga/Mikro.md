# Jegyzőkönyv  
**Távközlési Technikus Vizsgafeladat**  
**Feladat neve**: Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése  
**Időtartam**: 2 óra  
**Helyszín**: [Miskolc Kandó V3-Labor]  
**Dátum**: [2025.01.29]

---

## 1. Előkészítés és tervezés

### 1.1 Eszközök gyári beállításainak visszaállítása (Factory Reset)

- **Mikrotik LHG18 LTE antenna**:
  - Az antenna tápellátását eltávolítottam.
  - Nyomva tartottam a reset gombot, majd visszakapcsoltam a tápellátást.
  - Az LED villogni kezdett, majd elengedtem a reset gombot.
  - Az eszköz gyári beállításokra állt vissza.

- **Mikrotik nRay 60GHz antennák**:
  - A reset folyamatot elvégeztem mindkét eszközön (192.168.88.2 és 192.168.88.3).
  - Mindkét antenna gyári beállításra került vissza.

- **SOHO router**:
  - Az eszközt áramtalanítottam, majd nyomva tartottam a reset gombot.
  - A gyári beállítások visszaálltak.

### 1.2 Hálózati topológia tervezése

A hálózati diagramot a **Draw.io** segítségével készítettem el, amely tartalmazza az összes eszközt és azok kapcsolatait:

- Mikrotik LHG18 LTE: 192.168.88.1
- Mikrotik nRay 60GHz Master: 192.168.88.2
- Mikrotik nRay 60GHz Slave: 192.168.88.3
- Router (AP mód): 192.168.88.4
- Switch (ha szükséges): 192.168.88.254
- Kliens laptop: 192.168.88.100-250 (DHCP-ből)

A diagramot az alábbiakban csatoltam. Az IP címek megfelelő kiosztásával és az alhálózati maszk 255.255.255.0 beállításával biztosítottam a hálózat zökkenőmentes működését.

---

## 2. Eszközök telepítése és konfigurálása

### 2.1 Mikrotik LHG18 LTE antenna beállítása

- A laptopot az Mikrotik LHG18 LTE-hez Ethernet kábellel csatlakoztattam.
- Beállítottam a laptop IP-címét: 192.168.188.2
- A böngészőben elértem a konfigurációs felületet: **http://192.168.188.1**.
- Az LTE kapcsolatot a szolgáltató által megadott APN beállításokkal konfiguráltam.
- Beállítottam a DHCP szervert az IP-kiosztás számára: 192.168.88.100-250.
- Mentettem a beállításokat, és ellenőriztem az állapotot.
- Végeztem ping tesztet a külső szerverhez (8.8.8.8), és mértem a késleltetést.

**Jelerősség**: Mikrotik LHG18 LTE 
- RSRP: [-81 dBm]  
- RSRQ: [-10.0 dB]  
- SINR: [18 dB]  
- RSSI: [-54 dBm]

---

### 2.2 Mikrotik nRay 60GHz antennapár beállítása

- **Master antenna (192.168.88.2)**:
  - Az eszközt Ethernet kábellel csatlakoztattam a laptophoz.
  - A böngészőben elértem: **http://192.168.88.2**, és beléptem admin jelszóval.
  - Az eszközt “Master” módban konfiguráltam.

- **Slave antenna (192.168.88.3)**:
  - A Slave eszközt szintén Ethernet kábellel csatlakoztattam.
  - Az eszközt “Slave” módban konfiguráltam, és csatlakoztattam a Master antennához.
  - Ellenőriztem a jelminőséget a **WIRELESS 60G STATUS** oldalon.

**Képernyőképek**: (-)

---

### 2.3 SOHO router beállítása AP módban

- A routert Ethernet kábellel csatlakoztattam a laptophoz.
- Az IP-cím megtalálásához a **arp -a** parancsot használtam, majd a böngészőben elértem a routert.
- Az SSID-t **GazdaXX**-re állítottam, a jelszó: **G1234567**.
- A router AP módba került, és a megfelelő IP-t beállítottam a 192.168.88.xxx tartományban.

---

## 3. Hálózati tesztelés és hibakeresés

### 3.1 Ping teszt

A hálózaton lévő eszközöket pingeltem az alábbi IP-címekkel:

- ping 192.168.88.1
- ping 192.168.88.2
- ping 192.168.88.3
- ping 192.168.88.4

**Eredmények**:
- Minden eszköznél sikeres válaszok érkeztek, a válaszidők [ms értékek].

### 3.2 Sávszélesség mérése (iperf használata)

Az **iperf3** szoftvert telepítettem a laptopokra és a következő teszteket végeztem:

- Az egyik laptop szerverként futott: **iperf3 -s**
- A másik laptop kliensként futott: **iperf3 -c 192.168.88.xxx**

**Eredmények**:
- A sávszélesség mért értékek: []
- Az internet elérést teszteltem, és a **speedtest** alkalmazással is mértem.

---

## 4. Dokumentáció és értékelés

- A hálózati forgalom monitorozását és a hibakeresést az iperf segítségével végeztem.
- A ping és traceroute teszteket elvégeztem, hogy ellenőrizzem a kapcsolatokat.
- A hibák elhárítása során az **ipconfig** és **ipconfig /renew** parancsokat használtam, ha problémák adódtak a DHCP szerverrel.

**Prezentáció**:  
A projekt során bemutattam az eszközök telepítését és konfigurálását, valamint a mérések eredményeit.
---

**Aláírás**:  
[Pavlyás Bence]  
**Vezető neve**: [Név]  
**Vizsgahelyszín**: [Helyszín]
