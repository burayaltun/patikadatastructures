# Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Insertion Sort:
[22,27,16,2,18,6]:
1.[22,27,16,2,18,6]
2.[22,16,27,2,18,6]
3.[16,22,27,2,18,6]
4.[16,22,2,27,18,6]
5.[16,2,22,27,18,6]
6.[2,16,22,27,18,6]
7.[2,16,22,18,27,6]
8.[2,16,18,22,27,6]
9.[2,16,18,22,6,27]
10.[2,16,18,6,22,27]
11.[2,16,6,18,22,27]
12.[2,6,16,18,22,27]

Big o-notation:
n*(n+1)/2 = (n^2+n)/2
Big O(n^2)

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]:
1.[2,3,5,8,7,9,4,15,6]
2.[2,3,4,8,7,9,5,15,6]
3.[2,3,4,5,7,9,8,15,6]
4.[2,3,4,5,6,9,8,15,7]

Merge Sort:
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


                               [16,21,11,8,12,22]
                       
                      {16,21,11}                         {8,12,22}
           
               {16}           {21,11}                {8}          {12,22}
                
       {16}              {21}         {11}        {8}           {12}        {22}
       
          {16}              {11,21}               {8}            {12,22}
          
                 {11,16,21}                                {8,12,22}
                 
                                   {8,11,12,16,21,22}
                                   
Big O gösterimi : O(nlogn)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.



Root'u 7 kabul edersek:



                              7
                       /             \
                    5                  8
                /       \                \            
              1          6                  9
            /   \
           0      3
                /    \
               2      4