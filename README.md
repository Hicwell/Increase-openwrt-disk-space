# OpenWrt Disk Alanı Artırma (Exroot)


## USB Bellek ile OpenWrt Disk Alanını Artırın

Merhaba! Bu araç, OpenWrt cihazınızın kısıtlı dahili hafızasını bir USB bellek kullanarak artırmanıza (Exroot) yardımcı olur. Bu repoyu, orijinali silinse dahi elimde güvenli bir yedek olması için çatalladım (fork).

### Kurulum Nasıl Yapılır?

📍 **Adım 1:** USB belleği router'ın USB portuna takın.

📍 **Adım 2:** Putty veya benzeri bir programla SSH üzerinden router'a bağlanın ve şu komutu çalıştırın:

```bash
rm -f exroot.sh && wget https://raw.githubusercontent.com/Hicwell/Increase-openwrt-disk-space/main/exroot.sh && chmod 777 exroot.sh && sh exroot.sh
