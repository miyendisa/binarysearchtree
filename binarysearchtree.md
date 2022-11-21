>**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

Verilen dizide root 7 olarak seçilsin. Veriyi sağ ve sola referans verecek şekilde seçeriz. Root'un sağında rootdan daha büyük olan sayı, solundan ise küçük olan sayı bulunur.

* Dizinin ikinci elemanı olan 5, 7'den küçüktür. Dolayısıyla, 1. düğüm satırında 5, root olarak belirlenen 7'nin sol tarafında olacaktır.
  
                                    4            Root Satırı
                                      \ 
                                        7        1. Düğüm Satırı
* Dizinin ikinci elemanı olan 5, 4'ten büyüktür ancak 7'den küçüktür. Dolayısıyla, 2. düğüm satırında 7'nin sol tarafında yer alacaktır.
  
                                    4            Root Satırı
                                      \ 
                                        7        1. Düğüm Satırı
                                       /
                                      5          2. Düğüm Satırı    
                                    
                                    
* Dizinin üçüncü elemanı olan 1, 4'ten büyüktür ancak 7'den küçüktür. Dolayısıyla, 1. düğüm satırında 4'ün sol tarafında yer alacaktır.
  
                                    4            Root Satırı  
                                  /   \  
                                 1     7         1. Düğüm Satırı                 
                                      /
                                    5          2. Düğüm Satırı 
* Dizinin dördüncü elemanı olan 8, 4'ten büyüktür. 8, 7'den de büyük olduğu için 2. düğüm satırında 7'nin sağ tarafında bulunacaktır.
  
                                    4            Root Satırı  
                                  /   \  
                                 1     7         1. Düğüm Satırı                 
                                      / \
                                     5   8       2. Düğüm Satırı 
* Dizinin beşinci elemanı olan 3, 4'ten küçüktür. 3, 1'den de büyük olduğu için 2. düğüm satırında 1'in sağ tarafında bulunacaktır.
  
                                4              Root Satırı
                             /      \  
                           1          7        1. Düğüm Satırı
                            \       /   \
                              3    5      8    2. Düğüm Satırı            
* Dizinin altıncı elemanı olan 6, 4'ten büyüktür. 6, 8'den küçük olduğu için 3. düğüm satırında 8'in sol tarafında bulunacaktır.
  
                                4              Root Satırı
                             /      \  
                           1          7        1. Düğüm Satırı
                            \       /   \
                              3    5      8    2. Düğüm Satırı
                                         /  
                                        6      3. Düğüm Satırı  
                                    
* Dizinin yedinci elemanı olan 0, 4'ten küçüktür. 0, 1'den de küçük olduğu için 2. düğüm satırında 1'in sol tarafında bulunacaktır.
  
                                4              Root Satırı
                             /      \  
                           1          7        1. Düğüm Satırı
                          /  \      /   \
                         0    3    5      8    2. Düğüm Satırı
                                         /  
                                        6      3. Düğüm Satırı     

 * Dizinin sekizinci elemanı olan 9, 4'ten büyüktür. 9, 8'den de büyük olduğu için 3. düğüm satırında 8'in sağ tarafında bulunacaktır.
  
                                4                Root Satırı
                             /      \  
                           1          7          1. Düğüm Satırı
                          /  \      /   \
                         0    3    5      8      2. Düğüm Satırı
                                         /  \  
                                        6     9  3. Düğüm Satırı     

* Dizinin son elemanı olan 2, 4'ten küçüktür. 2, 0'dan da büyük olduğu için 3. düğüm satırında 0'ın sağ tarafında bulunacaktır.
  
                                4                Root Satırı
                             /      \  
                           1          7          1. Düğüm Satırı
                          /  \      /   \
                         0    3    5      8      2. Düğüm Satırı
                          \              /  \  
                           2            6     9  3. Düğüm Satırı     
