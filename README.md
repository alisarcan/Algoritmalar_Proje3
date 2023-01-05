# PROJE-3
--------------------------------------------------------------------------------------
Binary Search Tree
[7,5,1,8,3,6,0,9,4,2] 

6'yı Root Node olarak alalım.

             6         1.Adım 7>6 sağa yazılır.  5<6 sola yazılır.
            
           5  7        2.adım 1<6 ve 1<5 sola yazılır.  8>6 ve 8>7 sağa yazılır.
          
         1      8      4.adım 3<6 ve 3>1 sağa yazılır.  0<6, 0<5, 0<1 sola yazılır.
        
       0    3     9    7.adım 9>6, 9>7, 9>8 sağa yazılır.
    
           2  4        8.adım 4<6, 4<5, 4>1, 4>3 sağa yazılır. 
           
                       9.adım 2<6, 2<5, 2>1, 2<3 sola yazılır.