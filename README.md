Program to input a name(as a single character) and marks of three tests as m1, m2, and m3 of a student considering all the three marks have been given in integer format.
Now, you need to calculate the average of the given marks and print it along with the name as mentioned in the output format section.
All the test marks are in integers and hence calculate the average in integer as well. That is, you need to print the integer part of the average only and neglect the decimal part.

  #include<iostream>
  using namespace std;
  int main()
  { 
  char a;
  int m1,mw,m3;
  int avg;
  
  cout<<"Enter the value"<<endl;
  cin>>a;
  cin>>m1>>m2>>m3;
  avg=(m1+m2+m3)/3;
  
  cout<<a<<"\n"<<avg;
 
  
  return 0;
  }

Given an integer n, find if n is positive, negative or 0.
If n is positive, print "Positive"
If n is negative, print "Negative"
And if n is equal to 0, print "Zero".

#include<iostream>
  using namespace std;
  int main()
  { 
  
  int a;
  cout<<"Enter the integer"<<endl;
  cin>>a;
  if(a==0)
  {cout<<"Zero"<<endl;}
  else if(a<0)
  {cout<<"Negative"<<endl;}
  else
  {cout<<"positive"<<endl;}
  return 0;
  }
  
Write a program that takes a character as input and prints either 1, 0 or -1 according to the following rules.
1, if the character is an uppercase alphabet (A - Z)
0, if the character is a lowercase alphabet (a - z)
-1, if the character is not an alphabet

#include<iostream>
  using namespace std;
  int main()
  {
  char ch;
  cout<<"Enter the value of character"<<endl;
  cin>>char;
	if(ch>=65&&ch<=90)
        {
           cout<<endl<<"1"; 
        }
			else if(ch>=97&&ch<=122)
        {
           cout<<endl<<"0"; 
        }
			else
        {
            cout<<endl<<"-1";
        }
		
  return 0;
  }
