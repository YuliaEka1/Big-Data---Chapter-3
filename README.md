# TUGAS 4 Experiment Chapter 3

Nama : Yulia Eka Ardhani

Kelas : TI 3C / 21

NIM : 2041720064

## Langkah-langkah praktikum

### I. Uji Coba PySpark

Menjalankan service dari pyspark terlebih dahulu dengan perintah :

<code>cd spark-2.0.0-bin-hadoop2.7</code>

<code>bin/pyspark</code>

![](ss/ss1.png)

1. Uji coba  <code> Accumulator.py </code>
![](ss/ss2.png)

**sc** : singkatan dari SparkContext, ini adalah objek utama dalam pemrograman dengan Apache Spark. Ini digunakan untuk menginisialisasi aplikasi Spark dan membuat RDD (Resilient Distributed Datasets) yang mendukung komputasi paralel.

**accumulator** : objek shared variable yang digunakan dalam Apache Spark untuk agregasi asinkron nilai dari beberapa executor (pekerja) di sepanjang sebuah job (tugas). Biasanya digunakan untuk menghitung statistik yang kompleks atau mengakumulasikan hasil dalam loop.

**parallelize** : method yang digunakan pada objek SparkContext untuk membuat RDD dari koleksi data yang ada dalam program. RDD ini nantinya akan didistribusikan secara paralel pada executor (pekerja) yang tersedia.

**lambda** : fungsi anonim yang sering digunakan dalam pemrograman fungsional dan pemrograman paralel. Biasanya digunakan untuk melakukan operasi yang sederhana dan terbatas pada sebuah data, sehingga sangat cocok untuk dijalankan di dalam RDD.

**value** : tipe data dasar dalam Spark. Ini mewakili nilai tunggal dan dapat berupa tipe data apapun seperti integer, float, string, boolean, atau objek Python. Ini sering digunakan sebagai argument dalam method yang membutuhkan input data seperti map atau reduceByKey.

2. Uji coba <code> BroadCast.py </code>
![](ss/ss3.png)


3. Uji coba <code> LogAnalytics.py </code>
![](ss/ss4.png)
![](ss/ss5.png)

4. Uji coba <code> PairRDD.py </code>
![](ss/ss6.png)

5. Uji coba <code> UnderstandingRDD.py </code>
![](ss/ss7.png)
![](ss/ss8.png)
![](ss/ss9.png)

6. Uji coba <code> WordCount.py </code>
![](ss/ss10.png)
![](ss/ss10_1.png)


### II. Uji Coba Scala

Menjalankan service dari sparkshell terlebih dahulu dengan perintah :

<code>cd spark-2.0.0-bin-hadoop2.7</code>

<code>bin/spark-shell</code>

![](ss/ss11.png)

Jalankan juga service cloudera manager dengan perintah:

<code> sudo /home/cloudera/cloudera-manager --express --force </code>
kemudian login pada browser. Setelah itu, jalankan service HDFS

![](ss/ss12.png)
![](ss/ss13.png)

1. Uji coba <code> SystemCommandsOutput.scala </code>
![](ss/ss14.png)
![](ss/ss15.png)
![](ss/ss16.png)

2. Uji coba <code> SystemCommandsReturnCode.scala </code>
![](ss/ss17.png)
![](ss/ss18.png)

