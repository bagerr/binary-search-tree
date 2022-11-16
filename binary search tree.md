Proje 3

Problem

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Çözüm

root ilk eleman olarak 7 yi alıyoruz.

ikinci olarak 5 i 7 (root)'nin soluna yerleştiriyoruz.

üçüncü olarak 1 i 5 in soluna yerleştiriyoruz.

dördüncü olarak 8 i 7 den büyük olduğu için sağına yerleştiriyoruz.

beşinci olarak 3 ü 7 den küçük olduğu gerekçesiyle sol tarafa bakıyoruz ve en altta 1 den büyük olduğu gerekçesiyle sağına atıyoruz.

altıncı olarak 6 yı 5 in sağına atıyoruz

yedinci olarak 0 ı 1 in soluna atıyoruz.

sekizinci olarak 9 u rootdan büyük olduğu için sağına ayrıca 8 den'de büyük olduğu için onunda sağına yerleştiriyoruz.

dokuzuncu olarak 4 ü 3 ün sağına yerleştiriyoruz.

son olarak 2 yi 3 ün soluna yerleştiriyoruz.




                        7                        root satırı

                    /       \

               5               8                1. Düğüm 

            /       \               \

       1              6               9        2. Düğüm 

    /       \
0               3                                3. Düğüm 

            /       \

          2              4                        4. Düğüm 
