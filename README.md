# InsomWRT
![Downloads](https://img.shields.io/github/downloads/bobbyunknown/InsomWRT/total.svg)
![Views](https://komarev.com/ghpvc/?username=bobbyunknown&repo=InsomWRT)

### Telegram group:
[![SanTech](https://img.shields.io/badge/SanTech-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/+TuLCASzJrVJmNzM1)

**OpenWRT untuk perangkat berbasis ARM**

Firmware openwrt 23.05.05
- B860H WIFI ON sudah test
- OPIZ 3 WIFI ON sudah test
- H680P dan yang lain nya belum test gak punya device nya

## Sudah di tambahkan

- Netdata xos (maaf saya buang menu karna suka melebar)
- Log viewer
- Vnstat
- Filemanagar (bisa search file)
- Theme argon + config (sudah di tambahkan menu)
- Rakitan manager
- 3ginfo lite
- modemband
- Modeminfo
- SMSTool
- Droidnet
- IPinfo
- Mactodong
- Netspeedtest (local & online)
- Speedtest CLI ketik "speedtest.net"
- ModemManager auto reconnect (by radenku)

### Tunnel
- Nekoclash
- Openclash
- Passwall
- MihomoTproxy

# Tambahan
Jika ingin menggunakan Passwall, silakan install dependensi nya terlebih dahulu
```
opkg update && opkg install ipset ipt2socks iptables iptables-legacy iptables-mod-iprange \
iptables-mod-socket iptables-mod-tproxy kmod-ipt-nat coreutils coreutils-base64 \
coreutils-nohup curl dns2socks ip-full libuci-lua lua luci-compat luci-lib-jsonc \
microsocks resolveip tcping unzip
```
Install juga
```
opkg install v2ray-extra v2ray-geoip v2ray-geosite v2ray-ctl xray-geodata
```


***Catatan: Jika mengalami masalah dengan ttyd tidak bisa di buka:***
1. Klik menu System/Startup
2. Scroll ke bawah cari ttyd
3. Klik tombol Restart

**Login:**
- user: root
- pass: dbai

## Thank to:
- Allah SWT
- DBAI (Terima kasih banyak sepepuh bantu fix wifi)
- IndoWRT

## Screenshot:
<details>
<summary>Klik untuk melihat screenshot</summary>

![screenshot 1](img/Snag_b3a08e.png)
![screenshot 2](img/Snag_b3a0ec.png)
![screenshot 3](img/Snag_b3a15a.png)
![screenshot 4](img/Snag_b3a254.png)
![screenshot 5](img/Snag_b3a2f0.png)
![screenshot 6](img/Snag_b3a36d.png)
![screenshot 7](img/Snag_b3a409.png)

</details>

## Support me:

[![Sociabuzz](https://img.shields.io/badge/Sociabuzz-1DA1F2?style=for-the-badge&logo=sociabuzz&logoColor=white)](https://sociabuzz.com/bobbyunknown/tribe)
[![Saweria](https://img.shields.io/badge/Saweria-FFA500?style=for-the-badge&logo=saweria&logoColor=white)](https://saweria.co/bobbyunknown)

## Build
Menggunakan [ULO-Builder](https://github.com/armarchindo/ULO-Builder)
## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detailnya.
