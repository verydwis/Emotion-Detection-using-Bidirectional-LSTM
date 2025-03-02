# Emotion-Detection-using-Bidirectional-LSTM

Deteksi Emosi, seperti namanya, berarti mengidentifikasi emosi di balik suatu teks atau ucapan. Deteksi emosi merupakan tugas penting dalam Pemrosesan Bahasa Alami (Natural Language Processing).  

Deteksi emosi telah diterapkan dalam berbagai tugas bisnis. Contohnya adalah Twitter, di mana jutaan pengguna menulis tweet, dan model pembelajaran mesin (ML) dapat membaca semua postingan serta mengklasifikasikan emosi di balik tweet tersebut.  

Contoh lainnya adalah Amazon, di mana model sentimen mengklasifikasikan ulasan sebagai positif, negatif, atau netral. Berdasarkan klasifikasi tersebut, Amazon dapat mengetahui apakah suatu produk memiliki kualitas yang baik atau tidak.

# Loading the Data for Emotion Detection

![image](https://github.com/user-attachments/assets/c4b43da5-8625-49ae-88ec-39628d44893c)

df_train memiliki 16000 baris dan 2 kolom, df_test & df_val memiliki 2000 baris dan 2 kolom. Sekarang Mari kita periksa distribusi data berdasarkan kategori.


![image](https://github.com/user-attachments/assets/d2dd6bae-b221-4292-909e-2af7f0e11d79)


kategori Surprise memiliki sampel data paling sedikit, Anda dapat membuat data seimbang dengan menyeimbangkan semua kategori baik dengan over-sampling atau under-sampling.

# Plotting the History


![image](https://github.com/user-attachments/assets/b0f4b096-1ae6-4dc0-9f96-cfbd7670aff9)

# Test the Emotion Detection Model


<img width="551" alt="image" src="https://github.com/user-attachments/assets/6cee0cd3-bbe2-4b25-a2c1-8ed7fa0380ab" />



