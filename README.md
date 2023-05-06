# Selection-Sort-Proje
Veri yapıları ve Algoritmalar-Proje1
[22,27,16,2,18,6] n 
[2,27,16,22,18,6] n-1 
[2,6,16,22,18,27] n-2 
[2,6,16,18,22,27] n-3

Big-O gösterimi:
n+(n-1)+(n-2)+n-3)+(n-4)+1=[n.(n+1)]/2=(n^2+n)/2===>O(n^2)

18 sayısına erişmek ise averge case kapsamına girer çünkü [2,6,16,18,22,27] son hali bu şekilde olduğu için 18 sayısı ortada yer alır.

 [7,3,5,8,2,9,4,15,6] En küçük sayı 2 en sola yazıldı... ardından küçükler aynı mantık ile dizildi.
1==>[2,3,5,8,7,9,4,15,6]
2==>[2,3,4,8,7,9,5,15,6]
3==>[2,3,4,5,7,9,8,15,6]
4==>[2,3,4,5,6,9,8,15,7]

------------------- Proje 2------------------------

[16, 21, 11], [8, 12, 22]
[16], [21, 11], [8], [12, 22]
[16], [11, 21], [8], [12, 22]
[11, 16, 21], [8, 12, 22]
[8, 11, 12, 16, 21, 22]

