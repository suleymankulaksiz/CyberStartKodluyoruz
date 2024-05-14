Soru 1 => [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.



Cevap 1 =>
          [16,12,11] - [8,12,22] -  3  gruba ayırılır.

          [16] - [21,11] - [8,12] - [22] -  16 ve 22 tek kalanlar çift gruplara ayrılır.

          [16] - [21] - [11] - [8] - [12] - [22] - tekerli gruplara ayırana kadar bunu tekrar et.

          [16] - [11,21] - [8,12] - [22] - 2. adımdaki işlem tekrarla

          [11,16,21] - [8,12,22] - tekli gruplar küçükten büyüğe şeklinde gruplara dahil edilir.

          [8,11,12,16,21,22] - Küçükten büyüğe olacak şekilde sırala ve bitir.






Soru 2 =>Big-O gösterimini yazınız



Cevap 1 =>2^x=n = O(nlogn)



