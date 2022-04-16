```c++
#include <iostream>
#include <human.h>

using namespace std;

int main()
{
    human VladikVT();
    
    /** MAIN INFO **/
    VladikVT.name    = "Vladislav Timirbaev";
    VladikVT.age     = "16";
    VladikVT.country = "Russia";
    VladikVT.live    = true;
    /** MAIN INFO **/
    
    /** DESCRIPTION **/
    VladikVT.smallDescription = "
        Born in 2005 year. Currently studying in college to be a system administrator.
        Started programming from 9 y.o. Positoins itself as a game developer.
        Likes math, science, programming, games and food.
        ";
    VladikVT.currentProject   = "SimpConGraph"; // https://github.com/VladikVT/SimpConGraph
    VladikVT.job              = "Programmer";
    VladikVT.PL               = "C++, Python, GDScript";
    /** DESCRIPTION **/
    
    while (VladikVT.live)
    {
        VladikVT.programming();
    }
    
    return 0;
}
```
