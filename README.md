INSERTION - SORT
[22,27,16,2,18,6] -> Insertion Sort <br>

Soru 1: Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.<br>

Big-O gösterimini yazınız.<br>
Cevap1 :<br>
1)[22|27,16,2,18,6] == n    <br>
2)[22,27|16,2,18,6] == n-1   <br>
3) 22 ve 27 ,16 dan büyük olduğu için yer değiştiriyor.<br>
[16,22,27|2,18,6] == n-2  <br>
4)22,27 ve 16  2'den büyük olduğu için yer değiştirir.<br>
[2,16,22,27|18,6] == n-3   <br>
5)22 ve 27 18'den büyük olduğu için  yer değiştiryor. <br>
[2,16,18,22,27|6] == n-4 <br>
6)27,22,18,16 büyük olduğu için yer değiştirir.<br>
[2,6,16,18,22,27] == 1  <br>

BİG O NOTATION: <br>
  =n.(n+1)/2 <br>
  =(n^2+n)/2  <br>
  =O(n^2) dir.<br>

Soru 2:Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız. <br>

Average case: Aradığımız sayının ortada olması <br>
Worst case: Aradığımız sayının sonda olması  <br>
Best case: Aradığımız sayının dizinin en başında olması.<br><br>

Cevap2:<br>
Average case kapsamına girmektedir.<br>

Soru3:[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.<br>

Cevap3:<br>
        1.adım : [2,3,5,8,7,9,4,15,6] == n  <br>
        2.adım : [2,3,5,8,7,9,4,15,6] == n-1 <br>
        3.adım : [2,3,4,8,7,9,5,15,6] == n-2 <br>
        4.adım : [2,3,4,7,8,9,5,15,6] == n-3 <br>
 Dizinin ilk 4 adımı istenildiği için son hali  [2,3,4,7,8,9,5,15,6] dir.
