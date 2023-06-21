INSERTION - SORT
[22,27,16,2,18,6] -> Insertion Sort

Soru 1: Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.
Cevap1 :
1)[22|27,16,2,18,6] == n
2)[22,27|16,2,18,6] == n-1
3) 22 ve 27 ,16 dan büyük olduğu için yer değiştiriyor.
[16,22,27|2,18,6] == n-2
4)22,27 ve 16  2'den büyük olduğu için yer değiştirir.
[2,16,22,27|18,6] == n-3
5)22 ve 27 18'den büyük olduğu için  yer değiştiryor.
[2,16,18,22,27|6] == n-4
6)27,22,18,16 büyük olduğu için yer değiştirir.
[2,6,16,18,22,27] == 1

BİG O NOTATION: 
  =n.(n+1)/2
  =(n^2+n)/2
  =O(n^2) dir.

Soru 2:Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Cevap2:
Average case kapsamına girmektedir.

Soru3:[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevap3: 1.adım : [2,3,5,8,7,9,4,15,6] == n
        2.adım : [2,3,5,8,7,9,4,15,6] == n-1
        3.adım : [2,3,4,8,7,9,5,15,6] == n-2
        4.adım : [2,3,4,7,8,9,5,15,6] == n-3
 Dizinin ilk 4 adımı istenildiği için son hali  [2,3,4,7,8,9,5,15,6] dir.
