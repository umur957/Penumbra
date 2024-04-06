# Penumbra
# Kurulum
 curl -sSfL -O https://github.com/penumbra-zone/penumbra/releases/download/v0.71.0/pcli-x86_64-unknown-linux-gnu.tar.xz &
 unxz pcli-x86_64-unknown-linux-gnu.tar.xz &
 tar -xf pcli-x86_64-unknown-linux-gnu.tar &
 sudo mv pcli-x86_64-unknown-linux-gnu/pcli /usr/local/bin/ 
# Versiyon kontrol
 pcli --version 
# Cuzdan Ekleme
 pcli init soft-kms import-phrase 
# Yeni cuzdan yaratma
 pcli init soft-kms generate
# Cuzdan adresini gormek ve daha sonra faucetten coin almak
 pcli view address 0
# Bakiye kontrol etmek
 pcli view balance
# Calistiralim
 screen -S penumbra &
 pcli ceremony contribute --phase 2 --bid 60penumbra

# Ctrl a + d   / form: https://t.co/hQOGR9JKMQ  / Slot bulma linki: https://t.co/wuuTvlzeiA
