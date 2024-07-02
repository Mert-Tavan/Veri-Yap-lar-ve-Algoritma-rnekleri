Proje 1
  [22,27,16,2,18,6] -> Insertion Sort
  
  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  
  Big-O gösterimini yazınız.
  
  Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
  
  Average case: Aradığımız sayının ortada olması
  Worst case: Aradığımız sayının sonda olması
  Best case: Aradığımız sayının dizinin en başında olması.
  
  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Proje 1 Çözüm

  ----Insertion Sort 
  Step1: 22 | 27 16 2 18 6
  Step2: 22 27 | 16 2 18 6
  Step3: 16 22 27 | 2 18 6
  Step4: 2 16 22 27 | 18 6
  Step5: 2 16 18 22 27 | 6
  Step5: 2 6 16 18 22 27 |
  no need to swap -> 2 6 16 18 22 27 

  ----Big O
  n+(n-1)+(n-2)...1 = n.(n+1)/2 = n^2+n/2 => O(n^2)
  Average case

  ----Selection Sort 
  Step1: 7,3,5,8,2,9,4,15,6
  Step2: 2,3,5,8,7,9,4,15,6
  Step3: 2,3,4,8,7,9,5,15,6
  Step4: 2,3,4,5,7,9,8,15,6


Proje 2
  [16,21,11,8,12,22] -> Merge Sort
  
  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
  Big-O gösterimini yazınız.


Proje 2 Çözüm
  
  1 :                 [16,21,11,8,12,22]                          
  2 :         [16,21,11]                [8,12,22]
  3 :       [16,21]   [11]            [8,12]    [22]
  4 :      [16]  [21]  [11]          [8]  [12]  [22]
  5 :       [16,21]  [11]             [8,12]  [22]
  6 :         [11,16,21]                [8,12,22]
  7 :                 [8,11,12,16,21,22]

  O(nlogn)

Proje 3
  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
  
  Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


Proje 3 Çözüm

  root: 7 
                         
                         7
                       /   \            
                      5      8
                    /   \      \        
                  1       6      9 
                /   \    
               0     3
                    /  \
                   2    4
