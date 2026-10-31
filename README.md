## 🔧 Penyebab & Perbaikan Error Gambar `GitHub stats`

Ikon gambar pecah (*broken image*) bertuliskan **`GitHub stats`** tersebut muncul **bukan karena kesalahan penulisan kode Markdown kamu**, melainkan karena:

1. **Server Publik `github-readme-stats.vercel.app` Sedang *Limit* / *Down*:** Layanan asli milik `anuraghazra` di alamat `https://github-readme-stats.vercel.app` sangat sering mengalami **503 Deployment Paused** atau **429 Too Many Requests** (kehabisan kuota API GitHub) karena digunakan oleh jutaan profil GitHub secara bersamaan. Saat server tersebut lambat merespons, proxy gambar GitHub (*Camo*) otomatis memutus koneksi dan menampilkan ikon gambar rusak.
2. **Domain Heroku Streak Stats Sudah Pindah:** URL lama `github-readme-streak-stats.herokuapp.com` sering mengalami *timeout* karena layanannya kini telah dipindahkan secara resmi ke `https://streak-stats.demolab.com`.

---

### ✅ Solusi Cepat (Pilih Salah Satu untuk Bagian `## 📊 GitHub Stats`)

#### **Opsi 1: Menggunakan Mirror Cepat `github-readme-stats-fast` (Tampilan Sama Persis)**
Ganti bagian `## 📊 GitHub Stats` di profil GitHub kamu dengan kode berikut:

```html
## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats-fast.vercel.app/api?username=RevanAnugrah&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats">
<img height="170" src="https://streak-stats.demolab.com/?user=RevanAnugrah&theme=tokyonight&hide_border=true" alt="GitHub streak">

</div>
```

#### **Opsi 2: Menggunakan `github-profile-summary-cards` (Paling Stabil & Anti-Limit)**
Jika sewaktu-waktu server Opsi 1 juga terkena antrean penuh, layanan `github-profile-summary-cards` jauh lebih stabil dan tetap mendukung tema `tokyonight`:

```html
## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=RevanAnugrah&theme=tokyonight" alt="GitHub stats">
<img height="170" src="https://streak-stats.demolab.com/?user=RevanAnugrah&theme=tokyonight&hide_border=true" alt="GitHub streak">

</div>
```

---

## 📋 Kode Lengkap `README.md` Profil GitHub (Sudah Diperbaiki & Siap Copy-Paste)

Salin seluruh blok kode di bawah ini dan tempelkan langsung ke file `README.md` pada repositori profil `RevanAnugrah/RevanAnugrah` kamu:

```html
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A1220,100:1F6FB2&height=200&section=header&text=Revan%20Anugrah%20Wibowo&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Aspiring%20Network%20Engineer&descSize=20&descAlignY=60" width="100%" alt="Header">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=1F6FB2&center=true&vCenter=true&width=680&lines=Halo!+I'm+Revan+%F0%9F%91%8B;TJKT+Student+%7C+SMKN+3+Kota+Tangerang;GNS3+%C2%B7+MikroTik+CHR+%C2%B7+Cisco+IOS+%C2%B7+OSPF+%C2%B7+eBGP+%C2%B7+EIGRP;Linux+Server+%C2%B7+Proxmox+%C2%B7+VMware+%26+VirtualBox;Building+networks%2C+one+topology+at+a+time)](https://github.com/RevanAnugrah)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/revan-anugrah-wibowo/)
![Location](https://img.shields.io/badge/Kota%20Tangerang-Indonesia-red?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to](https://img.shields.io/badge/Open%20to-PKL%20%2F%20Internship-success?style=for-the-badge)

</div>

---

## 👋 About Me

I'm a **TJKT (Teknik Jaringan Komputer dan Telekomunikasi) student** at **SMKN 3 Kota Tangerang**, passionate about designing, simulating, and troubleshooting multi-vendor network infrastructure.

- 🌐 I build multi-site and multi-vendor topologies in **GNS3** and **Cisco Packet Tracer** (**MikroTik RouterOS CHR**, **Cisco IOS / IOSvL2**, **OSPF**, **eBGP**, **EIGRP**, **RIPv2**, **Static Routing**, **VLAN**, **VoIP CME**, **AAA/RADIUS**, **SSH**, **ACL**)
- 🖧 I work with virtualized lab environments across **Proxmox**, **VMware (GNS3 VM / KVM)**, and **VirtualBox**
- 🐧 I'm learning **Linux server administration**, web hosting panels, and infrastructure monitoring
- 💻 I'm picking up **front-end basics** (HTML, CSS, JavaScript)
- 🎯 I'm looking for a **PKL / internship** in network engineering or system administration

---

## 🛠️ Skills

**Networking & Routing**

![GNS3](https://img.shields.io/badge/GNS3-FF6C37?style=for-the-badge&logo=gns3&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco%20Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Cisco IOSvL2](https://img.shields.io/badge/Cisco%20IOS%20%2F%20IOSvL2-049FD9?style=for-the-badge&logo=cisco&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik%20RouterOS-293239?style=for-the-badge&logo=mikrotik&logoColor=white)
![OSPF](https://img.shields.io/badge/Routing-OSPF-10B981?style=for-the-badge)
![eBGP](https://img.shields.io/badge/Routing-eBGP-C0392B?style=for-the-badge)
![EIGRP](https://img.shields.io/badge/Routing-EIGRP-2E9E6B?style=for-the-badge)
![RIPv2](https://img.shields.io/badge/Routing-RIPv2-0A66C2?style=for-the-badge)
![Static Routing](https://img.shields.io/badge/Routing-Static%20Route-3B82F6?style=for-the-badge)
![VLAN](https://img.shields.io/badge/VLAN%20%26%20Trunking-2E9E6B?style=for-the-badge)
![AAA](https://img.shields.io/badge/SSH%20%2F%20AAA%20RADIUS-EF4444?style=for-the-badge)
![ACL](https://img.shields.io/badge/ACL-D62828?style=for-the-badge)
![DHCP](https://img.shields.io/badge/DHCP%20%26%20DNS-8E44AD?style=for-the-badge)
![VoIP](https://img.shields.io/badge/VoIP%20(CME)-E8890C?style=for-the-badge)
![Subnetting](https://img.shields.io/badge/Subnetting-555?style=for-the-badge)

**Systems, Virtualization & Servers**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

**Web (learning)**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="55%">

### 🌐 AetherNet — Multi-Protocol Campus Network

A multi-site campus and branch network simulation in **Cisco Packet Tracer** integrating **four routing protocols** with controlled redistribution and dual-core redundancy.

- 🔀 **4 Routing Protocols:** OSPF Area 0, eBGP (Serial WAN), EIGRP AS 100, and RIPv2
- 🔁 **Controlled Redistribution:** loop-free border design at `WAN1/WAN2`, `EDGE1`, and `R5`
- 🧱 **Dual-Core Redundancy & VLANs:** each building dual-homed to Layer 3 cores (`C1` & `C2`) with Data & Voice VLANs
- ☎️ **VoIP (Cisco CME):** automated IP Phone provisioning via DHCP `option 150`
- 🔐 **SSH v2 & AAA (RADIUS):** centralized management from VLAN 99 plus DNS, HTTP, TFTP, Syslog, Email, FTP & NTP

[![View Project](https://img.shields.io/badge/View%20Project-1F6FB2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RevanAnugrah/aethernet-packet-tracer)

</td>
<td width="45%">

<img width="955" height="346" alt="AetherNet Multi-Protocol Campus Topology" src="https://github.com/user-attachments/assets/62580bf6-b667-4457-b5a6-71b1c5419fdc" />

</td>
</tr>
<tr>
<td width="55%">

### 🔀 Multi-Vendor Inter-Branch Network (GNS3)

An end-to-end **LAN-to-LAN inter-branch network** simulated in **GNS3**, combining **MikroTik RouterOS CHR** and **Cisco IOSvL2** across a hybrid hypervisor setup.

- 🤝 **Multi-Vendor Integration:** 2x `MikroTik CHR` as Layer 3 gateways + 2x `Cisco IOSvL2` as Layer 2 access switches
- 🛣️ **Point-to-Point WAN & Static Routing:** bidirectional static routes connecting LAN 1 (`192.168.10.0/24`) and LAN 2 (`192.168.20.0/24`)
- ⚡ **Hybrid Virtualization:** QEMU/KVM acceleration on VMware GNS3 VM paired with VirtualBox Linked Clones
- 📘 **Complete Lab Guide:** port mapping reference, full CLI scripts, and printable PDF module

[![View Project](https://img.shields.io/badge/View%20Project-1F6FB2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RevanAnugrah)

</td>
<td width="45%">

<img width="705" height="584" alt="GNS3 Multi-Vendor Topology" src="https://github.com/user-attachments/assets/442e2650-6f74-4bdb-946b-4d027f837ce7" />

</td>
</tr>
<tr>
<td width="55%">

### 🏢 Three-Building Enterprise Network (OSPF & AAA)

A Cisco Packet Tracer simulation of **three buildings (Gedung A, B, and C)** connected in a redundant **triangle Serial WAN** topology.

- 🛣️ **OSPF Area 0** dynamic routing with automatic failover
- 🧩 **3 VLANs (50, 70, 100)** with 802.1Q Router-on-a-Stick
- 🔐 **AAA Server (RADIUS)** & local fallback authentication
- 📶 **Wireless LAN** for smartphones & laptops via AP
- 🗂️ **DHCP Pools** per VLAN & centralized Server/Printer zone

Full topology, subnet plan, step-by-step configuration guide, and CLI scripts are available in the repo.

[![View Project](https://img.shields.io/badge/View%20Project-1F6FB2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RevanAnugrah/cisco-roas-ospf-aaa-simulation)

</td>
<td width="45%">

<img width="951" height="353" alt="Three-Building OSPF Topology" src="https://github.com/user-attachments/assets/cf8a2981-4cfb-4d82-ad2a-883934125e01" />

</td>
</tr>
<tr>
<td width="55%">

### 🌐 Two-Building Enterprise Network (RIPv2 & VoIP)

A Cisco Packet Tracer simulation of two buildings connected by a **ring of 4 routers**.

- 🧩 **7 VLANs** with router-on-a-stick
- 🛣️ **RIPv2** dynamic routing
- 📞 **VoIP** with IP Phones
- 📶 **Wireless** access points
- 🗂️ **DHCP** and **DNS** services
- 🛡️ **ACL** to block a specific host

Full topology, addressing plan, step-by-step configuration, and device configs are in the repo.

[![View Project](https://img.shields.io/badge/View%20Project-1F6FB2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RevanAnugrah/network-simulation-vlan-ripv2-voip)

</td>
<td width="45%">

<img width="944" height="345" alt="Two-Building RIPv2 Topology" src="https://github.com/user-attachments/assets/2f0f9e16-aa7a-489b-bd31-7554a6279ae1" />

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats-fast.vercel.app/api?username=RevanAnugrah&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats">
<img height="170" src="https://streak-stats.demolab.com/?user=RevanAnugrah&theme=tokyonight&hide_border=true" alt="GitHub streak">

</div>

---

## 📚 Currently Learning

| Topic | Focus |
|-------|-------|
| 🔀 **Routing** | Multi-area OSPF, BGP policy control, and MikroTik RouterOS |
| 🐧 **Linux** | Server setup, services, and security |
| 🖥️ **Virtualization** | Proxmox containers/VMs and GNS3 multi-vendor labs |
| 📈 **Monitoring** | Zabbix for servers and networks |
| 🏅 **Certification** | Cisco CCNA & MikroTik certification path |

---

## 📫 Let's Connect

I'm open to **internship (PKL) opportunities** and happy to talk about networking.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Revan%20Anugrah%20Wibowo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/revan-anugrah-wibowo/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FB2,100:0A1220&height=100&section=footer" width="100%" alt="Footer">

</div>
```