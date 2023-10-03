---
sidebar_position: 3
title: Shared Directory
---

# `/Shared` Directory

Folder `Shared` adalah folder yang dikhususkan untuk menyimpan kode yang bersifat global/umum dan *reusable*. 
Seperti *reuse-component*, *Layout*, *Style*, API, *constants*, gambar dsb.

Terdapat beberapa bagian dibawah folder *shared*:

| Folder | Description |
|--------|-------------|
| /api | Folder /api dikhususkan untuk menyimpan segala kebutuhan yang menyangkut dengan request API |
| /components | Folder /components menyimpan semua komponent yang sudah di custom dan bersifat *reusable*. Lebih lanjut lihat pada bagian [`Custom Component`](./custom-component). |
| /components/layout | Folder ini berada di bawah folder /components untuk menyimpan Layout seperti Auth Layout dan Private Route Layout |
| /constants | Folder /constants digunakan untuk menyimpan ENDPOINT dan URL untuk mengelompokkan URL Auth dan Private. |
| /font | Folder /font untuk menyimpan asset font. |
| /hooks | Folder /hooks digunakan untuk menyimpan hooks yang bersifat global. Misalnya seperti `useLogoutUser()` |
| /images | Folder /images digunakan untuk menyimpan assets gambar. |
| /lib |  Folder /lib seringkali digunakan untuk menyimpan kode yang *library* berhubungan dengan logika bisnis utama. |
| /styles | Folder /styles digunakan untuk menyimpan style global. Folder ini juga menyimpan kode untuk kustom tema **and.design** lebih lanjut [`Customize Theme`](https://ant.design/docs/react/customize-theme). |
| /types | Folder /types digunakan untuk menyimpan type typescript |
| /utils | Folder yang digunakan untuk menyimpan fungsi-fungsi utilitas atau alat-alat yang dapat digunakan kembali. |