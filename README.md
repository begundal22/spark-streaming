# spark-streaming
Nama : Dio Aulia Ari Kurnia Sandi
Nim : 2041720086
Kelas : 3C

![1](https://github.com/begundal22/spark-streaming/assets/89907128/3d60526a-5e30-42ba-81d4-e5c4970e00b3)
![2](https://github.com/begundal22/spark-streaming/assets/89907128/daa59b68-2509-463e-89bc-a3825c3e0350)
![3](https://github.com/begundal22/spark-streaming/assets/89907128/d806e7c2-e3af-44d5-bbe6-47b454f626db)
![4](https://github.com/begundal22/spark-streaming/assets/89907128/7bed66fd-4754-4996-af8a-6b6c621fc9cc)
![5](https://github.com/begundal22/spark-streaming/assets/89907128/85aa1a59-16d0-44c6-8ee1-d9b09c8a62f4)
![6](https://github.com/begundal22/spark-streaming/assets/89907128/046ddd4c-7ba1-420d-8af1-c35514ee350f)


sys.argv: Ini adalah sebuah list dalam bahasa Python yang berisi argumen baris perintah yang dikirimkan ke sebuah skrip.

sys.stderr: Ini adalah objek mirip file dalam bahasa Python yang mewakili aliran error standar, yang digunakan untuk pesan error dan diagnosis.

StreamingContext: Ini adalah sebuah kelas dalam modul streaming Apache Spark yang digunakan untuk membuat konteks streaming, yang merupakan titik masuk utama untuk fungsionalitas streaming. Ini mewakili koneksi ke kluster streaming dan mengatur pemrosesan kontinu dari aliran data.

sc: Ini adalah sebuah instance dari kelas SparkContext dalam Apache Spark, yang merupakan titik masuk utama untuk membuat RDD (Resilient Distributed Datasets) dan melakukan operasi pada RDD tersebut.

socketTextStream: Ini adalah sebuah metode dalam kelas StreamingContext dari Apache Spark yang membuat input DStream (Discretized Stream) dengan menghubungkan ke soket TCP dan mendengarkan data.

reduceByKey: Ini adalah operasi transformasi dalam Apache Spark yang diterapkan pada sebuah pasangan RDD. Ini menggabungkan nilai-nilai setiap kunci menggunakan sebuah fungsi reduce yang ditentukan.

lambda line: Ini adalah sebuah fungsi lambda dalam bahasa Python yang mengambil parameter line dan dapat digunakan untuk mendefinisikan fungsi anonim. Ini sering digunakan dalam Spark untuk mendefinisikan transformasi atau tindakan pada RDD.

awaitTermination: Ini adalah sebuah metode dalam kelas StreamingContext dari Apache Spark yang memblokir eksekusi hingga konteks streaming dihentikan, baik secara manual atau karena adanya exception.

nc: Ini mengacu pada koneksi jaringan atau perintah netcat, yang sering digunakan untuk menjalin koneksi TCP dan mengirim/menerima data melalui jaringan.

lk: Ini bisa merujuk pada sebuah variabel atau singkatan yang spesifik dalam konteks tertentu. Tanpa informasi lebih lanjut, tidak mungkin menentukan arti yang tepat.

spark-submit: Ini adalah sebuah perintah baris yang disediakan oleh Apache Spark yang digunakan untuk mengirimkan aplikasi Spark ke sebuah kluster untuk dieksekusi. Ini mengambil file JAR aplikasi atau skrip Python/Scala sebagai input dan menjalankannya pada kluster.

master: Ini adalah sebuah parameter yang digunakan dalam Apache Spark untuk menentukan URL dari manajer kluster yang akan dihubungi. Ini menentukan mode eksekusi kluster atau lokal untuk aplikasi Spark.

ssc.checkpoint: Ini adalah sebuah metode dalam kelas StreamingContext dari Apache Spark yang mengatur direktori tempat konteks akan menyimpan metadata-nya untuk toleransi kesalahan. Ini memungkinkan pemulihan StreamingContext dari kegagalan.

parallelize: Ini adalah sebuah metode dalam kelas SparkContext dari Apache Spark yang digunakan untuk membuat RDD dengan melakukan paralelisasi dari koleksi yang ada dalam program driver.

updateStateByKey: Ini adalah operasi transformasi dalam Apache Spark Streaming yang diterapkan pada DStream (Discretized Stream) untuk menjaga state (keadaan) antar batch. Ini memungkinkan pembaruan state dari sebuah kunci berdasarkan data baru dan state sebelumnya.

flatMap: Ini adalah operasi transformasi dalam Apache Spark yang diterapkan pada RDD. Ini memetakan setiap elemen input menjadi nol atau lebih elemen
rdd.take(5) :

rdd.take(5): Ini adalah sebuah metode pada RDD di Apache Spark yang mengembalikan sebuah array dengan n elemen pertama dari RDD. Dalam kasus ini, metode ini akan mengembalikan sebuah array dengan lima elemen pertama dari RDD.

transform: Ini adalah sebuah operasi transformasi pada Apache Spark Streaming yang diterapkan pada DStream. Ini memungkinkan Anda untuk menerapkan fungsi RDD-to-RDD yang sembarang pada DStream.

rdd.sortByKey(False): Ini adalah sebuah metode pada RDD di Apache Spark yang mengurutkan elemen-elemen dalam RDD berdasarkan kunci mereka dalam urutan menaik atau menurun. Dalam kasus ini, metode ini akan mengurutkan RDD berdasarkan kunci dalam urutan menurun (False menunjukkan urutan menurun).
