# Patika_Projeler
## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

### 1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    1)Dizideki en küçük elemanı sırayla bakarak bul.
    2)En küçük elemanı en baştaki eleman ile değiştir.
    3)2. elenamdan başlayarak kalan dizideki en küçük elemanı bul.
    4)En küçük elemanı 2. eleman ile değiştir.
      ..
      işlemleri n-1 elemanına kadar tekrala
    [2,27,16,22,18,6]
    [2,6,16,22,18,27]
    [2,6,16,18,22,27]

### 2- Big-O gösterimini yazınız.

  n + (n-1) + (n-2) ..... + 1 --> (n*(n-1))/2 --> o(n^2)
  
### 3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.


### 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
  Average Case

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    [2,3,5,8,7,9,4,15,6]
    [2,3,4,8,7,9,5,15,6]
    [2,3,4,5,7,9,8,15,6]
    [2,3,4,5,6,9,8,15,7]
