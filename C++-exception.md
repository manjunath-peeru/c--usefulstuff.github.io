# c--usefulstuff.github.io


#include <iostream>
#include <string>
#include <sstream>
#include <exception>
using namespace std;

class BadLengthException {

    int _n;

public:
    explicit BadLengthException( int n ) : _n(n) {}

    int what() {
            return _n;
        }    
};





https://protegejj.gitbooks.io/algorithm-practice/content/tree.html
