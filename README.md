# Cleaning_dataset_transaksi_penjualan
Proyek ini berfokus pada proses pembersihan data menggunakan Microsoft Excel agar dataset siap digunakan untuk analisis, visualisasi, maupun reporting.  Proses data cleaning meliputi: 
- Menghapus data duplikat
- Menangani missing values
- Standardisasi format data
- Perbaikan typo
- Formatting tanggal & angka
- Filtering dan validasi data

## 📂 Dataset
Dataset yang digunakan berada pada folder:

```bash
data/data_transaksi_penjualan_kotor.xlsx
```

## 🛠 Tools
Project ini menggunakan: 
- Microsoft Excel
- Excel Formula
- Pivot Table
- Conditional Formatting
- Power Query

## Langkah Data Cleaning
1. Import Dataset
   Membuka dataset mentah di Excel.

3. Data Inspection
   Pengecekan:
   - Missing values
   - Data duplikat
   - Kesalahan format
   - Inkonsistensi penulisan
  
3. Data Cleaning
   Beberapa fitur Excel yang digunakan:
   - Remove Duplicates
   - Find & Replace
   - TRIM()
   - Data Validation

4. Standardisasi Data
   - Format tanggal menjadi DD/MM/YYYY
   - Penyeragaman huruf kapital
   - Perbaikan nama kategori
  
5. Export Clean Data
Dataset hasil cleaning disimpan sebagai:
```bash
data_transaksi_penjualan_CLEANED.xlsx
