---
aliases: []
tags:
- DSAL
---
# Selectionsort
- kleinstes / größtes Element suchen
- an die erste  (unsortierte) Stelle kopieren

```python
def selection_sort(A,n):  
	for i in range(n):  
		min = i
		for j in range(i+1,n):
			if A[j] < A[min]:
				min = j
				
		swap(i,min)
```