# SIS252-Lab-5-Implementando-CIDR
Estudiante: Avendaño Retamozo Juan Antonio
## Requerimientos

| Red  | Hosts |
|------|------|
| LAN2 | 888  |
| LAN1 | 254  |
| **Total** | **1142** |

| Cálculo | Resultado |
|--------|----------|
| Capacidad requerida | 2^11 - 2 |
| Hosts disponibles  | 2046 |

---

## Red Padre -> Superred

| Concepto | Valor |
|----------|------|
| Red inicial | 208.68.225.0/24 |
| Nueva máscara | /21 |
| Máscara decimal | 255.255.248.0 |
| Superred | 208.68.224.0/21 |

---

## LAN2

| Parámetro | Valor |
|----------|------|
| Hosts requeridos | 888 |
| Prefijo | /22 |
| Máscara | 255.255.252.0 |
| Red | 208.68.224.0/22 |

### Rango de Direcciones

| Tipo | Dirección |
|------|----------|
| Primera IP | 208.68.224.1 |
| Última IP | 208.68.227.254 |

### Direcciones Reservadas

| Uso | Dirección |
|-----|----------|
| Rango reservado | 208.68.224.1 - 208.68.224.10 |
| Gateway | 208.68.227.254 |
| DHCP | 208.68.224.3 |
| Home Gateway | 208.68.224.4 |

---

## LAN1

| Parámetro | Valor |
|----------|------|
| Hosts requeridos | 254 |
| Prefijo | /24 |
| Máscara | 255.255.255.0 |
| Red | 208.68.228.0/24 |

### Subredes posibles

| Subred |
|--------|
| 208.68.228.0/24 |
| 208.68.229.0/24 |
| 208.68.230.0/24 |
| 208.68.231.0/24 |

### Rango de Direcciones

| Tipo | Dirección |
|------|----------|
| Primera IP | 208.68.228.1 |
| Última IP | 208.68.228.254 |

### Direcciones Reservadas

| Uso | Dirección |
|-----|----------|
| Rango reservado | 208.68.228.1 - 208.68.228.5 |
| Gateway | 208.68.228.254 |
| DHCP | 208.68.228.3 |

---

## Subred Inalámbrica

| Parámetro | Valor |
|----------|------|
| Red | 172.18.15.0/28 |
| Máscara | 255.255.255.240 |

### Rango de Direcciones

| Tipo | Dirección |
|------|----------|
| Primera IP | 172.18.15.1 |
| Última IP | 172.18.15.14 |
| Broadcast | 172.18.15.15 |
