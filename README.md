# Insertion-Sort-Projesi
## Proje 1
[22,27,16,2,18,6] -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    1) [22,27,16,2,18,6]
    2) [2,27,16,22,18,6]
    3) [2,6,16,22,18,27]
    4) [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.
    
    Worst Case : O(n^2)
    Best Case : O(n)
    Average Case : O(n^2)

3. Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, 
    Best case: Aradığımız sayının dizinin en başında olması.

    Average Case : [22,27,2,16,18,6]
    Worst Case : [22,27,16,18,6,2]
    Best Case : [2,6,16,18,22,27]

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

```
Dizi sıralandıktan sonra 18 sayısının ortada olmasından dolayı Average Case kapsamına girer.

```

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

       [7,3,5,8,2,9,4,15,6]
    1. [3,7,5,8,2,9,4,15,6]
    2. [3,5,7,8,2,9,4,15,6]
    3. [3,5,7,8,2,9,4,15,6]
    4. [2,3,5,7,8,9,4,15,6]