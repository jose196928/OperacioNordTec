# Operació Nord Tec
**José Luis Bernal Rodríguez**
**ASIX1A**

---

# Índex

- [Operació Nord Tec](#operació-nord-tec)
- [Índex](#índex)
- [1. Estat del projecte](#1-estat-del-projecte)
- [2. Arquitectura de xarxa](#2-arquitectura-de-xarxa)
- [3. Configuracions](#3-configuracions)
  - [3.1. Lab\_0373\_firewall](#31-lab_0373_firewall)
  - [3.2. UbuntuServer\_lab\_0373](#32-ubuntuserver_lab_0373)
  - [3.3. Ubuntu\_desk\_lab0226](#33-ubuntu_desk_lab0226)
- [4. Incidències i solucions](#4-incidències-i-solucions)
- [5. Decisions tècniques](#5-decisions-tècniques)
- [6. Reflexions tècniques](#6-reflexions-tècniques)

---

# 1. Estat del projecte

En aquest apartat es descriu l'estat actual del projecte, les tasques realitzades i les que encara queden pendents.

**Tasques completades:**
- Configuració dels paràmetres de xarxa de les tres màquines.
- Assignació de les adreces IP corresponents.
- Realització de proves de connectivitat entre les màquines.

**Tasques pendents:**
- [Afegir tasques pendents.]

# 2. Arquitectura de xarxa

L'arquitectura de la xarxa està composta per tres màquines:

- `Lab_0373_firewall`
- `UbuntuServer_lab_0373`
- `Ubuntu_desk_lab0226`

**Esquema de la infraestructura:**

[Afegir aquí un diagrama de la topologia de xarxa.]

# 3. Configuracions

S'han configurat els paràmetres de xarxa de les tres màquines amb les seves corresponents adreces IP. Posteriorment, s'han realitzat proves de connectivitat per verificar el funcionament correcte de la infraestructura.

## 3.1. Lab_0373_firewall

La màquina **`Lab_0373_firewall`** disposa de tres interfícies de xarxa:

- Una interfície per proporcionar accés a Internet.
- Dues interfícies per connectar-se a dues xarxes internes diferents.

**Configuració de les interfícies de xarxa:**

| Interfície | Funció | Adreça IP | Màscara |
|---|---|---|---|
| **`enp3s0`** | Connexió a l'exterior (Internet) | 10.0.0.1 | 255.255.255.0 |
| **`enp4s0`** | Connexió a la primera xarxa interna | 192.168.10.1 | 255.255.255.0 |
| **`enp5s0`** | Connexió a la segona xarxa interna | 192.168.20.1 | 255.255.255.0 |

**Detall de la configuració IP:**

## 3.2. UbuntuServer_lab_0373

[Descripció de la màquina i de la seva funció dins de la xarxa.]

**Configuració de les interfícies de xarxa:**

| Interfície | Adreça IP | Màscara | Passarel·la |
|---|---|---|---|
| **`enps1s0`**| 192.168.10.10 | 255.255.255.0 | Passarel·la | 

## 3.3. Ubuntu_desk_lab0226

[Descripció de la màquina i de la seva funció dins de la xarxa.]

**Configuració de les interfícies de xarxa:**

| Interfície | Adreça IP | Màscara | Passarel·la |
|---|---|---|---|
| **`enps1s0`** | 192.168.20.10 | 255.255.255.0 | Passarel·la |

# 4. Incidències i solucions

En aquest apartat es documenten els problemes que han aparegut durant el desenvolupament del projecte i les solucions aplicades.

**Incidència 1: Problema salida a internet Ubuntu Server y Ubuntu Desktop**

- **Problema:** [Descripció del problema.]
- **Causa:** [Origen de la incidència.]
- **Solució aplicada:** [Accions realitzades.]
- **Resultat:** [Resultat obtingut.]

# 5. Decisions tècniques

En aquest apartat es justifiquen les decisions preses durant la configuració i el desenvolupament de la infraestructura.

- **Decisió:** [Decisió tècnica adoptada.]
- **Motiu:** [Justificació.]
- **Avantatges:** [Beneficis de la decisió.]

# 6. Reflexions tècniques

En aquest apartat es recullen les conclusions i els aprenentatges obtinguts durant el desenvolupament del projecte.

- Quins coneixements tècnics s'han adquirit?
- Quines dificultats han aparegut?
- Com s'han resolt els problemes?
- Quines millores es podrien implementar en el futur?