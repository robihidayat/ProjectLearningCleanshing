
Saat kalian membuka file dengan python, kalian tidak perlu mengimport library apapun.
kenapa ? karena sudah dihandle secara native oleh bahasa ini. meskipun dengan cara yang unik.

pertama kalian akan membutuhkan function build in "open" dari bahasa python untuk membuat object file,
fucntion open kemudian membuka file tersebut.

saat kalian menggunakan function open, return value nya disebut sebagai file object.
file object mengandung metode dan atribut yang dapat digunakan untuk mengumpulkan informasi dari file yang kamu buka.
nah function ini juga bisa digunakan untuk memanipulasi file.

####bagaimana caranya ?
mudah sekali. bisa dicoba.
sumber: http://www.pythonforbeginners.com/files/reading-and-writing-files-in-python

>file_object = open('sample.txt','r')

>print file_object.read()

Program diatas adalah untuk membuka file dengan metode function open.
untuk bisa dapat membaca file, metode yang bisa dipakai adalah read.

