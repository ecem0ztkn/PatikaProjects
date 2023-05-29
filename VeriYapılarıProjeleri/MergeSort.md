[16,21,11,8,12,22] dizisi için Merge Sort adımları:

-Dizi: [16,21,11,8,12,22] (Diziyi ikiye böl)
-Diziler: [16,21,11] ve [8,12,22]
-Diziyi tekrar ikiye böl: [16], [21,11] ve [8], [12,22]
-Diziyi tekrar ikiye böl: [16], [21], [11] ve [8], [12], [22]
-Şimdi, bu tek elemanlı dizileri sıralayarak birleştirme adımına geçeriz: [16,21], [11] ve [8,12], [22]
-Dizileri tekrar birleştir: [11,16,21] ve [8,12,22]
-Son adımda tüm diziyi birleştirir ve sıralarız: [8,11,12,16,21,22]
Merge Sort'un Big-O gösterimi:

En iyi durum (Best Case): O(n log n)
Ortalama durum (Average Case): O(n log n)
En kötü durum (Worst Case): O(n log n)