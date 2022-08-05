# mehedicharlei777
Nothing

1.Check even or odd. C
Answer:
#include <stdio.h>
int main() {
    int num;
    printf("Enter an integer: ");
    scanf("%d", &num);

    // true if num is perfectly divisible by 2
    if(num % 2 == 0){
        printf("%d is even.", num);
         }
    else{
        printf("%d is odd.", num);
    }
    return 0;
}
2.ANumPositiveOrEven.c


#include<stdio.h>
Int main(){
	Int number;
	Printf(“Enter a number to check validity:”);
    Scanf(“%d”,&number);
    If(number>=0 || number%2==0)
    	Printf(“valid.\n”);
	Else
		Printf(“Invalid.\n”);
	
	
}


3.WeatherACharCapitalOrSmall.c
#include<stdio.h>

Int main(){
    Char ch;
    Scanf(“%c”,&ch);
    If(ch>=’A’ && ch<=’Z’){
        Printf(“Capital\n”);
    }else if(ch >= ‘a’ && ch <= ‘z’){
    	Printf(“Small\n”);
	}else{
		Printf(“Invalid input\n”);
	}
       
}
4.TakeStringInputAnd PrntIt.c

#include<stdio.h>
Int main(){
    Char ar[5000];
    Int I, n;
    Printf(“How many character do wanna to print:\n”);
    Scanf(“%d”, &n);
    For (I = 0; I < n;i++){
        Scanf(“%c”, &ar[i]);
    }
    For (I = 0; I < n;i++){
        Printf(“%c”, ar[i]);
    }
}
//another way
#include<stdio.h>
Int main(){
    Char ar[3000];
    Gets(ar);
    Puts(ar);
}
5.CharAndString.c

#include<stdio.h>
Int main(){
    Int n;
    Char ar[1000];
    Printf(“How many character do you wanna print:\n”);
    Scanf(“%d”, &n);
    For (I = 0; I < n;i++){
        Scanf(“%c”, &ar[i]);
    }
    For (I = 0; I < n;i++){
        Printf(“%c”, arr[i]);
    }
}

6.UsingArrayCalTheSumOfEvenNum.c
#include<stdio.h>
Int main(){
    Int arr[20],I, sum = 0;
    For (I = 0; I < 10;i++){
        Scanf(“%d”, &arr[i]);
    }
    For (I = 0; I < 10;i++){
        If(arr[i]%2==0){
            Sum += arr[i];
        }
    }
    Printf(“%d”, sum);
}

7.UsingArrayAvgOfTenNu.c


#include<stdio.h>
Int main(){
    Int arr[16], I, sum = 0, avg;
    For (I = 0; I < 10; i++)
    {
        Scanf(“%d”, &arr[i]);
    }
    For (I = 0; I < 10;i++){
        Sum += arr[i];
    }
    Avg = sum / 10;
    Printf(“Average is =%d”, avg);
}

8.SumOfAnyNumber.c
#include<stdio.h>
Int main(){
    Int num,I,sum=0;
    Scanf(“%d”,&num);
    For(i=1;i<=num;i++){
        Sum+=I;
    }
    Printf(“Sum=%d”,sum);
}
9.SumOfAnyEvenNUm.c

#include<stdio.h>
Int main(){
    Int num,I,sum=0;
    Scanf(“%d”,&num);
    For(i=2;i<=num;i+=2){
        Sum+=I;
    }
    Printf(“Sum=%d”,sum);
}

10.SumOFNegativeOddAndPositiveOdd.c

//sum of 1-2+3-4+5+…………+-n
#include<stdio.h>
Int main(){
    Int num,I,sum=0;
    Scanf(“%d”,&num);
    For(i=1;i<=num;i++){
        If(i%2!=0)
        Sum+=I;
        Else
        Sum-=I;
    }
    Printf(“Sum=%d”,sum);
}
11.Explain conditonal Operatorc.c


Expalin condiitonal operator with proper example.
Ans:
The conditiona operator is also known as a ternary operator.
The conditional are the decision -making statement
Which depends upon the output of the expression.It is represnted by two symbols,i.e ‘?’:
	
As conditional operator woeks on three operands,so it is also known as the ternary operator.

The behavior of the conditional operator is similar to the ‘if-else’ statementas 
If-else’ statement is also a decision making statement.
Syntex of conditional operator.
Exp1?exp2:exp3;
Example.
(marks>40)?printf(“Passed”):printf(failed);
	12.ANumPositiveOrEven.c

/*A number is valid if its positive or even.Take input from user and check its validity.*/
#include<stdio.h>
Int main(){
	Int number;
	Printf(“Enter a number to check validity:”);
    Scanf(“%d”,&number);
    If(number>=0 || number%2==0)
    	Printf(“valid.\n”);
	Else
		Printf(“Invalid.\n”);
	
	
}
13.Students marks.c

/* take input from user a marks and check the grade for this corresponnding mark*/
#include<stdio.h>
Int main(){
	Int marks;
	Printf(“Enter marks\n”);
	Scanf(“%d”,&marks);
	If(marks>=80 && marks<=100)
	     Printf(“Grade: A+\n”);
	     
	   Else if(marks>100 && marks<0)
	     Printf(“Invalid input.\n”);
	     
	   Else if(marks>=70 && marks<=79)
	     Printf(“Grade:A\n”);
	     
	   Else if(marks<70 && marks>=40)
	     Printf(“Grade: B\n “);
	     
	   Else
	    Printf(“failed!\n”);
}

14.Find_biggestNum.c

#include<stdio.h>
Int main(){
	Int n1,n2,n3;
	Printf(“Enter three numbers:\n”);
	Scanf(“%d%d%d”,&n1,&n2,&n3);
	If(n1>=n2 && n1>=n3){
		Printf(“%d is the biggest number.”,n1);
	}else{
		If(n2>=n3){
			Printf(“%d is the biggest number.”,n2);
		}else{
			Printf(“%d is the biggest number.”,n3);
		}
	}
}

15.Positive_even_num.c
#include<stdio.h>
Int main(){
	Int num;
	While(1){
		Printf(“Enter any num:\n”);
	Scanf(“%d”,&num);
	If(num>=0 && num%2==0){
		Printf(“True\n”);
	}else{
		Printf(“Fales\n”);
	}
	}
	
}


