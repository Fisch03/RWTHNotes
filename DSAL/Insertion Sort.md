---
aliases: []
tags:
- DSAL
---
# Insertion Sort
- Nächstes unsortiertes Element nehmen
- An passende Stelle in Sortierten Array einfügen
```python
def insertion_sort(A,n):  
	for i in range(1,n):
		tmp = A[i]
		j=i
		
	while j>0 and A[j-1] > tmp:
		A[j] = A[j-1]
		j -= 1
		
	A[j] = tmp
```