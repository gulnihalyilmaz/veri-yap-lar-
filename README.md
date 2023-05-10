# veri yapilari
sorting uygulamaları

## soru 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

## cevap 1  

--> öncelikle en küçük elemanı bulup ardından kalan (n-1) tane elemanı karşılaştırarak sıralayacak.

- [2, 22, 27, 16, 18, 6]
- [2, 22, 16, 27, 18, 6]
- [2, 16, 22, 27, 18, 6]
- [2, 16, 22, 18, 27, 6]
- [2, 16, 18, 22, 27, 6]

--> ardından 6 da tek tek elemanları geçerek şu şekli alacaktır;
- [2, 6, 16, 18, 22, 27]


## soru 2
Aynı dizinin Big-O gösterimini yazınız.

## cevap 2

--> [n (n+1)] / 2 ile açılım yaptığımızda elde ettiğimiz şey (n^2 +n) / 2 olacaktır ve belirleyici olan n^2 olacaüo için cevap
O(n^2) 'dir. 

## soru 3 
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

## cevap 3
--> 18 sayısı Avarage case kapsamındadır.

## soru 4
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## cevap 4
--> Selection sort algoritmasında ilk eleman en küçük kabul edilir, ardından ondan küçüğü gelene kadar elemanlar karşılatırılır, geldiğinde ise yer değiştirilir.
- [2, 3, 5, 8, 7, 9, 4, 15, 6]
- [2, 3, 4, 8, 7, 9, 4, 15, 6]
- [2, 3, 4, 5, 7, 9, 8, 15, 6]
- [2, 3, 4, 5, 6, 9, 8, 15, 7]
