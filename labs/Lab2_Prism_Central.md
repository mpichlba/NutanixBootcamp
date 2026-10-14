# Lab 2 – Prism Central

**Prism Central Walkthrough**

> Hier gehen wir einige wesentliche Elemente aus dem Prism Central durch.

Quelle: <https://stephopper.com/published/guide_1777396177614>

[← Zurück zur Übersicht](../README.md)

### Schritt 1

Gehe auf "Dashboard"

![Schritt 1: Gehe auf "Dashboard"](images/Lab2_Prism_Central/step_01.png)

### Schritt 2

Das Dashboard zeigt dir unterschiedliche Metriken - es kann angepasst werden: Schiebe eines der Kästchen mittels Drag & Drop an eine andere Stelle.

![Schritt 2: Das Dashboard zeigt dir unterschiedliche Metriken - es kann angepasst werden: Schiebe eines der Kästchen mittels Drag & Drop an eine andere Stelle.](images/Lab2_Prism_Central/step_02.png)

### Schritt 3

Gehe zu VMs – hier werden alle VMs angezeigt die auf allen Clustern bereitgestellt sind. Du kannst die Ansicht auf verschiedene Metriken oder Einstellungen gruppieren oder filtern.

![Schritt 3: Gehe zu VMs – hier werden alle VMs angezeigt die auf allen Clustern bereitgestellt sind. Du kannst die Ansicht auf verschiedene Metriken oder Einstellungen gruppieren oder filtern.](images/Lab2_Prism_Central/step_03.png)

### Schritt 4

Wähle nun eine VM aus zb "Nutanix_Move"

![Schritt 4: Wähle nun eine VM aus zb "Nutanix_Move"](images/Lab2_Prism_Central/step_04.png)

### Schritt 5

In der VM Detail Ansicht werden sämtliche Details der VMs angezeigt.

![Schritt 5: In der VM Detail Ansicht werden sämtliche Details der VMs angezeigt.](images/Lab2_Prism_Central/step_05.png)

### Schritt 6

unter images können Images upgeloaded werden wie zb ISO oder Disk Images

![Schritt 6: unter images können Images upgeloaded werden wie zb ISO oder Disk Images](images/Lab2_Prism_Central/step_06.png)

### Schritt 7

Storage Containers sind die logische Abbildung des AOS Storages im SelfService und NutanixManagementShare sind interne Container die Nutanix u.a. für das Image Service nutzt.

![Schritt 7: Storage Containers sind die logische Abbildung des AOS Storages im SelfService und NutanixManagementShare sind interne Container die Nutanix u.a. für das Image Service nutzt.](images/Lab2_Prism_Central/step_07.png)

### Schritt 8

Virtual Switches bzw. ein Virtual Switch ist ein logischer verteilter Switch der sich über den ganzen Cluster streckt. Es gibt auch die Möglichkeit über mehrere Cluster einen logischen Switch zu bauen.

![Schritt 8: Virtual Switches bzw. ein Virtual Switch ist ein logischer verteilter Switch der sich über den ganzen Cluster streckt. Es gibt auch die Möglichkeit über mehrere Cluster einen logischen Switch zu bauen.](images/Lab2_Prism_Central/step_08.png)

### Schritt 9

Subnet sind die logischen Netze (VLANs) wo die virtuellen Netzwerkkarten der VMs angebunden werden. Es gibt unmanaged Subnets (entspricht einer VM Port Group bei vSphere) oder Managed Subnet - diese ermöglichen ein internes IPAM zu nutzen.

![Schritt 9: Subnet sind die logischen Netze (VLANs) wo die virtuellen Netzwerkkarten der VMs angebunden werden. Es gibt unmanaged Subnets (entspricht einer VM Port Group bei vSphere) oder Managed Subnet - diese ermöglichen ein internes IPAM zu nutzen.](images/Lab2_Prism_Central/step_09.png)

### Schritt 10

Das Security Dashboard zeigt wo bei den Nutanix Clustern noch potentielle Sicherheitslücken geschlossen werden müssen. Diese können teilweise angepasst werden an die eigenen Security Anforderungen.

![Schritt 10: Das Security Dashboard zeigt wo bei den Nutanix Clustern noch potentielle Sicherheitslücken geschlossen werden müssen. Diese können teilweise angepasst werden an die eigenen Security Anforderungen.](images/Lab2_Prism_Central/step_10.png)

### Schritt 11

Eine der Kernfunktionen bei Nutanix ist die Möglichkeit virtuelle Maschinen auf andere Cluster zu replizieren. Dies geschieht mit den sog. "Protection Policies". Dabei werden asynchrone, semisynchrone oder synchrone Replikationen unterstützt.

![Schritt 11: Eine der Kernfunktionen bei Nutanix ist die Möglichkeit virtuelle Maschinen auf andere Cluster zu replizieren. Dies geschieht mit den sog. "Protection Policies". Dabei werden asynchrone, semisynchrone oder synchrone Replikationen unterstützt.](images/Lab2_Prism_Central/step_11.png)

### Schritt 12

In den "Tasks" kann man die laufenden und die bereits durchgeführten Aktionen einsehen.

![Schritt 12: In den "Tasks" kann man die laufenden und die bereits durchgeführten Aktionen einsehen.](images/Lab2_Prism_Central/step_12.png)

### Schritt 13

Unter "Administration" -> "IAM" kann der Zugriff zu den einzelnen Ressourcen im Nutanix Cluster gesteuert werden.

![Schritt 13: Unter "Administration" -> "IAM" kann der Zugriff zu den einzelnen Ressourcen im Nutanix Cluster gesteuert werden.](images/Lab2_Prism_Central/step_13.png)

---

## Optionale Schritte

### Schritt 14

Erkunde weitere Elemente im Prism Central - Bei Unklarheiten wende dich an den Vortragenden
