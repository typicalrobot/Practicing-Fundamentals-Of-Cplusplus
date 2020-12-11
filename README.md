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
