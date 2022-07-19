# Insertion-Sort-Projesi
www.patika.dev


Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


# 1- Insertion Sort Aşamaları

  [22,27,16,2,18,6]
  
  [2,|22,27,16,18,6]
  
  [2,6,|22,27,16,18]
  
  [2,6,16,|22,27,18]
  
  [2,6,16,18,|22,27]
  
  [2,6,16,18,22,|27]
  
  [2,6,16,18,22,27]


# 2- Big O Notation Gösterimi

  O (n^2)
  
# 3- Time Complexity

  Average Case: [18,22,27,2,6,16]
  Worst Case: [27,22,18,16,6,2]
  Best Case: [2,6,16,18,22,27]

# 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
  
  [2,6,16,18,22,27] : 18 sayısı tam ortada olduğu için avarege case kapsamına girer.
  

# 5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

  1- [2,|7,3,5,8,9,4,15,6]
  2- [2,3,|7,5,8,9,4,15,6]
  3- [2,3,4,|7,5,8,9,15,6]
  4- [2,3,4,5,|7,8,9,15,6]


















