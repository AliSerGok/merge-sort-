
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

 n:0               [16,21,11,8,12,22]
 n:1            [16,21,11]    [8,12,22]
 n:2        [16]	[21,11]				[8,12]	[22]
 n:3      [16]  [21]  [11]    [8]  [12]  [22]
 n:4       [16]  [11,21]				[8,12]	[22]
 n:5         [11,16,21]				[8,12,22]
 n:6             [8,11,12,16,21,22]


Big-O gösterimini yazınız.

kademe sayısı 2^x=n ==> logn=x
her kademede yapılan işlem sayısı dizi sayısı kadardır yani n kadardır.
nlogn = toplam işlem sayısı
O(nlogn)
