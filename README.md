# cplus2.0-if-else
average grade of mid term and the likes.

#include <iostream>
using namespace std;
int main()
{
    double quiz, midterm, final, average;
    
    cout << " Please enter quiz: ";
    cin >> quiz;
    cout << "Please enter midterm:  ";
    cin >> midterm;
    cout << "Please enter final:  ";
    cin >> final;
    
    cout << "average:";
    
     average=(quiz + midterm + final) /3;
    
   if (average >= 90)
    {
      cout<<" Your grade is A ";
    }
    else if ((average >= 70) && (average < 90))
    {
      cout<<" Your grade is B ";
    }
    else if ((average >= 50) && (average < 70))
    {
      cout<<" Your grade is C ";
    }
    else 
    {
      cout<<" Your grade is F ";
    }
    return 0;
}
   /*
   output:
             
   Please enter quiz: 90
   Please enter midterm:  98
   Please enter final:  95
   average: Your grade is A  */
