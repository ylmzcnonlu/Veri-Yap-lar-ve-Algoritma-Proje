# Veri-Yap-lar-ve-Algoritma-Proje
Patika kurs sonu veri yapıları ve algoritma projeleri


# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#Dizinin sort türüne göre aşamaları
[2, | 27, 16, 22, 18, 6]
[2, 6, | 16, 22, 18, 27]
[2, 6, 16, | 22, 18, 27]
[2, 6 16 18 ,22, 27]

#Big-o Gösterimi
Worst case: O(n²) = n+(n-1)+(n-2)....+1
Average case: O(n²)
Best case: O(n)

#Time Complexity
Worst case: [27,22,18,16,6,2] (Aradığımız sayının sonda olması)
Best case: [2,6,16,18,22,27]  (Aradığımız sayının dizinin en başında olması)

#Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Verilen dizi küçükten büyüğe sıralandıktan sonra 18 değeri ortanca değer olur ve Average case: Aradığımız sayının ortada olması anlamında
geldiği için cevap average casedir.

#[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

[2|,3,5,8,7,9,4,15,6]
[2,3|,5,8,7,9,4,15,6]
[2,3,4|,8,7,9,5,15,6]
[2,3,4,5|,7,9,8,15,6]
