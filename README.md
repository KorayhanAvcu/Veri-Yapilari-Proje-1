# Veri-Yapilari-Proje-1


### Selection Sort
### Soru 1
```
[7,3,5,8,2,9,4,15,6] 
```
dizisinin Selection Sort'a göre ilk 4 adımını yazınız. <br>

Cevap: <br>

```
Step 1: 
	
	[2,3,5,8,7,9,4,15,6]

Step 2:
	[2,3,4,8,7,9,5,15,6]

Step3: 
	[2,3,4,5,7,9,8,15,6]

Step 4: 
	[2,3,4,5,6,9,8,15,7]

Step 5: 
	[2,3,4,5,6,7,8,15,9]

Step 6:
	[2,3,4,5,6,7,8,9,15]
```

### Insertion Sort
### Soru 2
```
[22,27,16,2,18,6]
```
a-) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. <br>
Cevap: <br>
```
Step 1: 
	[22,27,16,2,18,6] // 22, 27'den küçük olduğundan yer değişimi olmadı.
Step 2:
	[22,16,27,2,18,6] //27 ile 16 yer değiştirdi.
Step 3:
	[16,22,27,2,18,6] //22 ile 16 yer değiştirdi.
Step 4:
	[16,22,2,27,18,6] //27 ile 2 yer değiştirdi.
Step 5:
	[16,2,22,27,18,6] //2 ile 22 yer değiştirdi.
Step 6:
	[2,16,22,27,18,6] //2 ile 16 yer değiştirdi.
Step 7:
	[2,16,22,18,27,6] //18 ile 27 yer değiştirdi.
Step 8:
	[2,16,18,22,27,6] //18 ile 22 yer değiştirdi.
Step 9:
	[2,16,18,22,6,27] //6 ile 27 yer değiştirdi.
Step 10:
	[2,16,18,6,22,27] //6 ile 22 yer değiştirdi.
Step 11:
	[2,16,6,18,22,27] //6 ile 18 yer değiştirdi.
Step 12:
	[2,6,16,18,22,27] //6 ile 16 yer değiştirdi.
```
b)Big-O gösterimini yazınız. <br>
Cevap: <br>
```
O(n^2)
```
c) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız <br>
Cevap: <br>
```
Average case
```
