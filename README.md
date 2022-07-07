# Veri Yapıları ve Algoritmaları Projesi
## Insertion Sort Projesi
1) [22,27,16,2,18,6] dizinin Insertion Sort medotu ile aşamaları;
İlk önce en küçük eleman bulunur ve en baştaki sayı ile yeri değiştirilir.
* [2,22,27,16,18,6]
* [2,6,22,27,16,18]
* [2,6,16,22,27,18]
* [2,6,16,18,22,27]
2) Big-O gösterimini bulmak için her bir veriyi sıralamak için kaç tane işlem yapıldığına bakmak lazım.
Her bir veride n+(n-1)+(n-2)...+1 tane veri irdelemesi yapacağımdan bu hesap n*(n+1)/2=(n^2+n+)/2 olur.Big-O gösteriminde dominant olan kısım alındığında Big-O gösterimi O(n^2) olur.
3) Dizi sıralandıktan sonra dizinin son hali [2,6,16,18,22,27] olur ve 18 sayısını arar isek 18 sayısı Average case kapsamına girer.
4) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Short'a göre ilk 4 adımı;
* [2,7,3,5,8,9,4,15,6]
* [2,3,7,5,8,9,4,15,6]
* [2,3,4,7,5,8,9,15,6]
* [2,3,4,5,7,8,9,15,6]
## Merge Short Projesi
1) [16,21,11,8,12,22] dizisinin Merge Short türüne göre aşamaları;<br/>
[16,21,11]       [8,12,22]
[16,21] [11]     [8,12] [22]
[16] [21] [11] [8] [12] [22]
[16,21] [8,11] [12,22]
[8,11,16,21] [12,22]
[8,11,12,16,21,22]</br></br>
2) Yukarıdaki her adımda ben kaç tane eleman varsa her adım da O(n) tane işlem yapıyorum. O halde yukarıda yapılan bütün işlem adımlarına x dersem 2^x = n den x=logn olarak gelir.
O halde O(nlogn) olur.
## Binary Search Tree Projesi
Binary Search de verilen verilerin sıralı olduğu varsayımı ile yola çıkıldığından [7,5,1,8,3,6,0,9,4,2] verilmiş diziyi sıralı hale getirelim. [0,1,2,3,4,5,6,7,8,9] bu dizide rootumuzu ortanca sayıya alırsak en az işlemde Binary Search Tree mizi oluşturabileceğimizi düşünüyorum. O yüzden root=4 alalım ve ağacımızı oluşturalım. 
