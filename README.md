# capstone-project-ecommerce-data-classification-summarization

# 🛍️ Capstone Project: Data Classification & Summarization Using IBM Granite

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis dataset transaksi e-commerce dengan fokus pada klasifikasi produk dan pembuatan ringkasan deskripsi produk menggunakan model AI (IBM Granite / HuggingFace pipeline).  
Melalui analisis ini, diharapkan dapat diperoleh insight mengenai pola pembelian pelanggan serta rekomendasi strategis untuk bisnis.

## 📊 Dataset
- **Sumber**: Online Retail Dataset (CSV)  
- **Jumlah data**: 541.909 baris  
- **Kolom utama**:
  - `InvoiceNo` → nomor transaksi  
  - `StockCode` → kode produk  
  - `Description` → nama produk  
  - `Quantity` → jumlah produk dibeli  
  - `UnitPrice` → harga per unit  
  - `Country` → negara pelanggan  

## 🔎 Analysis Process
1. **Explorasi Data**: melihat struktur dataset, distribusi negara, produk terpopuler.  
2. **Classification**: menggunakan model AI untuk mengklasifikasikan deskripsi produk (contoh: kategori hadiah vs non-hadiah).  
3. **Summarization**: membuat ringkasan singkat dari deskripsi produk panjang.  
4. **Visualisasi**: menampilkan grafik negara dengan transaksi terbanyak.  

## 💡 Insight & Findings
- Mayoritas transaksi berasal dari **United Kingdom**.  
- Produk terpopuler banyak berupa **gift items & dekorasi musiman**.  
- Pola pembelian meningkat menjelang **musim liburan**.  

## ✅ Recommendations
- Fokus strategi pemasaran dan stok di **UK**.  
- Perbanyak stok **produk dekorasi musiman** menjelang akhir tahun.  
- Gunakan ringkasan produk untuk membuat **deskripsi singkat & menarik** di katalog online.  

## 🤖 AI Support Explanation
- **IBM Granite / HuggingFace pipeline** digunakan untuk:
  - *Classification*: mengklasifikasikan sentimen & kategori produk.  
  - *Summarization*: meringkas deskripsi produk panjang menjadi singkat & jelas.  

---
