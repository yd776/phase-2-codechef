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


**Q1:**
Given a group of words, rearrange them in alphabetical order on the basis of their fourth alphabet. Take the last letter into consideration if the word contains less than 4 

characters. Minimum word length would be of two characters. 

ans)

LINK TO PROGRAM

https://onlinegdb.com/hfS8MAK-2p

LANGUAGE USED PYTHON 3

CODE

n=int(input())

words=[]

for i in range(n):

    string=""
    
    string=str(input())
    
    if len(string)>4:
        
        string=string[3]+string
    
    else:
        
        string=string[-1]+string
    
    words.append(string)

words=sorted(words)   

for i in range(n):
    
    words[i]=words[i][1:]

for i in range(n)   : 
    
    print(words[i])




**Q2:**
Given an array arr[] and an integer K where K is smaller than the size of the array, the task is to find the Kth smallest element in the given array. It is given that all 
 
array elements are distinct. Check if kth element is a prime number or not. 

Input: size of array = 5 

Array [] = 7 10 4 5 2 

Kth element = 4 



ans)

LINK TO PROGRAM

https://onlinegdb.com/tHydzE2rK


LANGUAGE USED C++

CODE



#include <iostream>

using namespace std;
 
int main ()

 {
 
 int n;
 
 cout<<"PLEASE ENTER SIZE OF ARRAY";
 
 cout<<"\n";
 
 cin>>n;
 
 int arr[n];
 
 cout<<"ENTER THE ARRAY ELEMENTS";
 
 cout<<"\n";
 
 for(int i=0;i<n;i++){
 
   cin>>arr[i];
 
 }
 
 int counter=1;
 
 while(counter<n){
 
      for(int i=0;i<n-counter;i++){
         
 if(arr[i]>arr[i+1]){//using bubble sort as the list is unsorted
            
 int temp=arr[i];
             
 arr[i]=arr[i+1];
             
 arr[i+1]=temp;
 
 }
 
 }
 
 counter++;
 
 }
 
 int k;
 
 cout<<"please enter k value";
 
 cout<<"\n";
 
 cin>>k;

 cout<< "kth smallest value is ";
 
 cout<<arr[k-1];
 
 cout<<"\n";
 
 int l;
 
 
 l=arr[k-1];
 
 if (l==0 ||l== 1) {
 
 cout<<"THE KTH ELEMENT IS NOT PRIME";
 
 }
 
 else {
 
 for (int i = 2; i <= l / 2; i++) {
 
                      if (l % i == 0) {
                
                      cout<<"THE KTH ELEMENT IS NOT PRIME";
                
                             break;
            
                             }
         
                             cout<<"THE KTH ELEMENT IS PRIME";
        
 }
   
 }
  
 return 0;

 }
 
 
 
 **Q3**
 
 
 
 Q3: Rajesh is a 5 year old kid who is practising the alphabet. He is really confused with the homework he has got and he needs your help to do the homework. The homework is to 
 
 print alternate letters from A to Z in alternate uppercase and lowercase
 
 ANS)
 LINK TO PROGRAM
 
 https://onlinegdb.com/IVqJw1lan
 
 LANGUAGE USED C++
 
 
 CODE
                                    
 #include <iostream>

using namespace std;

int main()

 {
    int a=0;
    
    char start_lowercase='a';
 
    
    char start_uppercase='A';
    
    
    
    while(start_lowercase <='z' &start_uppercase<='Z'){
        
         if((a%2)==0){
         
           cout<<start_uppercase;
         
            }
        
         else {cout<<start_lowercase;}
        
         a=a+1;
        
         start_lowercase+=2;
        
         start_uppercase+=2;
     
     cout<<"\n";   
    
     }
    

    return 0;

 }
 
 Q4: 
 
 Given a number n, find out whether this number is Chef number or not.Let's consider an example of 297 as a Chef number: square of 297 is 88209; divided it into two 
 
 portions, 88 and 209; now total them, 88 + 209 to get 297 back. Consider an n-digit number k (take another example of 45). Square it (452 = 2025) and add the right n digits 
 
 (that is 25) to the 

 remaining n or n-1 digits (in this case, 20). If the resultant quantity is k, then k is a Chef number (45 is a Chef number as 20 + 25 = 45). Splitting of the squared number 
 
 should be based on the number of digits of the given number. 
 
 
 ANS)
 
 LINK TO CODE
 
 https://onlinegdb.com/I-ysIyb_kD
 
 
 LANGUAGE USED PYTHON 3

CODE 
n=int(input())

k=n

n=n**2

n=str(n)

x=list(n)

length=len(x)

half_length=length//2

sum1=[]

sum2=[]
 
if length%2==0:
    
     for i in range(half_length):
        
        sum1.append(x[i])
        
     for i in range(half_length,length):
        
        sum2.append(x[i])
    
    str1=''
    
    str2=''
    
    str1=str1.join(sum1)
    
    str2=str2.join(sum2)
    
    str1=int(str1)
    
    str2=int(str2)
    
    if str1+str2==k:
     
       print("Chef Number")
    
    else:
        
       print("Not Chef Number")
        
        
else:
    
    for i in range(half_length):
    
       sum1.append(x[i])
        
    for i in range(half_length,length):
       
       sum2.append(x[i])
    
     str1=''
     
     str2=''
    
     str1=str1.join(sum1)
     
     str2=str2.join(sum2)
     
     str1=int(str1)
     
     str2=int(str2)
    
     if str1+str2==k:
       
        print("Chef Number")
        
    else:
       
        print("Not Chef Number")    

 
 
 
 

 















