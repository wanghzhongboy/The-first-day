# The-first-day
nothing
#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>
#include <string.h>
int main()
{
char arr1[] = "welcome to bit!!!!!!";
char arr2[] = "####################";\
int left = 0;
int right = atrlen(arr1)-1;
while(left<=right)
  {
  arr2[left] = arr1[left];
  arr2[right] = arr1[right];
  printf("%s\n", arr2);
  left++;
  right--;
  }
return 0;
}
