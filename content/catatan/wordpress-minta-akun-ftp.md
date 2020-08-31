---
title: Wordpress minta FTP akun saat update
date: 2020-08-28T14:28:39.000+08:00
categories: catatan
description: cara agar wordpress self hosting tidak minta akun FTP saat self hosting
tags:
- wp
- wordpress

---
Pernahkah kalian saat ingin update ataupun install tema maupun plugin di wordpress namun muncul permintaan akun FTP ? Padahal, kita tidak pernah tau ataupun men-setting akun FTP pada wordpress.

Biasanya ini terjadi pada web yang menggunakan CMS wordpress dan hosting sendiri

Anda Hanya perlu membahkan baris berikut

    /* Sets up direct update and install. */
    define('FS_METHOD', 'direct');

pada file wp-config.php yang ada di folder utama aplikasi web wordpress.