# Veri Yapıları ve Algoritmalar Proje 1,2,3
Bu repoda Patika.dev Kodluyoruz Eğitimi kapsamında yapmış olduğum Proje 1,2 ve 3 bulunmaktadır.


### **PROJE 1** 

**Insertion Sort**

_1. Soru: Verilen [22,27,16,2,18,6] dizisini Insertion Sort algoritmasına göre sıralayınız._

Başlangıç Dizisi: [22,27,16,2,18,6]

1. Adım: [22,27,16,2,18,6] → 22 sıralı kabul edilir.

2. Adım: [22,27,16,2,18,6] → 27 doğru konumda.

3. Adım: [16,22,27,2,18,6] → 16 yerleştirildi.

4. Adım: [2,16,22,27,18,6] → 2 en başa yerleşti.

5. Adım: [2,16,18,22,27,6] → 18 uygun yere yerleşti.

6. Adım: [2,6,16,18,22,27] → 6 doğru yere yerleşti ve sıralama tamamlandı.

Sonuç Dizisi: [2,6,16,18,22,27]

Time Complexity (Big-O):

Worst-case: O(n²)

Average-case: O(n²)

Best-case: O(n)

**Bu örnekte seçilen sayı 18, dizinin orta kısımlarında yerleştiği için Average-case durumuna örnektir.**



**Selection Sort**
_2.Soru: Selection sort algoritmasına göre sıralıyınız._

Başlangıç Dizisi: [7,3,5,8,2,9,4,15,6]

1.Adım: Dizideki en küçük sayı olan 2, ilk eleman 7 ile yer değiştirir:[2,3,5,8,7,9,4,15,6]

2.Adım: Kalan dizideki en küçük sayı 3, zaten doğru yerdedir (değişiklik olmaz):[2,3,5,8,7,9,4,15,6]

3.Adım: Kalan dizideki en küçük sayı olan 4, üçüncü konumdaki 5 ile yer değiştirir:[2,3,4,8,7,9,5,15,6]

4.Adım: Kalan dizideki en küçük sayı 5, 8 ile yer değiştirir:[2,3,4,5,7,9,8,15,6]




### **PROJE 2**
**Merge Sort**

_2. Soru: Verilen [16,21,11,8,12,22] dizisinin Merge Sort algoritmasına göre sıralayınız_

Başlangıç Dizisi: [16,21,11,8,12,22]

Adım: Dizi iki parçaya bölünür: [16,21,11] ve [8,12,22]

Adım: [16,21,11] tekrar ikiye bölünür: [16] ve [21,11]; [8,12,22] ise [8] ve [12,22]

Adım: [21,11] → [11,21] ve [12,22] zaten sıralı.

Adım: [16] ve [11,21] birleşerek [11,16,21] oluşturur.

Adım: [8] ve [12,22] birleşerek [8,12,22] oluşturur.

Adım: Son olarak [11,16,21] ve [8,12,22] birleşerek [8,11,12,16,21,22] dizisini oluşturur ve sıralama tamamlanır.

Sonuç Dizisi: [8,11,12,16,21,22]

Time Complexity (Big-O):

Worst-case: O(nlogn)

Average-case: O(nlogn)

Best-case: O(nlogn)



