xderm-mini SSL (SSH & VMESS)
for profesional tool script armbian stb

dibutuhkan: python3 (gunakan koneksi internet stabil untuk instalasi agar tidak ada error).

Cara Install
sudo su
wget -O /usr/bin/xderm-mini https://raw.githubusercontent.com/kevindoni/Xderm-Mini-GUI-Openwrt/main/xderm-mini && chmod +x /usr/bin/xderm-mini
xderm-mini setup #khusus PURE LINUX.
v2ray:
bash <(curl -L https://raw.githubusercontent.com/v2fly/fhs-install-v2ray/master/install-release.sh) #khusus PURE LINUX.
ubah/edit file config yang berisi akun ssh dan bug host ssl di /root/config.txt

mode=0 untuk ssh, mode=1 untuk vmess

setelah setup selesai, ketik xderm-mini untuk perintah yang lain.

Thanks.
