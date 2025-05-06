# PRA (Plan de Reprise d’Activité)

## **Plan d’adressage IP**

| Périphérique / Interface | IP Address | Subnet |
| --- | --- | --- |
| PC1 | 192.168.1.10 | 255.255.255.0 |
| SW1 | Pas d'IP (non géré) |  |
| R1 (LAN vers SW1) - G0/0 | 192.168.1.1 | 255.255.255.0 |
| R1 (WAN principal) - S0/0/0 | 10.0.0.1 | 255.255.255.252 |
| R1 (WAN secours) - S0/0/1 | 10.0.0.5 | 255.255.255.252 |
| R2 (WAN principal) - S0/0/0 | 10.0.0.2 | 255.255.255.252 |
| R2 (WAN secours) - S0/0/1 | 10.0.0.6 | 255.255.255.252 |
| R2 (LAN vers SW2) - G0/0 | 192.168.2.1 | 255.255.255.0 |
| PC2 | 192.168.2.10 | 255.255.255.0 |

### pc1

```
IP: 192.168.1.10
Mask: 255.255.255.0
Gateway: 192.168.1.1
```

### pc1

```
IP: 192.168.2.10
Mask: 255.255.255.0
Gateway: 192.168.2.1
```

### R1

[conftr1_pra.txt](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/conftr1_pra.txt)

### R2

[conftr2_pra.txt](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/conftr2_pra.txt)

### SW1

[conftsw1_pra.txt](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/conftsw1_pra.txt)

### SW2

[conftsw2_pra.txt](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/conftsw2_pra.txt)

## Ping v1

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image.png)

<aside>
💡

je peux ping pc 2 depuis pc 1

</aside>

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%201.png)

<aside>
💡

je peux ping pc 1 depuis pc 2

</aside>

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%202.png)

<aside>
💡

avec cette configuration présente

</aside>

## Ping v2

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%203.png)

<aside>
💡

je peux ping pc 2 depuis pc 1 avec le câble en moins car le second câble DCE à pris le relais

</aside>

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%204.png)

<aside>
💡

je peux ping pc 1 depuis pc 2 avec le câble en moins car le second câble DCE à pris le relais

</aside>

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%205.png)

# Annexes

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%206.png)

![image.png](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/image%207.png)

[PRA.pkt](PRA%20(Plan%20de%20Reprise%20d%E2%80%99Activite%CC%81)%201eb252007eb480af953ae5bc4aed5532/PRA.pkt)