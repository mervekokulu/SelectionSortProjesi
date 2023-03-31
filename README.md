# Selection Sort Projesi
Patika.dev-Veri Yapıları ve Algoritmalar-Selection Sort Projesi


Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# ÇÖZÜM

1. Dizinin en küçük elemanı bulunur ve dizinin en başındaki eleman ile yer değiştirilir -> [2,27,16,22,18,6]
2. İkinci en küçük eleman bulunur ve 2. sıra ile yer değiştirilir -> [2,6,16,22,18,27]
3. Üçüncü en küçük sayı doğru yerde olduğu için dördüncü eleman için de aynı işlemler yapılır ve dizinin son sıralanışı şu şekildedir -> [2,6,16,18,22,27]

Big-O gösterimi O(n^2) şeklindedir.

18 sayısı, Average case kapsamına girmektedir.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
5. [2,3,4,5,6,7,8,15,9]
6. [2,3,4,5,6,7,8,9,15]
