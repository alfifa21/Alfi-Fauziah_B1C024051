A. Mengapa Evaluasi Model Tidak Cukup Hanya Menggunakan Accuracy?

Dalam mendeteksi kanker payudara, kita tidak bisa hanya melihat nilai Accuracy untuk menilai apakah model sudah bekerja dengan baik. Ada beberapa hal yang perlu diperhatikan.
Data bisa tidak seimbang
Misalnya, jumlah pasien sehat jauh lebih banyak daripada pasien kanker. Dalam kondisi ini, model bisa saja memiliki nilai Accuracy yang tinggi hanya karena lebih sering menebak pasien sebagai sehat, padahal belum tentu mampu mendeteksi pasien kanker dengan baik.
Risiko False Negative
False Negative terjadi ketika pasien yang sebenarnya terkena kanker justru dianggap sehat oleh model. Kesalahan seperti ini cukup berbahaya karena pasien bisa terlambat mendapatkan pemeriksaan atau pengobatan.
Recall juga penting
Recall menunjukkan seberapa baik model dalam menemukan pasien yang benar-benar terkena kanker. Semakin tinggi nilai Recall, semakin sedikit kemungkinan pasien kanker yang terlewat.

Jadi, dalam kasus deteksi kanker payudara, Accuracy yang tinggi saja belum cukup. Model juga perlu memiliki nilai Recall yang tinggi agar sebanyak mungkin pasien yang benar-benar terkena kanker dapat terdeteksi.
