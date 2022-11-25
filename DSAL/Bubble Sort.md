---
aliases: []
tags:
- DSAL
---
# Bubble Sort
- Aktuelles Element mit dem nächsten vergleichen und eventuell Tauschen
- Wenn am Ende angekommen ist das letzte element Sicher das größte
```python
def bubble_sort(A,n):  
	for i in range(n):  
		for j in range(n-1,i,-1):
			if A[j] < A[j-1]:
				swap(j,j-1)
```