# 📋 Panduan Deploy & SEO — PT. Bina Anugrah Nusantara

## File yang Perlu Di-upload ke Server (binanusantara.co.id)

```
/
├── index.html          ← Website utama
├── sitemap.xml         ← Peta halaman untuk Google
├── robots.txt          ← Izin crawling Google
├── logo-og.png         ← Gambar thumbnail saat link dibagikan (1200x630px)
└── og-image.jpg        ← Backup OG image format JPG
```

---

## ✅ Langkah Agar Google Tampilkan Deskripsi

### 1. Upload Semua File ke Root Domain
Upload semua file di atas ke folder root `public_html/` atau `www/`
di hosting **binanusantara.co.id**

### 2. Daftarkan ke Google Search Console
1. Buka: https://search.google.com/search-console
2. Tambah properti: `https://binanusantara.co.id`
3. Verifikasi dengan file HTML atau DNS TXT record
4. Klik **"Request Indexing"** pada URL homepage

### 3. Submit Sitemap
Di Google Search Console → Sitemaps → tambahkan:
```
https://binanusantara.co.id/sitemap.xml
```

### 4. Test Struktur Data
Buka: https://search.google.com/test/rich-results
Masukkan URL: `https://binanusantara.co.id`

### 5. Test Meta Description
Buka: https://www.google.com/webmasters/tools/richsnippets
atau gunakan: https://metatags.io

---

## 📊 Meta Tags yang Sudah Dioptimasi

| Tag | Nilai | Status |
|-----|-------|--------|
| Title | PT. Bina Anugrah Nusantara \| Refractory & Material Keramik Indonesia | ✅ 70 chars |
| Meta Description | Supplier refractory, material keramik, glaze & layanan teknis kiln industri Indonesia. 10+ tahun pengalaman. Hubungi: 0812-9087-1996. | ✅ 155 chars |
| OG Image | logo-og.png (1200x630px) | ✅ |
| JSON-LD Schema | Organization + LocalBusiness + WebSite + FAQPage | ✅ |
| Canonical URL | https://binanusantara.co.id/ | ✅ |
| robots.txt | Allow all, Sitemap declared | ✅ |
| sitemap.xml | 5 URLs dengan priority | ✅ |
| Hreflang | id (Indonesian) | ✅ |

---

## ⏱ Estimasi Waktu Google Index

- **Pertama kali index**: 1-7 hari setelah submit ke Search Console
- **Deskripsi muncul**: 3-14 hari setelah indexing
- **Peringkat naik**: 1-3 bulan dengan konten berkualitas

---

## 📱 Test Tampilan di Google

Setelah deploy, cari di Google:
```
site:binanusantara.co.id
```
Kalau muncul = sudah terindex ✅

---
*Generated for PT. Bina Anugrah Nusantara — binanusantara.co.id*
