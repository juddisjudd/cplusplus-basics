# C++ Basics

## Variables
Variables are used to store values. They have a type, such as int (for integers), float (for floating-point numbers), or char (for characters), and a name. For example:
```
int age = 30;
float weight = 75.5;
char initial = 'J';
```
## Operators
C++ supports a variety of operators, such as arithmetic operators (e.g., +, -, *, /), relational operators (e.g., <, >, ==, !=), and logical operators (e.g., &&, ||, !). These operators can be used to perform calculations and compare values.
## Control structures
C++ has several control structures that allow you to control the flow of your program. These include if statements, for loops, and while loops. For example:
```
if (age > 18) {
  std::cout << "You are an adult." << std::endl;
} else {
  std::cout << "You are a minor." << std::endl;
}
```
```
for (int i = 0; i < 10; i++) {
  std::cout << i << std::endl;
}
```
```
int i = 0;
while (i < 10) {
  std::cout << i << std::endl;
  i++;
}
```
## Functions
Functions are blocks of code that can be called from other parts of your program. They can take parameters and return a value. For example:
```
int add(int x, int y) {
  return x + y;
}

int main() {
  int result = add(2, 3);
  std::cout << result << std::endl; // prints 5
  return 0;
}
```

These are just a few of the basics of C++. There are many other concepts to learn, such as classes, arrays, pointers, and more. I recommend finding a good tutorial or textbook to learn more about the language.
