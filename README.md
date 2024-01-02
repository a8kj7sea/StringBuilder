# **StringBuilder**

It is a class used in the C++ programming language, designed to assist in building or creating text strings efficiently. Its benefit lies in avoiding the use of repetitive operations to concatenate strings, and it helps improve program performance when dealing with large amounts of textual data. Simply put, it is a tool that aids in constructing texts in an efficient and fast manner


Simple example 
```cpp
#include <iostream>
#include <string>

#include <StringBuilder.cpp>

int main() {
  StringBuilder strBuilder;
  strBuilder.append("Hello ").append(" World !!").append("\n").append("My name is a8kj").append("\n");
  cout << strBuilder.toString();
  
  return 0;
}

```


```cpp

Object.append(); // Used to add/append items or strings or type in string
Object.toString(); // after finish append ... blabla you should convert them to string by toString();
```

output :
```


Hello  World !!
My name is a8kj

```



[Execute Code online](https://onlinegdb.com/onvVqu89NR)

