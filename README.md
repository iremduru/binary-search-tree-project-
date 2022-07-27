# binary-search-tree-project-

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizininin Binary SearchTree aşamalarını yazınız. # 

! [7,5,1,8,3,6,0,9,4,2] 

 Root'dan büyük sayılar sağa , root'dan küçük sayılar sola yazılır . 
 
 *ROOT = 7 
 
 Tek tek gidelim .
 
5 elemanı root'dan yani 7'den küçüktür . Bu yüzden sola ekleniyor.

              7
             /
            5
           
1 elemanı 7'den küçük. Sola eklenir. 1 elemanı 5'den küçük 5'in soluna ekleniyor. 

              7
             /
            5
           /
          1
         
 8 elemanı 7'den büyük. Sağa ekleniyor.
 
             7
            / \
           5   8
          /
         1   
         
3 elemanı 7'den küçük. Sola ekleniyor . 3 elemanı 5'ten küçük sola ekleniyor.  3 elemanı 1'den büyük 1'in sağına ekleniyor.
  
             7
            / \
           5   8
          /
         1
          \
           3
           
 6 elemanı 7'den küçük. Sola ekleniyor.6 elemanı 5'ten büyük. 5 elemanının sağına ekleniyor.        
           
              7
             / \
            5   8
           / \
          1   6
           \
            3
            
 0 elemanı 7'den küçük. Sola ekleniyor. 0 elemanı 5'ten küçük. 0 elemanı 1'den küçük. 1'in soluna ekleniyor. 
 
              7
             / \
            5   8
           / \
          1   6
         / \
        0   3
        
 9 elemanı 7'den büyük. Sağa ekleniyor. 9 elemanı 8'den büyük. 8'in sağına ekleniyor.  
 
              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
        
 4 elemanı 7'den küçük. Sola ekleniyor.4 elemanı 5'den küçük.4 elemanı 1'den büyük. 1'in sağından devam ediyoruz. 4 elemanı 3'ten büyük. 3'ün sağına ekleniyor.
 
               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
              \
               4

2 elemanı 7'den küçük. Sola ekleniyor.2 elemanı 5'den küçük. Soldan devam ediyoruz. 2 elemanı 1'den büyük. 1'in sağından devam ediyoruz. 2 elemanı 3'ten küçük. 3'ün soluna ekliyoruz ve sonuç.

                                   
               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
            / \
           2   4
           
   http://www.patika.dev/
     
