#Patika-Data-Structure-Algorithm-Project-1
##www.patika.dev
___
##Sorular
1.[22,27,16,2,18,6]
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
___
##Cevaplar
1.[22,27,16,2,18,6] ->dizisinin Insertion Sort aşamalarının yazılması istenmektedir.
- [2,27,16,22,18,6]=1
- [2,6,16,22,18,27]=2
- [2,6,16,22,18,27]...
- [2,6,16,18,22,27]...(n-1)
- [2,6,16,18,22,27]...(n)
___

2.Big (O) Gösterimi
1+2+3...(n-1)+n=n.(n+1)/2= (n²+n)/2
Worst Case: O(n²) = n+(n-1)+(n-2)....+1

Average Case: O(n²) = n+(n-1)+(n-2)....+1

Best Case: O(n²) = n+(n-1)+(n-2)....+1
____

3.Time Complexity
Tüm Case senaryolarında aynı işlem adedi gerçekleşmesi sebebiyle time complexityleri aynıdır.
____

4.18 Sayısının Case Durumu
Dizi sıralandıktan sonra 18 sayısının hangi case kapsamında girdiğini anlamak için Arama algoritmaları açısından değerlendirilmesi gerekmektedir.Her bir case için kapsamları değişebilecektir.
[2,6,16,18,22,27]
Linear Search açısından değerlendirildiğinde dizinin ortasında olması sebebiyle Avarage Case olarak değerlendirilir.
Binary Search açısından değerlendirildiğinde  ilk işlemde dizinin ortasında bölünecektir.Ancak dizinin indexinin çift sayılı olması nedeniyle ortasında 16 veya 18 sayılarından bölünecektir.
- Bu bölmenin 18 üzerinde gerçekleşmesi halinde Best Case gerçekleşecektir.
- Bu bölmenin 16 üzerinden gerçekleşmesi halinde ise Worst Case olarak gerçekleşecektir.

Binary Search Tree dağılımı oluşturulmadığı için Case açısından değerlendirilemez.
____

5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımının yazılması istenmektedir.

 -  1.[2,3,5,8,7,9,4,15,6]
 -  2.[2,3,5,8,7,9,4,15,6]
 -  3.[2,3,4,8,7,9,5,15,6]
 -  4.[2,3,4,5,7,9,8,15,6]

 ____
