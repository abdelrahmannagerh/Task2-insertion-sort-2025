# Task2
ترتيب الأرقام بحيث تكون الفردية قبل الزوجية
INSERTION-SORT-ODD-FIRST(A)
for j = 2 to A.length  
key = A[j]  
i = j - 1  
while i > 0 and (A[i] % 2 == 0 and key % 2 == 1)  
A[i + 1] = A[i]  
i = i - 1  
A[i + 1] = key
