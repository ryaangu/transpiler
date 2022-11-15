# About
A little custom language -> C transpiler written in Python. No type checking, it only converts a token list into C code. My plan is to rewrite the transpiler using the custom language.

# Example
```c
extern int puts(const char *content);

void main()
{
    puts("Hello, World!");
    return;
}
```