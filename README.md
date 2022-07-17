# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2-Big-O gösterimini yazınız.

## 1- Merge Sort Aşamaları
[16,21,11,8,12,22] ilk önce sayı dizisini ikiye böleriz.

- [16,21,11]     [8,12,22]
 böldüğümüz dizileri bir daha ikiye bölüyoruz.

- [16,21]   [11]   [8,12]   [22]
dizimizin şuan ki halinde tekli dizilere ayrıldığı için artık dizilerimizin içinde bulunan sayıları uygun bir şekilde küçükten büyüğe doğru sıralıyoruz.

- [11,16,21]   [8,12,22]
Son adımdan bir önce ki adımda dizimiz bu şekle dönüşüyor

- [8,11,12,16,21,22]
Ve dizi sıralı hale gelir.

## 2- Big O Notation Gösterimi
Worst case   : O(n*logn)

Average case : O(n*logn)

Best case    : O(n*logn)

# [Patika.dev](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)