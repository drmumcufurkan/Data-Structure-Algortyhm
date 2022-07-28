#Patika-Data-Structure&Algortyhm-Project-2
www.patika.dev
___
##Sorular
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
___
##Cevaplar
___
####1.[16,21,11,8,12,22] -> Merge Sort türüne göre aşamalarının yazılması istenmektedir.
[16,21,11] -[8,12,22]
[16,21] -[11]-[8,12]-[22]
[16] [21] [11] [8] [12] [22]
[16,21]-[11]-[8,12]-[22]
[11,16,21]-[8,12,22]
[8,11,12,16,21,22]
___
###2.Big-O gösterimi
[16,21,11] n/2 -> [16,21] - [11] n/2 -> [16] [21] [11] n-> [16,21]-[11] n-> [11,16,21] n-> [8,11,12,16,21,22]   2^x=n, x= log n & x=n -> O(nlog n)
___