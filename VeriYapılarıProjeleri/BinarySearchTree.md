Binary Search Tree (İkili Arama Ağacı), her düğümün sol alt ağacındaki tüm değerlerin düğümün değerinden daha küçük, sağ alt ağacındaki tüm değerlerin düğümün değerinden daha büyük olduğu düzenli bir ikili ağaçtır.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisiyle oluşturulan Binary Search Tree aşamalarını şu şekilde belirtebiliriz:

İlk eleman olan 7, root (kök) düğüm olur.
5, root'tan küçük olduğu için sol alt ağaca eklenir.
1, 5'ten küçük olduğu için 5'in sol alt ağacına eklenir.
8, root'tan büyük olduğu için sağ alt ağaca eklenir.
3, 5'ten küçük ancak 1'den büyük olduğu için 1'in sağ alt ağacına eklenir.
6, root'tan küçük ancak 5'ten büyük olduğu için 5'in sağ alt ağacına eklenir.
0, 1'den küçük olduğu için 1'in sol alt ağacına eklenir.
9, root'tan ve 8'den büyük olduğu için 8'in sağ alt ağacına eklenir.
4, 5'ten küçük ancak 3'ten büyük olduğu için 3'in sağ alt ağacına eklenir.
2, 3'ten küçük ancak 1'den büyük olduğu için 1'in sağ alt ağacına eklenir.
Bu işlemlerin sonucunda aşağıdaki gibi bir Binary Search Tree oluşur:

        7
       / \
      5   8
     / \   \
    1   6   9
   / \   \   
  0   3   4 
     /
    2

Burada root 7'dir. 7'nin sağından 8 bulunur, solunda ise 5 bulunur. 5'in sağından 6 bulunur, solunda 1 bulunur. Bu şekilde devam eder.