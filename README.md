# Audio_Guide_for_Visually_Impaired_Kayakers
Audio Guide Leveraging Precise Location Technology<br>

- Centimeter-level positioning is achieved using **RTK GPS** technology. A local RTK correction base transmits RTCM data via **LoRa 868MHz**, avoiding the limitations of the **Centipede network**. Two LC29H-EA modules are used in both the base and rover units.  
- **ESP-WROOM32** handles data acquisition, while audio commands (short beeps) for **Bluetooth** headphones are stored in an AT25SF041 **flash**.
