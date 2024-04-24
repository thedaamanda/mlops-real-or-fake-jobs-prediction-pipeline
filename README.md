# Submission 1: Real / Fake Job Posting Prediction
Nama: Muhammad Theda Amanda

Username dicoding: thedaamanda

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Real / Fake Job Posting Prediction](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction) |
| Masalah | Lowongan pekerjaan palsu merupakan salah satu permasalahan yang sering terjadi di masyarakat. Lowongan pekerjaan di buat dengan tujuan tertentu yang tidak jelas, seperti penipuan, pencucian uang, atau bahkan tindak kriminal lainnya. Hal ini tentu sangat merugikan bagi masyarakat yang mencari pekerjaan. Dataset yang digunakan merupakan data lowongan pekerjaan yang terdiri dari 18 ribu data yang dimana terdapat 800 data lowongan pekerjaan palsu. Diharapkan dengan adanya dataset ini bisa membantu dalam memprediksi lowongan pekerjaan yang asli dan palsu. |
| Solusi machine learning | Dari permasalahan diatas dengan memanfaatkan teknologi, machine learning menjadi salah satu solusi untuk memprediksi apakah suatu lowongan pekerjaan itu asli atau palsu. Dengan sebuah sistem prediksi lowongan pekerjaan, diharapkan para masyarakat dapat terbantu untuk dapat mendeteksi keaslian lowongan pekerjaan lebih awal. |
| Metode pengolahan | Metode pengolahan yang digunakan adalah tokenisasi sebagai fitur input model, data awal yang berupa teks akan dilakukan data cleaning menggunakan library *NLTK* dan pemilihan fitur yang akan digunakan untuk model. |
| Arsitektur model | Model ini dibangun cukup sederhana hanya menggunakan layer *TextVectorization* yang berguna untuk memproses input *string* ke dalam bentuk angka, *Embedding* yang berguna untuk mengukur kedekatan antar kata, *LSTM* yang berguna untuk memproses data sekuensial, *Dense* yang berguna untuk menghubungkan setiap neuron antar layer, dan *Dropout* yang berguna untuk mengurangi overfitting. |
| Metrik evaluasi | Metrik evaluasi yang digunakan adalah *binary accuracy*, *true positive rate*, *true negative rate*, *false positive rate*, *false negative rate* untuk mengevaluasi performa model. |
| Performa model | Model ini memiliki performa yang cukup baik dalam memberikan sebuah prediksi dan dari pelatihan yang dilakukan menghasilkan binary_accuracy sebesar 0.99, val_binary_accuracy sebesar 0.97, loss sebesar 0.01 dan val_loss sebesar 0.08. Dari hasil testing, performa model sudah mampu memberikan prediksi yang baik.
