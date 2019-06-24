### Tugas Akhir NLP
-------------------

Dikerjakan oleh :
- Asel Hidayat Sjamhars
- Muhammad Ikhsan Kurniawan
- Rahmania Astrid Mochtar

Penjelasan source code :
- `dataset_processing.ipynb` digunakan untuk melakukan preprocessing terhadap data yang akan dilakukan klasifikasi.
- `pos_tag_gold_standard.ipynb` digunakan untuk mengekstrak POS dari file .xml gold standard menjadi object dictionary python.
- `pos_tagging.ipynb` digunakan untuk melakukan POS tagging terhadap train data berdasarkan gold standard. Kami mengambil POS tag yang berdasarkan tag sensenya.
- `tfidf_training.ipynb` digunakan untuk melakukan WSD dengan pendekatan term-sample task dan melakukan training terhadap model yang kami lakukan.

Flow :
dataset_processing -> pos_tagging -> tfidf_training