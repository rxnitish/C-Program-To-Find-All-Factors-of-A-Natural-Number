# C-Program-To-Find-All-Factors-of-A-Natural-Number
#include <iostream> 
using namespace std; 
  
// Function to print the divisors 
void printDivisors(int n) 
{ 
    for (int i = 1; i <= n; i++) 
        if (n % i == 0) 
            cout <<" " << i; 
} 
  
// Driver code 
int main() 
{ 
    cout <<"The divisors of 100 are: "; 
    printDivisors(100); 
    return 0; 
} 
  
