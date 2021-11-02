 ****2ND YEAR****
 ***TASK 1***
  
  ERRORS ARE  WRITEN IN  BOLD
  
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


**Question 2:**

int sumcal(int len, int* arr, int value) 

{ 

int sum = 0; 

for(int i =0 ; i< len-1; i++ ) 

{ 

if(arr[i]%value == 0) 

sum =+ arr[i]; **ERROR SHOULD BE(sum =arr[i]) 

} 

return sum; 

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

class test{ 

int my_variable; 

} **ERROR should be a semicolun(;) after defining a class**

int main() { 

test code_chef; 

cin>>code_chef.my_variable; 

if(code_chef.my_variable%2==0){ cout<<"Even"; 

} 

else{ 

cout<<odd; **Error SHOULD BE (cout<<"odd";) as odd is a string

} 

return 0; 

}


**Question8:**

using namespace std **ERROR THERE SHOULD BR A SEMICOLUN AT THE END;**

void printSums(int N)

{

int start=1, end=(N+1)/2;

while (start<end)

{

int sum=0;

for (int i=start;i<=end;i++)

{

sum=+i;

if (sum == N)

{

for (j=start,j<=I,j++) **ERROR SHOULD BE(for(int j=start;j<=i;j++){) J WAS NOT DECLARED and I should be small and semicolun not given in for statement also no starting brackets **

cout<<j<<" ";

cout<<"/n";

break;

}

if (sum>N)

break **ERROR SHOULD END WITH SEMICOLUN**

}

sum=0;

start++;

}

}

int main()

{

int n;

cin>>n;

printsums(n);

return 0;

}


**Question9:**


using namespace std;

int main() {

int length

cout<<enter the length of the array"<<endl; **ERROR NO STARTING (") in the  Statement

cin>>length;

int array(length];**ERROR BRACKETS DO NOT MATCH"

for(int i=0;i<length;i++){

cin>>array[i];

}

int min=array[0];max=array[0];

for(int i=1;i<length;i++){

if(array[i]>max)

max = array[i];

else if(array[i]<<min)

min = array[i];

}

cout<< min<<" "<<max;

return std;

}


**Question10:**

*include <string.h>**ERROR SHOULD BE (#include >string.h>

 main() **ERROR no Return Value given**

{ 

int t,i,diff_count; 

scanf("%d";&t) **ERROR SHOULD BE(scanf("%d,&t);)**

char s[100001], **ERROR STATEMENT SHOULD END WITH A SEMICOLON**

while(t+-){ **ERROR SHOULD BE EITHER(t++ or t--)**

diff_count=0; 

scanf("%s",s); 

for(int i=0;i<strlen(s)-1;i++){ 

if(s[i]===s[i+1])**ERROR SHOULD BE == FOR COMPARING VALUES**

diff_count++; 

} 

printf("%d\n",diff_count); 

return 0; 

} **ERROR NO OF BRACKETS DO NOT MATCH SHOULD BE ON MORE } **




***TASK2***






 
 















