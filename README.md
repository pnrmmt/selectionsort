# Veri Yapıları ve Algoritmalar
## Proje 1
## Selection Sort Projesi

 [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


```
[22,27,16,2,18,6]
[16,22,27,2,18,6] 
[2,16,22,27,18,6] 
[2,16,18,22,27,6] 
[2,6,16,18,22,27] 

```

- Big-O gösterimini yazınız.
```
Elde ettiğimiz sıralı dizinin Big-O gösterimi O(n^2) şeklindedir.
```

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

```
18 sayısı sıralı dizide 4. eleman olduğu için awarage case kapsamına girer.
```

- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[2|3,5,8,7,9,4,15,6] 1.adım

[2,3,4|8,7,9,5,15,6] 2.adım

[2,3,4,5|7,9,8,15,6] 3.adım

[2,3,4,5,6|9,8,15,7] 4.adım

```