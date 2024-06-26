---
title: RISCV-Board und vom Betriebssystem unterstützte Matrix
---

{{% blocks/section color="white" type="row" %}}

## Mainstream-Betriebssysteme für die RISC-V-Hardwareanpassung (Mainstream-RISC-V-Entwicklungsboards)

| CPU      | Product number                      | Arch Linux | Debian/RevyOS | Fedora | FreeBSD | Gentoo | openAnolis | OpenBSD | openCloudOS | openEuler | openKylin | openSUSE | Ubuntu | Tina-Linux | Android 13 | Armbian | BuildRoot | OpenHarmony | FreeRTOS | RT-Thread | Zephyr | OpenWRT | ThreadX |
|----------|-------------------------------|------------|---------------|--------|---------|--------|------------|---------|-------------|-----------|-----------|----------|--------|------------|------------|---------|-----------|-------------|----------|-----------|--------|---------|---------|
| SG2042   | [Pioneer Box][Pioneer]         | N/A        | Gut          | Gut   | N/A     | N/A    | N/A        | N/A     | WIP         | Gut      | Gut      | N/A      | N/A    | N/A        | N/A        | N/A     | N/A       | WIP         | N/A      | N/A       | N/A    | N/A     | N/A     |
| CV1800B  | [Milk-V Duo (64M)][Duo]        | Basic      | Basic         | CFH    | N/A     | N/A    | N/A        | N/A     | N/A         | Basic     | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | Basic     | N/A         | Basic    | Basic     | N/A    | WIP     | N/A     |
| TH1520   | [LicheePi 4A][LPi4A]           | Gut       | Gut          | Gut   | N/A     | N/A    | N/A        | N/A     | N/A         | Gut      | Gut      | N/A      | WIP    | N/A        | N/A        | Good    | N/A       | WIP         | N/A      | N/A       | N/A    | Basic   | N/A     |
| JH7100   | [VisionFive][VF1]              | N/A        | N/A           | Gut   | N/A     | N/A    | N/A        | Basic   | N/A         | Gut      | Gut      | Basic    | Basic  | N/A        | N/A        | Basic   | Basic     | N/A         | N/A      | N/A       | N/A    | Basic   | N/A     |
| JH7110   | [VisionFive 2][VF2]            | Basic      | Gut          | N/A    | WIP     | Basic  | N/A        | Basic   | N/A         | Gut      | Gut      | Basic    | Basic  | N/A        | WIP        | Gut    | Basic     | WIP         | N/A      | Basic     | CFH    | Basic   | N/A     |
| K230     | [CanMV K230][K230]             | N/A        | Basic         | Basic  | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | Basic  | N/A        | N/A        | N/A     | N/A       | N/A         | N/A      | Basic     | N/A    | N/A     | N/A     |
| C906     | [LicheeRV/AWOL Nezha][C906]    | N/A        | Gut          | Gut   | WIP     | N/A    | N/A        | N/A     | N/A         | Gut      | N/A       | Basic    | Basic  | Basic      | N/A        | N/A     | N/A       | N/A         | N/A      | N/A       | N/A    | Basic   | N/A     |
| U740     | [HiFive Unmatched][Unmatched]  | N/A        | Basic         | Gut   | Basic   | N/A    | N/A        | Basic   | N/A         | Gut      | Gut      | Basic    | Basic  | N/A        | N/A        | CFH     | N/A       | WIP         | N/A      | N/A       | Basic  | Basic   | N/A     |
| SG2000   | [Milk-V Duo S][DuoS]           | N/A        | N/A           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | Basic     | N/A         | CFT      | N/A       | N/A    | N/A     | N/A     |
| JH7110   | [Milk-V Mars][Mars]            | N/A        | CFT           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | CFT       | N/A         | CFT      | N/A       | N/A    | N/A     | N/A     |
| FSL1030M | [Milk-V Vega][Vega]            | N/A        | N/A           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | CFH       | N/A         | N/A      | N/A       | N/A    | N/A     | N/A     |
| TH1520   | [Milk-V Meles][Meles]          | N/A        | CFT           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | N/A       | N/A         | N/A      | N/A       | N/A    | N/A     | N/A     |
| K210     | [Sipeed Maix-I][Maix]          | N/A        | N/A           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | N/A       | N/A         | CFT      | N/A       | N/A    | N/A     | N/A     |
| TH1520   | [Lichee Cluster 4A][Cluster4A] | N/A        | Gut          | Gut   | N/A     | N/A    | N/A        | N/A     | N/A         | Gut      | Gut      | N/A      | N/A    | N/A        | N/A        | Gut    | N/A       | N/A         | N/A      | N/A       | N/A    | Basic    | N/A     |
| TH1520   | [Lichee Console 4A][Console4A] | N/A        | CFT           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | N/A       | N/A         | N/A      | N/A       | N/A    | N/A     | N/A     |
| SG2002   | [LicheeRV Nano][LicheeRVNano]  | N/A        | N/A           | N/A    | N/A     | N/A    | N/A        | N/A     | N/A         | N/A       | N/A       | N/A      | N/A    | N/A        | N/A        | N/A     | CFT       | N/A         | CFT      | N/A       | N/A    | N/A     | N/A     |

#### Hinweise

* Gut: Unterstützt grafische Benutzeroberfläche
* Basic: Kann mit dem Laufen beginnen
* CFH (Hilferuf): Offizielle Informationen/Forumsinformationen deuten auf Unterstützung hin, wurden jedoch nicht durchgesehen.
* CFT (Aufruf zum Testen): Es gibt einen Spiegellink, es fehlt jedoch die Überprüfung des Hardwaregeräts.
* CFI (Anruf für weitere Informationen): Offizielle Informationen geben an, dass dies der Fall ist, es können jedoch keine tatsächlich verwendbaren Informationen wie Bilddateien gefunden werden.
* In Bearbeitung: Die offizielle Ankündigung lautet, dass das Betriebssystem bald Entwicklungsboards unterstützen wird, es wurden jedoch noch keine verfügbaren Images abgerufen.
* N/A: Es wurden keine Supportinformationen für das Entwicklungsboard von offiziellen oder anderen Kanälen erhalten.

[Pioneer]: https://github.com/ruyisdk/support-matrix/blob/main/Pioneer/README.md
[Duo]: https://github.com/ruyisdk/support-matrix/blob/main/Duo/README.md
[LPi4A]: https://github.com/ruyisdk/support-matrix/blob/main/LicheePi4A/README.md
[VF1]: https://github.com/ruyisdk/support-matrix/blob/main/VisionFive/README.md
[VF2]: https://github.com/ruyisdk/support-matrix/blob/main/VisionFive2/README.md
[K230]: https://github.com/ruyisdk/support-matrix/blob/main/K230/README.md
[C906]: https://github.com/ruyisdk/support-matrix/blob/main/D1_LicheeRV/README.md
[Unmatched]: https://github.com/ruyisdk/support-matrix/blob/main/Unmatched/README.md
[DuoS]: https://github.com/ruyisdk/support-matrix/blob/main/Duo_S/README.md
[Mars]: https://github.com/ruyisdk/support-matrix/blob/main/Mars/README.md
[Vega]: https://github.com/ruyisdk/support-matrix/blob/main/Vega/README.md
[Meles]: https://github.com/ruyisdk/support-matrix/blob/main/Meles/README.md
[Maix]: https://github.com/ruyisdk/support-matrix/blob/main/Maix-I_K210/README.md
[Cluster4A]: https://github.com/ruyisdk/support-matrix/blob/main/LicheeCluster4A/README.md
[Console4A]: https://github.com/ruyisdk/support-matrix/blob/main/LicheeConsole4A/README.md
[LicheeRVNano]: https://github.com/ruyisdk/support-matrix/blob/main/LicheeRV_Nano/README.md

{{% /blocks/section %}}
