#include <iostream>
using namespace std;

int main()
{
  float arr[] = {4, 3, 2, 1, 0, 1, 2, 3, 4, 3};     //Step 0: Test the array of size 10
  const int SIZE = 10;                              //Step 1: Ask a question: how do I                                                       //calculate the GPA?
  float sum = 0;
  double GPA = 0;
  
  for (int i=0; i<SIZE; i++)            
  {
    sum += arr[i];                              //Step 2: Find the sum of the array
    GPA = sum/SIZE;                             //Step 3: Divide the sum by SIZE
  }
   cout << GPA << endl;                         //Step 4:Print out the GPA         

return 0;  
}
