```c++
#include "human.h"

int main()
{
    human VladikVT();
    
    /** MAIN INFO **/
    VladikVT.name    = "Vladislav Timirbaev";
    VladikVT.age     = 17;
    VladikVT.country = "Russia";
    VladikVT.live    = true;
    /** MAIN INFO **/
    
    /** DESCRIPTION **/
    VladikVT.smallDescription = "
        Born in 2005 year. Currently studying in college to be a system administrator.
        Started programming from 9 y.o. Positions itself as a game developer.
        Likes math, science, programming, games and food.
        ";
    VladikVT.currentProject = "StartPage";    // https://github.com/VladikVT/StartPage
    VladikVT.job            = "Programmer";
    VladikVT.PL             = {"C++", "Python", "GDScript"};
    VladikVT.links = {
        "https://vk.com/mr_vladik112",
        "https://notabug.org/vladikvt",
        "https://deadgames-studio.itch.io/"
    };
    VladikVT.projects = {
        "SimpConGraph",    // https://github.com/VladikVT/SimpConGrapf
        "unity",           // https://github.com/VladikVT/unity
        "lost-dungeon",    // https://github.com/VladikVT/lost-dungeon
        "TelNet chat",     // https://github.com/VladikVT/tn-chat
        "StartPage"        // https://github.com/VladikVT/StartPage
    };
    /** DESCRIPTION **/
    
    while (VladikVT.live)
    {
        VladikVT.programming();
    }
    
    return 0;
}
```
