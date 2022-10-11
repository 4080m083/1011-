# 1011-C語言

- 作業 C語言
```C 
#include <stdio.h> int main() {
int i = 0;
do { 
printf("%d\n", i);
i++; 
} 
while (i < 5);
return 0; 
}
```



-程式設計題:九九乘法表
```C 
for i in range(1, 10):
    for j in range(1, 10):
        print("%d * %d = %d" % (i, j, i*j))
    print()
```
