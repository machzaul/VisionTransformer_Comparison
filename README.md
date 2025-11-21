
Vision Transformer Comparison (Swin vs MAE)

Project ini membandingkan performa dua model Vision Transformer
menggunakan library timm: - Swin Transformer - DeiT / MAE (Masked
Autoencoder)

Repository:
https://github.com/machzaul/VisionTransformer_Comparison

------------------------------------------------------------------------

Struktur Repository

    VisionTransformer_Comparison/
    │── swin.ipynb        # Notebook training Swin Transformer
    │── mae.ipynb         # Notebook training MAE 
    │── requirements.txt
    │── README.txt

------------------------------------------------------------------------

Dataset

Dataset dapat diunduh di Google Drive:

-   Dataset gambar:
    https://drive.google.com/drive/folders/1tFukd5YH1T8xsRl4j8Yt7OOQH_I0rpV4?usp=sharing

-   Label CSV:
    https://drive.google.com/file/d/1tMZsYXIifEl2S3qnkwNJs1G6KS-pl-tL/view?usp=sharing

Letakkan dataset sesuai struktur berikut:

    dataset/
    │── img/
    │── img/
    │── img/
    │── img/
    │── img/......

    labels.csv

------------------------------------------------------------------------

Instalasi

Install dependency menggunakan:

    pip install -r requirements.txt

------------------------------------------------------------------------

 Cara Menjalankan

1.  Buka Jupyter Notebook atau Google Colab
2.  Jalankan file:
    -   swin.ipynb untuk training Swin Transformer
    -   mae.ipynb untuk training DeiT/MAE
3.  Pastikan path dataset sudah benar
4.  Model akan otomatis melakukan training dan menghasilkan grafik
    loss + akurasi

------------------------------------------------------------------------

Model yang Dibandingkan

  Model       Deskripsi
  ----------- --------------------------------------------
  Swin Tiny   Efficient hierarchical transformer
  MAE         Self-supervised pretraining (encoder only)

------------------------------------------------------------------------

Output

-   Training loss & validation loss
-   Training accuracy & validation accuracy
-   Grafik learning curve
-   Model .pth (jika kamu menyimpannya)

------------------------------------------------------------------------

Kontributor

machzaul harmansyah
Informatics Engineering
2025
