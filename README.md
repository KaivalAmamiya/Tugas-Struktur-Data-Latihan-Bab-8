# Tugas Latihan Bab 8 - Struktur Data

**Nama:** Achmad Mohammad Rivaldi  
**NIM:** 25091397061  
**Kelas:** 2025B  
**Mata Kuliah:** Struktur Data  
**Program Studi:** S1 Terapan Manajemen Informatika - Fakultas Vokasi - Universitas Negeri Surabaya  

---

## Soal

1. Tentukan kompleksitas waktu (worst case) untuk setiap operasi yang didefinisikan dalam class `TicketCounterSimulation`.

2. Lakukan eksekusi manual kode berikut dan tampilkan isi queue yang dihasilkan:
    ```python
    values = Queue()
    for i in range(16):
        if i % 3 == 0:
            values.enqueue(i)
    ```

3. Lakukan eksekusi manual kode berikut dan tampilkan isi queue yang dihasilkan:
    ```python
    values = Queue()
    for i in range(16):
        if i % 3 == 0:
            values.enqueue(i)
        elif i % 4 == 0:
            values.dequeue()
    ```

4. Implementasikan metode yang tersisa dari class `TicketCounterSimulation`.

5. Modifikasi kelas `TicketCounterSimulation` agar menggunakan satuan detik, bukan menit. Jalankan eksperimen dan buat tabel seperti Tabel 8.1.

6. Rancang dan implementasikan fungsi untuk membalik urutan item dalam queue. Hanya boleh menggunakan operasi Queue ADT (boleh pakai struktur data lain).
