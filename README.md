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
        Started programming from 9 y.o. Positions itself as a game developer.
        Likes math, science, programming, games and food.
        ";
    VladikVT.currentProject   = "unity";    // https://github.com/VladikVT/unity
    VladikVT.job              = "Programmer";
    VladikVT.PL               = "C++, Python, GDScript";
    VladikVT.links = {
        "vk.com/mr_vladik112",
        "notabug.org/vladikvt",
        "deadgames-studio.itch.io/"
    };
    VladikVT.projects = {
        "SimpConGraph",    // https://github.com/VladikVT/SimpConGrapf
        "unity"            // https://github.com/VladikVT/unity
    };
    /** DESCRIPTION **/
    
    while (VladikVT.live)
    {
        VladikVT.programming();
    }

    return 0;
}
```
