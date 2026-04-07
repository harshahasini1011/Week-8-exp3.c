#include <stdio.h>
int sumArray(int a[], int n) {
int i, sum = 0;
for(i = 0; i < n; i++)
sum += a[i];
return sum;
}
int main() {
int a[5], i;
printf("REG NO: 25331A05c7\n");
printf("enter the elements:");
for(i = 0; i < 5; i++)
scanf("%d", &a[i]);
printf("sum=%d", sumArray(a, 5));
return 0;
}
