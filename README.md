# Simulazione della seconda prova di Sistemi e reti (2013/14)

In preparazione all'esame di Stato, in classe abbiamo svolto la traccia della seconda prova di Sistemi e reti dell'anno scolastico 2013/14. Questa è la mia soluzione in **Cisco Packet Tracer**.

Scheda nel portfolio, con la topologia: <https://portfoliogigi.com/progetti/reti-cisco-packet-tracer/>

## Contenuto

| File | Descrizione |
|---|---|
| `Simulazione_Sistemi_2013-2014.pkt` | Progetto Cisco Packet Tracer |

- un **router** collegato a Internet (nuvola);
- due **firewall Cisco ASA 5506-X**;
- due **switch multilayer Cisco 3650**, uno al centro della rete;
- cinque **switch Cisco 2960**: quattro per i computer degli uffici e uno per i tre **server**;
- una **VLAN «uffici»** (VLAN 10) sullo switch multilayer, con indirizzo `10.0.0.1/22` e una porta in **trunk**.

## Come aprirlo

Serve **Cisco Packet Tracer**. Apri il file `.pkt` con *File → Open*.

## Limiti noti

Gran parte della configurazione (firewall, router, indirizzi dei server) non è salvata nel file: c'è soprattutto la progettazione della topologia.

---

Autore: Luigi Lena · [portfoliogigi.com](https://portfoliogigi.com)
