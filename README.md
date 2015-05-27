#include <iostream>
using namespace std;

class Fan {
private:
    
    int Speed;
    bool On = true;
    double Radius;
    
public:
    void SetSpeed(int);
    
    Fan (){
        Speed = 1; on = false; radius = 5;
    }
    
};
