# Neverness to Everness (NTE) Global - Text Assets

Repositori ini berisi ekstraksi teks mentah dari game **Neverness to Everness (NTE)** versi Global. Tujuan repositori ini adalah untuk memfasilitasi para modder dan komunitas translator yang ingin melakukan lokalisasi (fan-translation) ke berbagai bahasa.

## 📊 Informasi Data
- **Engine:** Unreal Engine 5
- **Format:** JSON (.json)
- **Karakter Teridentifikasi:** Player, NPC, System, Shop, dll.
- **Encoding:** UTF-8 (Strictly Required)

## 📁 Struktur File
Data utama tersimpan di folder `Data/en_US.json`. Struktur datanya menggunakan format Key-Value:
- **Key:** ID unik (Contoh: `SD_S0111_Player_006`) - **JANGAN DIUBAH**.
- **Value:** Teks dialog/UI yang bisa diterjemahkan.

## 🛠 Panduan Penerjemahan
Bagi kamu yang ingin mulai menerjemahkan, ikuti aturan dasar ini:

1. **Gunakan Text Editor yang Mendukung JSON:** Disarankan menggunakan **VS Code**, **Sublime Text**, atau **Notepad++**.
2. **Pertahankan Key:** Hanya ubah teks di dalam tanda kutip bagian kanan (Value).
   - *Salah:* `"ID_Baru": "Halo"`
   - *Benar:* `"SD_S0111_Player_006": "Halo, apa kabar?"`
3. **Handle Special Characters:** Hati-hati dengan karakter seperti `\n` (baris baru) atau variabel jika ada di kemudian hari.
4. **Encoding:** Pastikan file disimpan dengan format **UTF-8 without BOM**.

## 🤝 Cara Berkontribusi
Jika kamu sudah menyelesaikan terjemahan ke bahasa lain (misalnya Bahasa Indonesia):
1. Fork repositori ini.
2. Tambahkan file kamu ke folder `Translations/` dengan nama `id_ID.json`.
3. Kirimkan **Pull Request**.

## ⚠️ Disclaimer
Aset teks asli di dalam repositori ini adalah hak cipta milik **Hotta Studio**. Repositori ini dibuat hanya untuk tujuan edukasi dan bantuan komunitas modding non-komersial. Silakan hapus jika ada permintaan resmi dari pihak pengembang.

---
*Dikelola oleh komunitas untuk komunitas.*
