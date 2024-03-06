#Cpp
# Printing Hello World
Before even using the print functions I need to grab the standard library this can be done by including
```c++
#Include <iostream>
```


Next in our code we need to have a **main** this tells C++ this is the **starting** **point** of the code 

```C++
#include <iostream>

int main() {
```


To actually print characters  out we need to use a function called **cout** this looks like,

```C++
#incude <iostream>

int main() {  
    std::cout << "Hello, World!" << std::endl;  
    return 0;  
}

```

The `return 0;` statement is the **"Exit status"** of the program. In simple terms, the program ends with this statement.


