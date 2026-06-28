# Custom Heart-Shaped LED PCB Keychain [WIP]

> **Status Proyek:** `Work in Progress` (Fase Desain)

## 📖 Deskripsi Proyek
Proyek ini adalah pembuatan gantungan kunci (*keychain*) kustom berbentuk hati yang dilengkapi dengan sirkuit lampu LED berkedip. Logika sirkuit elektronik ini mengadaptasi dan memodifikasi skematik klasik HBL-22 untuk menghasilkan efek animasi lampu yang estetik dan bekerja menggunakan daya baterai kecil.

## 🎯 Peran Saya (Electronic & PCB Design)
Dalam proyek mandiri ini, saya bertanggung jawab penuh atas seluruh tahapan R&D hardware:
* Menganalisis dan mereplikasi skematik elektronik sirkuit flasher HBL-22.
* Memilih komponen elektronik yang efisien dari segi dimensi (menyeimbangkan penggunaan komponen SMD/THT agar muat di area gantungan kunci).
* Merancang bentuk *outline* PCB kustom berbentuk hati.
* Melakukan *routing* jalur kelistrikan (*traces*) pada PCB dengan memperhatikan kerapian dan estetika visual sirkuit.

## 🛠️ Spesifikasi & Komponen (Bill of Materials)
* **Sumber Daya:** Baterai Li-Po 3.7V.
* **Kontroler/IC:** MCP6002 Dual Op-Amp dan MCP73831 Li-Po Charger Controller.
* **Indikator:** LED SMD 1210.
* **Komponen Pendukung:** Trimpot THT, S8050 SOT-23, USB Type C Female 6 pin, dan Slide Switch DPDT.
* **Komponen Pasif:** Resistor SMD 0805 dan Kapasitor SMD 0805 pendukung sirkuit *timing*.

## 📐 Desain Skematik & PCB Layout
### 1. Skematik Elektronik
<img width="869" height="419" alt="Screenshot_14" src="https://github.com/user-attachments/assets/4e77283d-c475-413a-b65d-166e47900d3a" />

### 2. Layout PCB (2D/3D Render)
<img width="634" height="444" alt="Screenshot_13" src="https://github.com/user-attachments/assets/447d2058-10c4-4f66-bba3-e42ae5e1fa57" /> <br>
<img width="634" height="444" alt="Screenshot_15" src="https://github.com/user-attachments/assets/510d9c8e-c9e1-47e8-ac88-8572d7b8696b" />


## 📈 Perkembangan Proyek & Langkah Selanjutnya
Saat ini proyek telah menyelesaikan fase desain digital dengan tingkat kesiapan 90% pada aspek sirkuit. Beberapa langkah berikutnya yang akan dieksekusi adalah:
1.  [ ] Mengirimkan file Gerber ke pihak manufaktur PCB (Fabrikasi).
2.  [ ] Belanja dan pengumpulan komponen fisik (*sourcing components*).
3.  [ ] Proses penyolderan komponen ke papan PCB. (*assembly*)
4.  [ ] Pengujian fungsi sirkuit kelistrikan dan daya tahan baterai.
