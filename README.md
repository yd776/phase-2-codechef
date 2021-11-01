  ***TASK 1***
  
  ERRORS ARE MARKED IN BOLD
  
  **Question 1:**
  
int main() 
{ 

int number, LD;

printf(" Enter a number"4589);

**ERROR :4589 should not be there as it is outside the quotes it will give error**

scanf("%d", &number); 

LD = number / 10; **ERROR: for last digit of a number replace / by %**

printf(" \n The Last Digit of a Given Number %d = %d", number, LD); return 0; 

} 

**Question 3:**

#include <stdio.h> 

int main() 

{

for(int i=1;i <= 4;i--)  

**ERROR WILL GO FOR INFINITE LOOP SHOULD BE ++**

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

void main() { **ERROR if return value is an integer the function should be of integer type**

char a='A'; 

a>10?printf("Yes");:printf("No");    **ERROR in ? the else condition is given by: not ;: return 0;** 

}

**Question5:**

int main() { 

int o; i; s;   **ERROR SHOULD BE (int o,i,s;) to declare multiple variables of same data type we need to use commas between them**

for(o=5; o>=1; o--) 
{ 

for(s=1 s<=5-o s++) **ERROR SHOULD BE (for(s=1;s<=5;s++)) in for loop to give conditions we need to separate by ;**

cout<<" "; 

for (i=1 i<=o i++){ 

cout>>"*";} **ERROR SHOULD BE (cout<”*”;)} the cout<<operator is << not>>**

cout<<endl; 

}}} }} **ERROR EXTRA } should be only 2}}**

**Question6:** 

z=int(“Enter a number:”) **ERROR Input not taken from user**

for in range [0,9]:  **ERROR variable x not declared in loop**

if z=x:  **ERROR should be (z==x) since we are comparing values**

print(“They are equal”); 

else: 

print(“They are not equal”) 

**Question 7**

 
 















