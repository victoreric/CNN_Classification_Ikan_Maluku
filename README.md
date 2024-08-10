# CNN_Classification_Ikan_Maluku

Deskripsi:
Penelitian ini bertujuan untuk mengembangakan metode deep learning yang secara otomatis dapat mendeteksi dan mengenal jenis ikan melalui gambar atau foto. Model ini dikembangakn menggunakan arsitektur MobileNetV2. Arsitektur MobileNETV2 sangat ringan untuk algortima CNN sehingga cocok untuk penerapan pada mobile phone, website dan perangkat dengan system tertanam (Embbeded system seperti mesin cuci otomatis, mesin ATM, jam tangan digital atau system GPS.) 

DATASET :
Kami menggunakan dataset primer (foto ikan) yang diperoleh secara langsung dari para nelayan atau pemancing. Foto-foto ikan tersebut dikelompokan menjadi 4 jenis, antara lain : Ikan Lencam (Lethrinus lentjan), Ikan Kerapu Macan (Epinephelus Merra), Ikan Jangki (Lutjanus decuccatus) dan Ikan Kerapu Sunu (Plectropomus Leopardus).

CNN Arsitektur :
Arsitektur MobileNetV2 adalah convolution neural network (CNN) yang dikembangkan oleh Google AI. Artistektur ini didesian lebih ringan dan efektif, sehingga sangat cocok untuk penerapan pada mobile dan perangkat dengan system tertanam/ embedded system. MobileNetV2 memiliki 2 arsitektur, antara lain Feature extractor dan Classifier. Feature Extractor akan mengekstrak fitur-fitur dari input foto atau gambar. Sedangkan Classifier akan mengklasifikasikan foto/  gambar berdasarkan ekstrak fitur.  
Modeling:
Model ini telah melatih 100 epoch menggunakan adam optimizer.  Fungsi kehilangan (the lost function) mengguankan binary cross-entropy, dan metrik yang digunakan untuk mengevaluasi model adalah ketepatan, recall, F1 score dan akurasi.
Model telah di ujicoba dan mendapatkan hasil yang baik. Presisi, recall, F1 score dan akurasi menunjukan angka 1.0 untuk semua jenis dari dataset yang digunakan.
Akurasi Nilai rata-rata makro dan akurasi rata-rata tertimbang juga menunjukan angka 1.0.
 
Kesimpulan :
Hasil Penelitian ini menunjukkan bahwa model Deep Learning yang dapat secara otomatis mendeteksi dan mengenali jenis ikan dari foro/ gambar dapat dikembangkan dengan akurasi yang sangat tinggi. Pada penelitian ini, Model yang dikembangkan didasarkan pada arsitektur MobileNetV2, yang merupakan CNN ringan dan efisien yang sangat cocok untuk perangkat seluler dan perangkat embbede system.
HASIL :
Tingkat Akurasi dari model yang dikembangkan ini mencapai 99.99%.  Dapat disimpulkan bahwa model ini memiliki tingkat akurasi 99,99% untuk mengklasifikasi foto/ gambar dalam dataset yang dipakai untuk penelitian.

![image](https://github.com/user-attachments/assets/e785f4f4-6163-424e-a079-0ce25c9c5114)
