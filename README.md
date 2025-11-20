ZMK Cradio/Sweep untuk Super Mini / Promicro Wireless NRF52840.

ZMK Codes Docs https://zmk.dev/docs/codes

Ada update baru ZMK Studio remapping tanpa perlu di flash https://zmk.studio/

Untuk cara fork repository ini :

ZMK Keymap Editor https://nickcoutsos.github.io/keymap-editor/
Tutorial Mapping ZMK https://youtu.be/cAi5pnkz48M

Setelah firmware di download, tekan 2x tombol reset saat USB terhubung. lalu tinggal extract dan drop file .uf2 nya di disk bootloader.


PENJELASAN BLUETOOTH

Ini di ibaratkan jika ada display
Penjelasan ZMK

Bluetooth auto ON. Penjelasannya di display ada angka dan simbol, angka tersebut menunjukan BT Profile. Contoh ada angka 1 di display berarti itu BT_SEL 0 di keymap. Jika ada gambar X berarti BT Profile tersebut sudah pernah terkoneksi sebelumnya. Jika ingin pairing ulang bisa press BT_CLR di keymap (akan berubah jadi gambar gerigi) lalu pair ulang dan jika berhasil gambar akan berubah menjadi ceklis. Tidak bisa di overwrite, misalnya keyboard ingin di gunakan di Tablet namun sudah pernah terkoneksi di PC. Harus pindah ke BT_SEL yang lain atau di Clear lagi dengan BT_CLR. Misal BT_SEL 0 di PC, BT_SEL 1 di tablet, dan BT_SEL 2 di Mac.
