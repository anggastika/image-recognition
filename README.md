
## *Requirements*
Program ini menggunakan bahasa pemrograman Python versi 2.7 dan ditulis dalam struktur *Object Oriented Programming* (OOP). Tujuan dikembangkan dalam struktur OOP yaitu supaya mempermudah pembacaan program dengan membagi kedalam modul-modul/kelas. Program ini dikembangkan dalam sistem operasi Linux.

Jika baru menginstal python, instal ```python-pip``` dan ```python-dev``` dahulu untuk mempermudah menginstal library-library yang dibutuhkan selanjutnya.
```sh
$ sudo apt-get install python-pip python-dev
```
Instal OpenCV pada python, tutorial buka link ini ->
[Install OpenCV](http://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/)

Jika menggunakan MacOS:
```sh
$ brew install opencv3
```

Instal library yang dibutuhkan yaitu: ```numpy```, ```scikit-image```, ```matplotlib``` (untuk plot *hyperplane* pada SVM), ```cvxopt``` (untuk operasi matriks dan masalah optimasi pada SVM):
```
$ sudo pip install numpy
$ sudo pip install scikit-image
$ sudo pip install matplotlib
$ sudo pip install cvxopt
```
Jalankan program:
```sh
$ python start.py
``` 
atau bisa juga (jika menggunakan Terminal Linux):
```sh
$ ./start.py
```
Jika masih terdapat error, instal library lain yang muncul di pesan error tersebut pada python:
```sh
$ sudo pip install [nama library]
```


