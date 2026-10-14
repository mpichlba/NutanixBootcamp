<div align="center">

# 🚀 Nutanix Bootcamp

**Hands-on Labs rund um Nutanix AHV, Prism und die Migration von VMware mit Nutanix Move**

![Labs](https://img.shields.io/badge/Labs-7-0869B2?style=for-the-badge)
![Schritte](https://img.shields.io/badge/Schritte-58-024DA1?style=for-the-badge)
![Sprache](https://img.shields.io/badge/Sprache-Deutsch-6C757D?style=for-the-badge)
![Plattform](https://img.shields.io/badge/Plattform-Nutanix%20AHV-7855FA?style=for-the-badge)

</div>

---

## 🗺️ Ablauf

```mermaid
flowchart LR
    subgraph A["🔍 Kennenlernen"]
        L1["Lab 1<br/>Prism Element"] --> L2["Lab 2<br/>Prism Central"]
    end
    subgraph B["🖥️ VMs bereitstellen"]
        L3["Lab 3<br/>Windows VM"] --> L4["Lab 4<br/>Linux VM"]
    end
    subgraph C["🔄 Migration"]
        L5["Lab 5<br/>vCenter"] --> L6["Lab 6<br/>Move Setup"] --> L7["Lab 7<br/>Cutover"]
    end
    A --> B --> C
```

---

## 📚 Labs

| | Lab | Inhalt | Schritte |
|:-:|---|---|:-:|
| <img src="labs/images/Lab1_Prism_Element/step_02.png" width="180"> | **[Lab 1 – Prism Element erkunden](labs/Lab1_Prism_Element.md)** | Login am Cluster, Hardware-, Storage- und Netzwerk-Diagramme, Health-Übersicht | 7 |
| <img src="labs/images/Lab2_Prism_Central/step_02.png" width="180"> | **[Lab 2 – Prism Central](labs/Lab2_Prism_Central.md)** | Dashboard, VMs, Images, Storage Container, Netzwerke, Security, Protection Policies, IAM | 14 |
| <img src="labs/images/Lab3_Windows_VM/step_03.png" width="180"> | **[Lab 3 – Windows VM Bereitstellung](labs/Lab3_Windows_VM.md)** | Deployment aus einem Template mit Sysprep-Gastanpassung | 5 |
| <img src="labs/images/Lab4_Linux_VM/step_05.png" width="180"> | **[Lab 4 – Linux VM Bereitstellung](labs/Lab4_Linux_VM.md)** | RHEL 10 aus einem Template mit cloud-init, optional SSH-Login | 8 |
| <img src="labs/images/Lab5_vCenter/step_01.png" width="180"> | **[Lab 5 – vCenter erkunden](labs/Lab5_vCenter.md)** | Bestehende vSphere-Umgebung ansehen, eigene VMs und IP-Adressen notieren | 1 |
| <img src="labs/images/Lab6_Nutanix_Move_Setup/step_12.png" width="180"> | **[Lab 6 – Nutanix Move: Initiales Setup](labs/Lab6_Nutanix_Move_Setup.md)** | Migration Plan anlegen: Source/Target, VM-Auswahl, Netzwerk-Mapping, VM-Vorbereitung | 19 |
| <img src="labs/images/Lab7_Nutanix_Move_Cutover/step_01.png" width="180"> | **[Lab 7 – Nutanix Move: Cutover](labs/Lab7_Nutanix_Move_Cutover.md)** | Fortschritt der Replikation verfolgen, Cutover auslösen, Ergebnis in Prism Central prüfen | 4 |

---

## ✅ Bevor du startest

> [!NOTE]
> Zugangsdaten (Prism, vCenter, Nutanix Move sowie Benutzer/Passwort der VMs) und deine **zweistellige Bootcamp-Nummer** bekommst du vom Vortragenden.

> [!TIP]
> Arbeite die Labs der Reihe nach durch – Lab 6 und 7 bauen auf den VMs aus Lab 5 auf.

---

## 📁 Aufbau des Repositories

```text
NutanixBootcamp/
├── README.md              ← diese Übersicht
└── labs/
    ├── Lab1_Prism_Element.md
    ├── Lab2_Prism_Central.md
    ├── ...
    └── images/            ← Screenshots je Lab
```
