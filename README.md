# SELECTION-SORT-PROJE

#SORU-1
[22,27,16,2,18,6] -> Insertion Sort Algoritmasına göre aşamalarını yazınız

22 | 27, 16, 2, 18, 6
22, 27 | 16, 2, 18, 6
16, 22, 27 | 2, 18, 6
2, 16, 22, 27 | 18, 6
2, 16, 18, 22, 27 | 6
2, 6, 16, 18, 22, 27 |

Big-O = O(n^2) olarak bulunur, çünkü her adımda dizideki eleman sayısı kadar gezme işlemi yapılır.

Time Complexity, 18 sayısı dizi sıralandıktan sonra ortalarda bulunduğundan time compexity Average Case olarak belirlenebilir.

#SORU-2
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız

2, 3, 5, 8, 7, 9, 4, 15, 6\n
2, 3, 4, 8, 7, 9, 5, 15, 6
2, 3, 4, 5, 7, 9, 8, 15, 6
2, 3, 4, 5, 6, 9, 8, 15, 7


