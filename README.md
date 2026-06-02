# ShadeMate Streamlit UI

File yang dibuat:
- `app_ui_baru.py` — UI Streamlit baru untuk aplikasi ShadeMate
- `style.css` — styling pastel pink-matcha sesuai referensi Figma
- `assets/` — logo dan dummy product images
- `data/foundation_mst.csv` — dataset foundation dari file yang kamu kirim

## Cara menjalankan

```bash
cd shademate_streamlit_ui
streamlit run app_ui_baru.py
```

Catatan:
- Asset product masih dummy.
- Halaman Results masih memakai hasil analisis dummy.
- Halaman Recommendations sudah membaca brand, price, shade, hex, dan LAB dari `data/foundation_mst.csv`.
- Nanti tinggal hubungkan variabel `DETECTED` dan fungsi rekomendasi dengan logic/model asli dari `app.py` lama.
