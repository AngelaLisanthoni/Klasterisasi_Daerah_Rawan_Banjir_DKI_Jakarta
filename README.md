# Klasterisasi Daerah Rawan Banjir DKI Jakarta

Klasterisasi ini dilakukan untuk melihat daerah mana di provinsi DKI Jakarta yang rawan banjir berdasarkan kecamatannya. Terbagi menjadi 4 cluster dimana 0 paling tidak rawan dan 4 yang paling rawan. Algoritma yang digunakan adalah Hierarichal Clustering berbasis Agglomerative Clustering yang codenya secara scratch (tanpa modul bawaan dari python). Adapun beberapa tahapan yang dilakukan adalah:
1. Menggabungkan data per bulan menjadi satu dataset 
2. Melakukan pre-processing data (seperti menghapus duplikasi data, mengganti typo, dan lainnya)
3. Melakukan ekstraksi fitur menggunakan PCA
4. Melakukan EDA secara statistik maupun visualisasi
5. Pemodelan Data menggunakan algoritma hierarichal clustering
6. Melakukan evaluasi dengan silhouette score
7. Membuat visualisasi Data hasil cluster
8. Membuat dashboard

