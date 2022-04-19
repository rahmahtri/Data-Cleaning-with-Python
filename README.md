# Categorical-Data-Encoding-with-Python
Repository ini berisi bagaimana melakukan data encoding pada python

## Description
Categorical Data Encoding adalah proses mengubah *feature categorical* menjadi feature *numeric*

### 1. Label Encoding (Naif)
Label encoding adalah perubahan *feature categorical* menjadi *numeric* dengan memberikan angka yang berbeda bagi masing-masing nilai unik
Dapat disimpulkan bahwa label encoding dapat digunakan apabila *feature categorical* tidak berjumlah lebih dari `2`

### 2. Ordinal Encoding
Ordinal encoding dapat digunakan apabila terdapat urutan pada *feature categorical* dan jumlah *feature categorical* >= `3`

### 3. One Hot Encoding
One hot encoding adalah perubahan *feature categorical* menjadi *numeric* dengan menjadikan masing-masing nilai unik feature tersendiri
One hot encoding dapat digunakan apabila **tidak** terdapat urutan pada *feature categorical* dan jumlah *feature categorical* >= `3`

### 4. Mean Encoding
Mean/Target Encoding adalah perubahan *feature categorical* menjadi *numeric* yang mirip dengan label encoding tetapi dikorelasikan dengan target

### 5. Frequency Encoding
Frequency Encoding adalah perubahan *feature categorical* menjadi *numeric* dengan menjadikan frequency/percentage dari kemunculannya pada dataset

## Requirements
1. Gunakan dataset berikut pada [link ini](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Pastikan library ini terinstall pada notebook anda `pandas, numpy, seaborn, matplotlib.pyplot`
