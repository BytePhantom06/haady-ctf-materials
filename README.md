# Haady CTF Materials

Haady platformasi uchun CTF modullari fayllari. Har bir modul uchun alohida papka.

## Modullar

| Modul | Fayl(lar) | Mavzu |
|---|---|---|
| **3.9.1** | `backup.sh` | Linux privilege escalation (cronjob) |
| **6.4.3** | `pcaparchive.tar.gz` | 7 ta pcap arxivi |
| **6.4.4** | `01-office-browsing.pcap` | Packet count & avg length |
| **6.5.1** | `02-lan-health-check.pcap` | Pcap deep-dive (FTP, JPEG flag) |
| **6.5.2** | `03-dns-burst.pcap` | ARP / ICMP / DNS |
| **6.6.1** | `04-tls-connects.pcap` | Link layer + MAC |
| **6.6.2** | `05-firmware-download.pcap` | ICMP ping / unreachable |
| **6.6.3** | `06-file-server-chatter.pcap` | DHCP DORA |
| **16.3.2** | `linux_base64` | Base64 decode |
| **16.3.3** | `final-encoding-exercise` | base64 → tar → hex zanjiri |
| **16.6.5** | `secret-message`, `decrypt-me.gpg`, `haady-lab.ovpn` | GPG symmetric + OpenVPN |
| **16.7.2** | `Melaine-public.asc`, `Melaine-private.asc`, `flag.gpg` | GPG asymmetric |
| **16.7.6** | `http_basic_auth.pcap`, `http_basic_auth.key.txt` | TLS keylog decrypt |

## Fayllardan foydalanish

Har bir fayl o'z CTF moduliga tegishli. Masalan, 3.9.1 moduli uchun raw URL:

```
https://raw.githubusercontent.com/BytePhantom06/haady-ctf-materials/main/3.9.1/backup.sh
```
