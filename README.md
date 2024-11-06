# Praktikum-5
## Membuat class pegawai
<img width="423" alt="pegawai1" src="https://github.com/user-attachments/assets/aff8a9d6-10e0-4178-a48a-f38ca32c0b3b">

<img width="393" alt="pegawai2" src="https://github.com/user-attachments/assets/7ab7e1e8-b785-4334-b567-b838607aef4d">

**Penjelasan**
- Constructor Default (Pegawai()): Tidak menerima parameter dan mengatur nama sebagai "Tidak Diketahui" dan gajiPokok sebagai 0.0.
- Constructor Overload:
  - Pegawai(String nama): Menerima parameter nama dan mengatur gajiPokok sebagai 0.0 secara default.
  - Pegawai(String nama, double gajiPokok): Menerima parameter nama dan gajiPokok, dan mengatur keduanya.

## Membuat class manager
<img width="470" alt="manager" src="https://github.com/user-attachments/assets/50b43683-3f56-4162-840d-a5a82516ccbe">

**Penjelasan :**
- Constructor Default (Manager()): Mengatur tunjangan sebagai 0.0 dan memanggil constructor default dari Pegawai.
- Constructor Overload:
  - Manager(String nama, double gajiPokok): Menerima parameter nama dan gajiPokok, mengatur tunjangan sebagai 0.0 secara default.
  - Manager(String nama, double gajiPokok, double tunjangan): Menerima parameter nama, gajiPokok, dan tunjangan, dan mengatur ketiganya.

 ## Membuat class programmer
 <img width="448" alt="programmer1" src="https://github.com/user-attachments/assets/7fda7dbf-3b3e-4f68-bbb0-eeedb61095aa">

<img width="353" alt="programmer2" src="https://github.com/user-attachments/assets/aeed0d93-d725-4f59-a2ba-82f6d97b4575">

**Penjelasan :**
- Constructor Default (Programmer()): Mengatur bonus sebagai 0.0 dan memanggil constructor default dari Pegawai.
- Constructor Overload:
  - Programmer(String nama): Menerima parameter nama, dan mengatur gajiPokok dan bonus sebagai 0.0.
  - Programmer(String nama, double gajiPokok): Menerima parameter nama dan gajiPokok, dan mengatur bonus sebagai 0.0.
  - Programmer(String nama, double gajiPokok, double bonus): Menerima parameter nama, gajiPokok, dan bonus, dan mengatur ketiganya.

## Membuat class main
<img width="591" alt="main prak5" src="https://github.com/user-attachments/assets/f3cfda85-729d-4873-9eff-fd8d1b47a0ac">

**Penjelasan :**
- Membuat Objek Programmer dengan Constructor Overload:
  - Programmer("Andi Herlambang"): Menggunakan constructor Programmer yang hanya menerima nama. Nilai gajiPokok dan bonus akan diset sebagai 0.0 secara default.
  - Programmer("Riko", 6000000): Menggunakan constructor yang menerima nama dan gajiPokok. Nilai bonus akan diset sebagai 0.0.
  - Programmer("Dina", 5000000, 3000000): Menggunakan constructor yang menerima nama, gajiPokok, dan bonus.

## Output
<img width="406" alt="output prak5" src="https://github.com/user-attachments/assets/32b3ebe1-f1a3-45bd-b5b5-2a53ad380710">
