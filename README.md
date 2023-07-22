# java question practice

QUESTION 1::----    percentage of 5 sub marks


package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	System.out.println("enter the marks ");
	Scanner sc = new Scanner(System.in);
	

	
	
	System.out.println("1st subject");
	int sub1 = sc.nextInt();
	
	System.out.println("2nd subject");
	int sub2 = sc.nextInt();

	System.out.println("3rd subject");
	int sub3 = sc.nextInt();
		
	System.out.println("4th subject");
	int sub4 = sc.nextInt();
		
	System.out.println("5th subject");
	int sub5 = sc.nextInt();
	
	System.out.println("mark out of");
	int n = sc.nextInt();
	
	float sum = sub1+ sub2+ sub3+ sub4+ sub5;
	float percent = (sum/(5*n))*100;
	System.out.print("total : ");
	System.out.println(sum);
	System.out.print("percentage: ");
	System.out.println(percent);
	
													
	    }
	}

------------------------------------------------------------------------------------------------------------------------------------------------


QUESTION 2 ::: THE sum of three numbers



package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println("enter the first number");
	 float a=sc.nextFloat();
System.out.println("enter the 2nd number");
float b=sc.nextFloat();
System.out.println("enter the 3rd number");
float c=sc.nextFloat();
System.out.print("the sum of the number is :-> ");
 float sum = a+b+c;
 System.out.println(sum);
	
	
	  }
	}
------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION  3 :::: cgpa of 3 subjects....




package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println("enter the marks");
	int sub1=sc.nextInt();
	System.out.println(sub1);
	int sub2 =sc.nextInt();
	System.out.println(sub2);
	int sub3 =sc.nextInt();
	System.out.println(sub3);
	System.out.println("total marks");
	float total = (sub1 +sub2 + sub3);
	System.out.println(total);
	float cgpa = total/30;
	System.out.println("CGPA : ");
	System.out.println(cgpa);
	
	
	
	  }
	}

------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 4 ::: hello + <name> + have a good day


package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println("WHAT IS YOUR NAME");
	String str = sc.nextLine();
	System.out.println("hello  " +str+ " ,have a good day ");
	



}
}
------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 5 ::::: km to miles...


package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println(" mesurement in km");
	double km =sc.nextDouble();
	
	double miles = (km/1.609);
	System.out.print("the length in miles is ::: ");
	System.out.println(miles);
	



}
}

------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 6 :::: number is integer or not ..


package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println(" enter a number ");
	System.out.println(sc.hasNextInt());
}
} 

------------------------------------------------------------------------------------------------------------------------------------------------


QUESTION 7 :::: operator's.....(arthimatic{+,-,*},,assignment{==,+=},,comparision{>,<})

 

package mohammadammar;

import java.util.Scanner;

public class chw_08_operators {
public static void main(String[] args) {
	
	Scanner sc = new Scanner(System.in);
	System.out.print("the number n is : ");
	int n = sc.nextInt();
	System.out.println("enter no. a");
	int a= sc.nextInt();	
//	 a == 3;
	//System.out.print("a  =  ");
	System.out.println("a > (3*n)  ? ");
	System.out.println(a>(3*n));
	
}
}

------------------------------------------------------------------------------------------------------------------------------------------------


QUESTION 8 ::::::: find value of 7/4 * 9/2 answers is 7.875



package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	float a = 7/4.0f * 9/2.0f ;
	System.out.println(a);
}
}

------------------------------------------------------------------------------------------------------------------------------------------------


QUESTION 9 ::::: manipulating grades 

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {


char grade = 'A';
 grade = (char)( grade + 8);
System.out.println(grade);

grade = (char)(grade-8);
System.out.println(grade);

}}  


------------------------------------------------------------------------------------------------------------------------------------------------


QUESTIONS 10 :: enterd number is greater than or not by given number.

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {

	Scanner sc = new Scanner(System.in);
	int a = 9;
	System.out.println("enter a number");
	int b = sc.nextInt();
	boolean br = b > a;
	System.out.print("the entered number is greater than given number :: ");	
	System.out.println(br);

}}  


------------------------------------------------------------------------------------------------------------------------------------------------

QUESTIONS 11 :: (v*v - u*u) / (2*a*s)....



package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println("enter a ,s,v,u respectively");
	float a = sc.nextFloat(), s=sc.nextFloat() , v=sc.nextFloat() , u=sc.nextFloat() ;
    float exp = (v*v - u*u) / (2*a*s);
    System.out.println(exp);



}} 



------------------------------------------------------------------------------------------------------------------------------------------------


QUESTIONS 12 :: string basics..



package mohammadammar;

import java.util.Scanner;

public class chw_09_strings {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	String a = "ammar ";
	System.out.println(a);
	  
	String a1 = sc.nextLine();
	//String a1 = new String("ammar wesal");
	System.out.println(a1);
		
	
}
}



------------------------------------------------------------------------------------------------------------------------------------------------

QUESTIONS 13 ::


package mohammadammar;

import java.util.Scanner;


public class chw_09_strings {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
    String a=sc.nextLine();
    System.out.println(a);
    
    //  1  length
    int value = a.length();
    System.out.println(value);
    
    //  2  uppercase
    String large = a.toUpperCase();
    System.out.println(large);
    
    //  3  lowercase 
    String small = a.toLowerCase();
    System.out.println(small);
    
    //  4 trim and non trim string
    String nontrim = ("         ammar wesal asjijkisj ISJIJWIN   ");
    System.out.println(nontrim.trim());
    
    //  5 substrate
    System.out.println(a.substring(3,4));  /*(3 is included (starting point) but 6 is excluded(end point)*/
    System.out.println(nontrim.substring(18,29));
    
    //  6 replace
    String b = "ASDFGkk";
    System.out.println(b.replace("kk","I") );
    
    //  7 starts with..  ends with..
    System.out.println(a.startsWith("amma"));
    System.out.println(a.endsWith("asdk"));
    
    //  8 char at..
    System.out.println(a.charAt(4));
    
    //  9 index of..
    System.out.println(a.indexOf("i"));
    System.out.println(a.indexOf("j", 2));
    
    //  10 last index of..
    System.out.println(b.lastIndexOf("DF"));
    System.out.println(b.lastIndexOf("DF", 3));
    
    //  11 string equality..
    System.out.println(b.endsWith("ammar"));
    System.out.println(a.endsWith("ammar"));
    
    //  12 equal ignore case.......
    System.out.println(b.equalsIgnoreCase("asdfgkk"));
    
    //  13 escape sequence character..(\n , \t ,\',\",etc).
    System.out.println("i am \"mohammad ammar\"");
    System.out.println("i am\nmohammad ammar"  );
    System.out.println("i am\t mohammad ammar"  );
    System.out.println("i am\\mohammad ammar"  );
    System.out.println("i am\bmohammad ammar"  );

}

}

---------------------------------------------------------------------------
QUESTIONS 14 : IF ELSE

int a = 29;
if (a>18) {
	System.out.println(“You can drive”);
}
else{
       System.out.println(“You are underage!");
}



---------------------------------------------------------------------
Question 15: Write a program to find out whether a student is pass or fail; if it requires a total of 40% and at least 33% in each subject to pass. Assume 3 subjects and take marks as input from the user


package com.company;
import java.util.Scanner;


public class cwh_19_ch4_ps {
    public static void main(String[] args) {

byte m1, m2, m3;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter your marks in Physics");
        m1 = sc.nextByte();

        System.out.println("Enter your marks in Chemistry");
        m2= sc.nextByte();

        System.out.println("Enter your marks in Mathematics");
        m3 = sc.nextByte();
        float avg = (m1+m2+m3)/3.0f;
        System.out.println("Your Overall percentage is: " + avg);
        if(avg>=40 && m1>=33 && m2>=33 && m3>=33){
            System.out.println("Congratulations, You have been             promoted");
        }
        else{
            System.out.println("Sorry, You have not been promoted! Please try again.");
        }

------------------------------------------------------------------------------
Question 16 :Calculate income tax paid by an employee to the government as per the slabs mentioned below:
--------------------------------------------------------------------------

Question 17: Write a Java program to find out the day of the week given the number [1 for Monday, 2 for Tuesday … and so on!]


Scanner sc = new Scanner(System.in);
        int day = sc.nextInt();

        switch (day){
            case 1 -> System.out.println("Monday");
            case 2 -> System.out.println("Tuesday");
            case 3 -> System.out.println("Wednesday");
            case 4 -> System.out.println("Thursday");
            case 5 -> System.out.println("Friday");
            case 6 -> System.out.println("Saturday");
            case 7 -> System.out.println("Sunday");
      }

----------------------------------------------------------------------------------------

Question 18:Write a Java program to find whether a year entered by the user is a leap year or not
(done by my self by didn't save)
---------------------------------------------------------------------------







QUESTIONS 19 :: find .com ,.org, .in sites


package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args)

{  Scanner sc= new Scanner(System.in);

   String a = sc.nextLine();
   if(a.endsWith(".com")){
	   System.out.println("commercial website");   
   }
   else if ( a.endsWith(".org")) {
	   System.out.println(a.endsWith("organisation website"));
   }
   else if(a.endsWith(".in")){
	   System.out.println(a.endsWith("indian website"));
   }
   else {
	   System.out.println(a.endsWith("none"));
   }
   
    
}} 
------------------------------------------------------------------------------------------------------------------------------------------------
questions 20 : looops basics

package mohammadammar;

public class loops_11 {
	public static void main(String[] args) {
		int i=1;
		while(i<=11) {
			System.out.println(i);
			i++;
		}
	}

}
------------------------------------------------------------------------------------------------------------------------------------------------

question 21: Write a program to print natural numbers from 100 to 200

package com.company;

public class cwh_21_ch5_loops {
    public static void main(String[] args) {
        System.out.println(1);
        System.out.println(2);
        System.out.println(3);

        System.out.println("Using Loops:");
        int i = 100;
        while(i<=200){
            System.out.println(i);
            i++;
        }
        System.out.println("Finish Running While Loop!");

//        while(true){
//            System.out.println("I am an infinite while loop!");
//        }
    }
}

----------------------------------------------------------------------------

QUESTION 22: Write a program to print first n natural numbers using a do-while loop.

package com.company;

public class cwh_22_ch4_do_while {
    public static void main(String[] args) {
//        int a = 0;
//        while(a<5){
//            System.out.println(a);
//            a++;
//        }
        int b = 10;
        do {
            System.out.println(b);
            b++;
        }while(b<5);

        int c = 1;
        do{
            System.out.println(c);
            c++;
        }while(c<=45);

    }
}
-----------------------------------------------------------------------------
QUESTION 23: Write a program to print first n odd numbers using a for loop.

QUESTION 24: Write a program to print first n natural numbers in reverse order.


package com.company;

public class cwh_23_for_loop {
    public static void main(String[] args) {
//        for (int i=1; i<=10; i++){
//            System.out.println(i);
//        }
        // 2i = Even Numbers = 0, 2, 4, 6, 8
        // 2i+1 = Odd Numbers = 1, 3, 5, 7, 9
        //int n = 3;
        //for (int i =0; i<n; i++){
        //    System.out.println(2*i+1);
        //}

        for(int i=5; i!=0; i--){
            System.out.println(i);
        }
    }
}
-------------------------------------------------------------------------------------------------------------------------------------------------

QUESTIONS 25: break statement.

public class CWH_break {  
public static void main(String[] args) {  
    //using for loop  
    for(int i=10;i>0;i--){  
        if(i==7){  
            break;   //break the loop
        }  
        System.out.println(i);  
    }  
}  
} 
------------------------------------------------------------------------------------------------------------------------------------------------------

QUESTIONS 26: continue statement

public class CWH_continue {  
public static void main(String[] args) {  
 
    for(int i=7;i>0;i--){  
        if(i==3){  
            continue;//continue skips the rest statement
        }  
        System.out.println(i);  
    }  
}  
}   

-----------------------------------------------------------------------------------------------------------------------------------------------------

question 27 : draw a patern


package mohammadammar;



public class ammarjava {
public static void main(String[] args)
{int n =5;

    for (int i= n ; i>0;i--) {
    	for(int j=0;j<i;j++) {
    		System.out.print("*");
    	}
    	System.out.println("\n");
    	
    
    }
    
}}  

------------------------------------------------------------------------------------------------------------------------------------------------

question 28:: sum of first n even number is

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	Scanner sc=new Scanner(System.in);
int sum =0;
System.out.println("enter the no. n");
	int n = sc.nextInt();
	for (int i=0;i<n;i++) {
		sum= sum +(2*i);
		
	}
	
  System.out.println("sum of first n even number is");
   System.out.println(sum); 
}}  
------------------------------------------------------------------------------------------------------------------------------------------------

question 29 :: 5 ki table

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	Scanner sc=new Scanner(System.in);
for(int i=0;i<=10;i++) {
	System.out.printf("%d X %d =%d \n",5,i,5*i);
}
}}  
------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 30:: table of ten in reverse order

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	Scanner sc=new Scanner(System.in);
for(int i=10;i>0;i--) {
	System.out.printf("%d X %d =%d \n",10,i,10*i);
}
}}  
------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 31: factorial of a number

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	Scanner sc=new Scanner(System.in);
	int n = sc.nextInt();
	int factorial = n;
// factorial 6!=6*5*4*3*2*1
for(int i=n;i>1;i--) {

factorial = factorial*(i-1);

	
}
System.out.println(factorial);


}}  

------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 32: sum of multiples of 8

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	Scanner sc=new Scanner(System.in);
	int n = sc.nextInt();
int sum =0;
for(int i=10;i>0;i--) {
	sum = sum +n*i;
 System.out.printf("%d X %d = %d\n",n,i,n*i);


}
System.out.println(sum);

}}  
------------------------------------------------------------------------------------------------------------------------------------------------
QUESTIONS 33: ARRAYS

package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
		
	int[] marks = new int[5];
	marks[0]=123;
	marks[1]=134;
	marks[2]=143;
	marks[3]=223;
	marks[4]=423;
	
System.out.println(marks[4]);

}}
------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 34: ANOTHER WAY

package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
		
	int[] marks = {123,34,5678,677,44,33};

	
System.out.println(marks[4]);

}}

---------------------------------------------------------------------------------------------------------------------------------------------
 QUESTIONS:35  basics of array

package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
		
int[] marks = {12,23,3,556,56};
System.out.println(marks.length);
System.out.println(marks[4]);

float []weight= {34,78,98.9f,9.377f};
System.out.println(weight[3]);

String[]name= {"asdgh","etvlo","ammar"};
System.out.println(name[2]);

}}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

QUESTIONS:36 arrays useing loop

package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
// suppose we have to print 11 marks of student..
		int[] marks= {12,45,67,90,45,89,67,78,98,23,42};
		System.out.println(marks[0]);
		System.out.println(marks[1]);
		System.out.println(marks[2]);
		System.out.println(marks[3]);
		System.out.println(marks[5]);
		System.out.println(marks[6]);
		System.out.println(marks[7]);
		System.out.println(marks[8]);
		System.out.println(marks[9]);
		System.out.println(marks[10]);
		System.out.println("\n\n");
//  it is to lengthy and take lots of time so we use loops
		
		int []markss= {12,45,67,90,45,89,67,78,98,23,42};
		for(int i=0;i<markss.length;i++) {
			System.out.println(markss[i]);
		}

// printing in reverse order

                 System.out.println("\n\n");
		
		for(int i=markss.length-1;i>=0;i--) {
			System.out.println(markss[i]);
		}
}}


-----------------------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 37: for eacl loop for array..


package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
		int []markss= {12,45,67,90,45,89,67,78,98,23,42};
		
		for(int element:markss) {
			System.out.println(element);
		}
}}

-----------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 38:multi dimensional arrays (2-d array)...

package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
// multi dimensional arrays (2-d array)
		
		int[][]flats=new int[2][3];
		flats[0][0]=101;
		flats[0][1]=102;
		flats[0][2]=103;
		flats[1][0]=201;
		flats[1][1]=202;
		flats[1][2]=203;
		
		System.out.println(flats[1][2]);

// multi dimenssional aaray useing for loop......

for(int i=0;i<flats.length;i++) {
			for(int j=0;j<flats[i].length;j++) {
			System.out.print(flats[i][j]);
			System.out.print(" ");
		}
			System.out.println(" ");
}
		
		
		
}}
----------------------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 39: sum of 5 elements of arrays..

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
float [] marks= {12.6f,13.4f,15.5f,18,20};
float sum = 0;

//for (int i=0;i<marks.length;i++) {
//	sum = sum+marks[i];
	
//}

              OR

for (float element:marks) {
	sum = sum+element;
	
}
System.out.println(sum);

}}

------------------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 40: to find whethere the integer is present in the array or not..


package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	Scanner sc= new Scanner(System.in);
int [] integer= {1,4,6,0,-1,-6};
System.out.println("enter any integer");
int n=sc.nextInt();
int i =0;
boolean is_in_array= false;
for( i=0;i<integer.length;i++) {
	if(n==integer[i]) {
		is_in_array=true;
		break;
	}}
	
if(is_in_array) {
	System.out.println("value is present in array ");


}
else {
	System.out.println("the value is not present in the array");
}

}} 
--------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 41: avg of element of arrays..

package mohammadammar;

import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	//Scanner sc= new Scanner(System.in);
int [] marks= {12,13,15,18,19};
float sum =0;
float avg =0.0f;
for(int i=0;i<marks.length;i++) {
	sum = sum + marks[i];
	avg = sum/marks.length;
}
System.out.println(avg);
	
}} 

------------------------------------------------------------------------------------------------------------------------------------------------


QUESTION 42: adding of 2 matrix of 2x3..

package mohammadammar;

//import java.util.Scanner;

public class ammarjava {
public static void main(String[] args){
	//Scanner sc= new Scanner(System.in);
int[][] matrix_1 = new int[2][3];
matrix_1[0][0]=12;
matrix_1[0][1]=22;
matrix_1[0][2]=34;
matrix_1[1][0]=21;
matrix_1[1][1]=23;
matrix_1[1][2]=24;

int[][] matrix_2 = new int[2][3];
matrix_2[0][0]=1;
matrix_2[0][1]=2;
matrix_2[0][2]=4;
matrix_2[1][0]=1;
matrix_2[1][1]=3;
matrix_2[1][2]=4;

int [][] result = new int[2][3];
result [0][0]=0;
result [0][1]=0;
result [0][2]=0;
result [1][0]=0;
result [1][1]=0;
result [1][2]=0;

for(int i=0;i<matrix_1.length;i++) {
	for(int j=0;j<matrix_1[i].length;j++) {
	//	System.out.format("setting value for i=%d and j=%d\n",i,j);
		result[i][j]=matrix_1[i][j]+matrix_2[i][j];
		System.out.print(result[i][j]+" ");
}
System.out.println("");	
}

	
}} 

************************OR****************************  

package mohammadammar;

public class arrays_12 {
	public static void main(String[] args) {
// multi dimensional arrays (2-d array)
		
		int[][]mat1 = {{01,02,03},{04,05,06}};
		int[][]mat2 = {{2,2,2},{5,5,5}};
int[][]result= {{0,0,0},{0,0,0}};

		for(int i=0;i<mat1.length;i++) {
			for(int j=0;j<mat1[i].length;j++) {
				result[i][j]=mat1[i][j]+ mat2[i][j];
				System.out.print(result[i][j]+" ");
		}
		System.out.println(" ");	
		}

		
}}

-------------------------------------------------------------------------------------------------------------------
QUESTION 43: reversing an array..

package mohammadammar;

//import java.util.Scanner;
public class ammarjava {
public static void main(String[] args){
	//Scanner sc= new Scanner(System.in);

 int[] array = {12,34,56,78};
 for(int i=array.length-1;i>=0;i--) {
	 System.out.println(array[i]);
 }
	
***************************************OR******************************************************

package mohammadammar;

//import java.util.Scanner;
public class ammarjava {
public static void main(String[] args){
	//Scanner sc= new Scanner(System.in);
int[] arr= {2345,34,2,3,4,5,56};
int l = arr.length;
int temp ;
int n= Math.floorDiv(arr.length, 2);
	for(int i=0;i<n;i++) {
		//swap a[i] and a[l-1-i]
		// |4| |3| ||
		temp = arr[i];
		arr[i]= arr[l-1-i];
	    arr[l-1-i]= temp;
		
	}
	for(int element: arr) {
	System.out.println(element);
}} }
------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 44: max and min element of arry..

package mohammadammar;

//import java.util.Scanner;
public class ammarjava {
public static void main(String[] args){
	//Scanner sc= new Scanner(System.in);
int[] arr= {345,34,2,3,4,5,0,5567};
int max= Integer.MIN_VALUE ;
int min= Integer.MAX_VALUE;
for(int element: arr) {
	if(element>max) {
		max=element;
		
	}	
	else if(element<min) {
		min=element;
		
	}
}
System.out.println("the value of the maximum element in this arry is:"+max);
System.out.println("the value of the minimum element in this arry is:"+min);

}} 
-----------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 45: array is sorted or nor...


package mohammadammar;

//import java.util.Scanner;
public class ammarjava {
public static void main(String[] args){
	//sorted means smaller to greater;
	boolean issorted= true;
int[] arr= {5,34,222,334,445,555,780,5567};
for(int i=0;i<arr.length-1;i++) {
	if(arr[i]>arr[i+1]) {
		issorted=false;
		
		break;
	}
	}
if(issorted) {
	System.out.println("the array is sorted");
}
else {
	System.out.println("not sorted");
}

}} 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

QUESTION 46: method in java..

package mohammadammar;

public class method_13 {

	static int logic(int x,int y) {
		int z;
		
		
		if(x>y) {
			z=x+y;
		}
		else {
			z=(x+y)*5;
		}
		return z;
	}
	
	
	public static void main(String[] args) {
	
		int a=2;
		int b=3;
		int c;
		c=logic(a,b);
		int a1=2;
		int b1=1;
		int c1;
		c1=logic(a1,b1);
		
		
		System.out.println(c);
		System.out.println(c1);
	}

}
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


QUESTION 47: method in java..


package mohammadammar;

public class method_13 {


	static void telljoke() {
		System.out.println("i invented a new word!\n"+"plagairism!");
	

	}
	
	public static void main(String[] args) {
		telljoke();
	}

}
------------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 48:

package mohammadammar;

public class method_13 {
	
	static void change(int a) {
		a=98;
	}
	
	
	static void change2(int[] arr ) {
		arr[0]=98;
	}



	static void telljoke() {
		
		System.out.println("i invented a new word!\n"+"plagairism!");
	

	}
	
	public static void main(String[] args) {
		//telljoke();
		int [] marks = {56,88,90,98,22};
//  CASE 1 CHANGE THE INTEGER
//		int x=45;
//		change(x);
//		System.out.println("the value of x after running chage is :"+ x);
		
 // CASE 2 CHANGE THE ARRAY
			
			change2(marks);
			System.out.println("the value of marks after running chage is :"+ marks[0]);
		
	}

}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 49: method of over loading ..

package mohammadammar;

public class method_13 {
	
	static void foo() {
		System.out.println("good morning");
	}
	
	
	static void foo(int a) {
		System.out.println("total boys are: " + a); // a is parameter
	}
	
	static void foo(int a,int b) {
		System.out.println("boys are: " + a + " and girls are: " + b); // a and b are parameter
	}
	
	public static void main(String[] args) {
	// arguments are actual value
		foo();
		foo(330); // 330 is ARGUMENT
		foo(45,89); // 45 AND 89 ARE ARGUMENT
	}

}
------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 50: VAIRAIBLE ARGUMENTS........................

package mohammadammar;

public class vairable_arguments_14 {
	
	static int sum(int a, int b) {
		return a+b;
	}
	
	static int sum(int a, int b,int c) {
		return a+b+c;
	}
	
	static int sum(int a, int b, int c, int d) {
		return a+b+c+d;
	}
	
	static int sum(int a, int b,int c,int d, int e) {
		return a+b+c+d+e;
	}
	
	
public static void main(String[] args) {
	System.out.println("welcome to varaggs tutorial");
	System.out.println("the sum of 4 and 5 is:"+" "+sum(4,5,6));
	System.out.println("the sum of 4 and 5 is:"+" "+sum(4,5,4,4));
	System.out.println("the sum of 4 and 5 is:"+" "+sum(4,5,3,2,1));
	System.out.println("the sum of 4 and 5 is:"+" "+sum(4,5));
	;
}
}


*************************************OR*********************************************************OR*************************************************************
package mohammadammar;

public class vairable_arguments_14 {
	
//	static int sum(int a, int b) {
//		return a+b;
//	}
//	
//	static int sum(int a, int b,int c) {
//		return a+b+c;
//	}
//	
//	static int sum(int a, int b, int c, int d) {
//		return a+b+c+d;
//	}
//	
//	static int sum(int a, int b,int c,int d, int e) {
//		return a+b+c+d+e;
//	}
//	
//	
	static int sum(int ...arr) {
		int result =0;
		for(int a: arr) {
          result += a;
         
		}
		 return result;
	}
	
	
public static void main(String[] args) {
	System.out.println("welcome to varaggs tutorial");
	

	System.out.println("the sum of nothing is:" +sum());
	System.out.println("the sum of 1 is:" +sum(1));
	System.out.println("the sum is:" +sum(4,5));
	System.out.println("the sum is:" +sum(6,4,5));
	System.out.println("the sum is:" +sum(2,6,4,5));
	System.out.println("the sum is:" +sum(6,3,4,5));
	
}
}

-----------------------------------------------------------------------------------------------------------------------------------------------------
QUESTION 51:

package mohammadammar;

public class vairable_arguments_14 {
	
	
	static int sum(int x,int ...arr) {
		int result =x;
		for(int a: arr) {
          result += a;
         
		}
		 return result;
	}
	
	
public static void main(String[] args) {
	System.out.println("welcome to varaggs tutorial");
	
//	System.out.println("the sum of nothing is:" +sum());// error
	System.out.println("the sum of nothing is:" +sum(0));
	System.out.println("the sum of 1 is:" +sum(1));
	System.out.println("the sum is:" +sum(4,5));
	System.out.println("the sum is:" +sum(6,4,5));

	
}
}
--------------------------------------------------------------------------------------------------------------------------
QUESTION 52: recursion baisics...

package mohammadammar;

import java.util.Scanner;

public class recursion_15 {
	 //calling function by itself is recursion
	
	static int factorial_iterative(int n) { //method 1
		if(n==0 || n==1) {
			return 1;
		}
		else {
			int product =1;
			for(int i=n;i>0;i--) {
				product *= i;
			}
			return product;
		}
	
	}
	static int factorial(int n) {  // method 2
		// factorial (0) is 1
		// factorial of 5 is -> 5*4*3*2*1
		// factorial of n is -> n*(n-1)*(n-2).....*1
		// factorial of n is -> n*factorial(n-1)		
	if(n==0||n==1) {
		return 1;
	}
	else {
		return n*factorial(n-1);
	}
	
	}
	

	public static void main(String[] args) {
		Scanner sc= new Scanner(System.in);
	
	System.out.print("enter the number n to get the factorial:\t");
	int n=sc.nextInt();	
	System.out.println("the value of factorial n is::\t" + factorial(n));
	System.out.println("the value of factorial n is::\t" + factorial_iterative(n));
		
	}
	
//	public static void main(String[] args) {  // without recursion
//		int n=4;
//		int factorial =n;
//		for(int i=n;i>1;i--) {
//			factorial=factorial*(i-1);
//		}
//		System.out.println(factorial);
//	}
}


-----------------------------------------------------------------------------------------------------------------
QUESTION 53: fibonacci series..





