# Insertion-sort-project

Project:

[22,27,16,2,18,6] -> Insertion Sort

    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız.
    Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1- Aşamalar

[22, 27, 16, 2, 18, 6]
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27]

## 2- Big-O

Best case: O(n)
Avarage case: O(n^2)
Worst case: O(n^2)

## 3- Time Complexity Case

Sıralandıktan sonra [2, 6, 16, 18, 22, 27] şeklinde olur ve ortada olduğundan Avarage Case olur.

## 4-İlk 4 adım [7,3,5,8,2,9,4,15,6]

[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[2,3,5,7,8,9,4,15,6]
[2,3,4,5,7,8,9,15,6]
