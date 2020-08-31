+++
categories = "catatan"
date = 2020-02-19T05:32:58Z
description = "agar LAMPP autostart saat booting pada linux centos 7 "
tags = ["centOs", "linux", "xampp", "lampp"]
title = "Autostart LAMPP pada CentOS 7"

+++
Berikut cara agar XAMPP untuk linux atau LAMPP otomatis dijalankan pada saat booting server atau PC anda. yang saya gunakana adalah OS centOS 7 (linux) kemungkinan tidak jauh berbeda dengan OS linux lainnya.

1. Buka file /etc/rc.d/rc.local
2. Tambahkan `/opt/lampp/lampp start` pada akhir file.
3. Buka console terminal
4. Jalankan perintah `chmod +x /etc/rc.d/rc.local` untuk mengubah hak ases file.
5. Uji coba dengan me-restart sistem.