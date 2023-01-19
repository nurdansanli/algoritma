
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
# Merge short olarak inceleme;
---
[16,21,11,8,12,22]
Yukarıdaki dizinin merge short türüne göre aşamalarını yazınız.
[16,21,11]   [8,12,22]

​[16] [21,11]   [8] [12,22]

[16] [21] [11]   [8] [12] [22]

[16] [11,21]   [8] [12,22]

[11,16,21]   [8,12,22]

[8,11,12,16,21,22]

----------------------------------------

Big-O gösterimini yazınız.

2^x=n    n eleman
x=log(n) 
n*log(n)

O(nlogn) 