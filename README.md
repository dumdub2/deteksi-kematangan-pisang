# Deteksi Kematangan Pisang

Aplikasi Streamlit untuk klasifikasi kematangan pisang (unripe / ripe / overripe) dengan CNN,
dilengkapi dua fitur unik: **Grad-CAM** dan **confidence threshold** (pesan "TIDAK YAKIN").

## Struktur
- `app.py` : aplikasi Streamlit
- `inference_utils.py` : fungsi inferensi, Grad-CAM, dan keputusan threshold
- `models/` : `best_model.keras`, `class_names.json`, `inference_config.json`
- `requirements.txt` : dependensi

## Cara menjalankan lokal
```
pip install -r requirements.txt
streamlit run app.py
```

## Notebook
`KlasifikasiKematanganPisang.ipynb` (pelatihan dan evaluasi) dan
`Fitur_Unik_GradCAM_Threshold.ipynb` (Grad-CAM dan threshold).

## Aplikasi online
Tautan: (isi setelah deploy di Streamlit Community Cloud)
