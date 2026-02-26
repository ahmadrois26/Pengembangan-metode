# Pengembangan-metode

Repositori ini berisi pengembangan metode analisis sentimen untuk ulasan *A Business Proposal* versi remake Indonesia.

## Update terbaru
- Menambahkan integrasi **hybrid contextual embedding–SVM** pada notebook.
- Pendekatan ini menggabungkan:
  - **Embedding kontekstual IndoBERT** untuk representasi semantik kalimat.
  - **TF-IDF karakter** untuk menangkap variasi ejaan/slang.
  - **Linear SVM** sebagai classifier akhir pada fitur gabungan.

Notebook utama: `Sentiment_Analysis_A_Business_Proposal_SVM.ipynb`
