# one-to-ten
Counts from one to ten
#include <iostream>
using namespace std;
//prints out the numbers from one to ten 
void myFunction( int counter){
cout<<"Alec Narkizian - 3/11/18"<<endl;
//using a loop go cycle through the numbers
   while (counter < 11){
      if(counter == 11)
         return;
      else{
      //prints number if previous conditions have been met  
         std::cout<<counter<<std::endl;
         counter = ++counter; 
         }
                        }
                          }
//main function calls myFunction
int main(){
  int counter = 1;
  myFunction(counter);
            }    
    
