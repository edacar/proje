# proje
[22,27,16,2,18,6]
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
 [22,27,16,2,18,6] 22<27?Yes. The first two elements are already in ascending order.
1.[22,27,16,2,18,6] 27<16?No. 22<16?No.
2.[16,22,27,2,18,6] 27<2?No. 22<2?No. 16<2?No.
3.[2,16,22,27,18,6] 27<18?No. 22<18?No. 16<18?Yes. 2<18?Yes.
4.[2,16,18,22,27,6] 27<6?No. 22<6?No. 18<6?No. 16<6?No. 2<6?Yes.
5.[2,6,16,18,22,27].
2. Big-O gösterimini yazınız.
1+2+...n-1=(n-1)*n/2: O(n^2).
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Worst case = O(n^2)
Average case = O(n^2)
Best case = O(n).
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average case.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1.[3 7] 5 8 2 9 4 15 6 
2.[3 5 7] 8 2 9 4 15 6
3.[3 5 7 8] 2 9 4 15 6
4.[2 3 5 7 8] 9 4 15 6
