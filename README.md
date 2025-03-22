#include <stdio.h>
#include <math.h>
int main() {
  double num, root;
  printf("Enter a number: ");
  scanf("%lf", &num);
  if (num < 0) {
    printf("Cannot calculate square root of a negative number.\n");
  } else {
    root = sqrt(num);
    printf("Square root of %.2lf = %.2lf\n", num, root);
  }
  return 0;
}
