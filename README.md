# 🏥 Simulasi Antrian Pendaftaran Klinik

**Capstone Project — Simulasi Sistem Unit 12**  
Program Studi: Sistem Informasi

## Deskripsi
Studi simulasi DES (Discrete Event Simulation) untuk menganalisis 
dampak penambahan petugas dan perubahan kebijakan antrian terhadap 
waktu tunggu pasien di loket pendaftaran klinik pada jam sibuk.

## Anggota Tim
| Nama | NIM | Peran |
|------|-----|-------|
| Ferdian Dwi Fitama | 2313000004 | Project Lead / Modeler |
| Achmad Rafi F | 2313000018 | Simulation Engineer / Analyst |
| Choirunnisa | 2313000019 | Documenter / Presenter |

## Cara Menjalankan Simulasi
1. Install dependencies:
   pip install simpy numpy scipy pandas matplotlib

2. Jalankan simulasi:
   python clinic_des.py

## Skenario yang Diuji
- S0: Baseline (1 petugas, FCFS)
- S1: Tambah 1 petugas
- S2: Priority queue
- S3: Capacity limit
- S4: Optimal combo (2 petugas + priority)

## Tools
- Python 3.x
- SimPy (DES engine)
- NumPy, SciPy, Pandas, Matplotlib
