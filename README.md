  **Question 1:**
  
int main() 
{ 

int number, LD;

printf(" Enter a number"4589);

**ERROR :4589should not be there as it is outside the quotes it will give error**

scanf("%d", &number); 

LD = number / 10; **ERROR: for last digit of a number replace / by %**

printf(" \n The Last Digit of a Given Number %d = %d", number, LD); return 0; 

} 

**Question 3:**

#include <stdio.h> 

int main() 

{

for(int i=1;i <= 4;i--)  

**WILL GO FOR INFINITE LOOP SHOULD BE ++**

{ 

for(int j=1;j <= 4; j++) 

{

if(i != j)

{

printf("*");

} 

else

{

printf(" ");

}

}

printf("\n");

} 

return 0;

} 

**Question4:**

#include <stdio.h> 

void main() { if return value is an integer the function should be of integer type

char a='A'; 

a>10?printf("Yes");:printf("No");    in ? the else condition is given by: not ;: return 0; 
}




