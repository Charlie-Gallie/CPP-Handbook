# Outputting to the console

### Example

`A`
```cpp
#include <iostream>

int main(){
    std::cout << "Hello" << std::endl;

    return 0;
}
```

`B`
```cpp
#include <iostream>

int main(){
    std::string someText = "Hello";

    std::cout << someText << std::endl;
    std::cout << "5 + 5 = " << 5 + 5 << std::endl;

    return 0;
}
```

`C`
```cpp
#include <iostream>

int main(){
    std::cout << "Hello";
    std::cout << "How are you?";

    return 0;
}
```

### Explanation

The standard library contains `cout` which stands for "character output". Using this function allows you to output text to the console. The `<<` operator allows you to concatenate text.

As seen in example `B`, variables can also be used in place of strings. As well as that, arithmetic can be parsed.

The reason `std::endl` (end line) is added to the end of each line which outputs text is to do a carriage return (new line). Without it, such as in example `C`, the text would all be printed on one line.