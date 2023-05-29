İlk olarak, [22,27,16,2,18,6] dizisinin insertion sort algoritması kullanılarak sıralanması aşamalarını ele alalım.

Dizi: [22, 27, 16, 2, 18, 6] (22 sıralanmış kabul edilir)
Dizi: [22, 27, 16, 2, 18, 6] (27 zaten doğru pozisyonda)
Dizi: [16, 22, 27, 2, 18, 6] (16, 22'nin önüne yerleştirilir)
Dizi: [2, 16, 22, 27, 18, 6] (2, dizinin en başına yerleştirilir)
Dizi: [2, 16, 18, 22, 27, 6] (18, 22'nin önüne yerleştirilir)
Dizi: [2, 6, 16, 18, 22, 27] (6, 16'nın önüne yerleştirilir)
Insertion Sort'un Big-O gösterimi:

En iyi durum (Best Case): O(n)
Ortalama durum (Average Case): O(n^2)
En kötü durum (Worst Case): O(n^2)
Sıralanmış dizi: [2, 6, 16, 18, 22, 27]. 18'in konumu, dizi ortada olduğu için "Average case" kapsamına girer.

Şimdi, [7,3,5,8,2,9,4,15,6] dizisinin selection sort algoritmasına göre ilk 4 adımını ele alalım.

Selection sort algoritması, her adımda en küçük (veya en büyük) elemanı bulup bunu sıradaki doğru pozisyona yerleştirir.

Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] (2 en küçük eleman ve ilk pozisyona yerleştirilir)
Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] (3 zaten doğru pozisyonda)
Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6] (4 bulunup 3. pozisyona yerleştirilir)
Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6] (5 bulunup 4. pozisyona yerleştirilir)
Bu şekilde devam ettiğimizde tüm dizi sıralanmış olur.