// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
/*
Input : Herman435Mill678er43

Output 1 : 435 + 678 + 43 = 1156
Output 2 : 4 + 3 + 5 + 6 + 7 + 8 + 4 + 3 = 40
*/
//Take string as a input
//for each char if = char next else 
/*
{
    Lopp
    if(char)
    found 
    next
    
    else
    {
        found*10+newnumber
        //second case not needed
    }
    
}*/

bool checkIsDigit(char digit)
{
    if(digit>=48 && digit <=57)
    return true;
    else
    return false;
}

int main() {
    // Write C++ code here
    //std::cout << "Hello world!";
    //First Take input
    //65 97 48
    while(1)
    {
      //string  strInput= "SRI62ram7kumar834sa42";
      string strInput;
      cout << "Enter a string Input";
      cin >> strInput;

      cout <<endl<< strInput<<endl;
      int nInputSize = sizeof(strInput);
      //cout<<nInputSize<<endl;

      int sum2 = 0;
      bool isFound = false;
      
      int sum1 = 0;
      for(int i=0;i<nInputSize;i++)
      {
          int temp = 0;
          if(checkIsDigit(strInput[i]) == true)
          {
              isFound = true;
              temp = (strInput[i]-48);
              
              while(checkIsDigit(strInput[++i]) == true)
              {
                temp = temp*10 +   (strInput[i]-48);
              }
              
              sum1 = sum1+temp;
          }
            
      }

      for(int i=0;i<nInputSize;i++)
      {
          if(checkIsDigit(strInput[i]) == true)
          {
              sum2 = sum2 + (strInput[i]-48);
          }

      }

      cout << sum1<<endl;
      cout << sum2<<endl;
      
      
      
    }

    return 0;
}
