# PCA (Principal Component Analysis)

| Appareil | Interface | Adresse IP | Masque | Passerelle |
| --- | --- | --- | --- | --- |
| PCA (PC client) | — | `192.168.1.10` | `255.255.255.0` | `192.168.1.1` |
| Routeur | G0/0 | `192.168.1.1` | `255.255.255.0` | — |
| Switch | VLAN 1 (optionnel) | `192.168.1.2` | `255.255.255.0` | `192.168.1.1` |

### Sur le **routeur** :

[conftr1_pca.txt](PCA%20(Principal%20Component%20Analysis)%201eb252007eb4803ea4dae3946fea61b7/conftr1_pca.txt)

### Sur le **switch**  :

[conftsw1_pca.txt](PCA%20(Principal%20Component%20Analysis)%201eb252007eb4803ea4dae3946fea61b7/conftsw1_pca.txt)

- IP Address : `192.168.1.10`
- Subnet Mask : `255.255.255.0`
- Default Gateway : `192.168.1.1`

```bash
ping 192.168.1.1

```

![image.png](PCA%20(Principal%20Component%20Analysis)%201eb252007eb4803ea4dae3946fea61b7/image.png)

![image.png](PCA%20(Principal%20Component%20Analysis)%201eb252007eb4803ea4dae3946fea61b7/image%201.png)