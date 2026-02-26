# Pengembangan-metode

Repositori ini berisi pengembangan metode analisis sentimen untuk ulasan *A Business Proposal* versi remake Indonesia.

## Update terbaru: Hybrid Contextual Embedding–SVM (lanjutan)
- Notebook kini memuat pipeline hybrid yang lebih lengkap:
  - **Embedding kontekstual IndoBERT**.
  - **TF-IDF karakter** untuk variasi ejaan/slang.
  - **Fusi fitur + reduksi dimensi (TruncatedSVD)**.
  - **Linear SVM** dengan `class_weight='balanced'`.
- Ditambahkan **ablation study**:
  - TF-IDF saja
  - Contextual embedding saja
  - Hybrid (gabungan)
- Ditambahkan **5-fold cross validation** (metrik F1-macro) untuk validasi stabilitas model.

Notebook utama: `Sentiment_Analysis_A_Business_Proposal_SVM.ipynb`
