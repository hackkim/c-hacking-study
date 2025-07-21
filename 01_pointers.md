# 🔹 C Language Day 1 - Variables and Pointers

## 🔑 Key Concepts
- `&variable` : Returns the memory address of a variable.
- `*pointer` : Dereferences the pointer to access the value stored at the address.
- Pointers are essential for low-level memory control, which is a foundation for hacking and reverse engineering.

## 💻 Practice 1

```c
#include <stdio.h>

int main() {
    int a = 42;
    int *p = &a;

    printf("Value of a: %d\n", a);
    printf("Address of a (&a): %p\n", &a);
    printf("Value pointed by p (*p): %d\n", *p);
    printf("Value of p (address it stores): %p\n", p);

    return 0;
}
```

## ✅ Sample Output

```
Value of a: 42
Address of a (&a): 0x7ffee5a1f68c
Value pointed by p (*p): 42
Value of p (address it stores): 0x7ffee5a1f68c
```

## 📌 What I Learned
- A pointer stores the address of another variable.
- Using `*p` lets you access or modify the value stored at that address.
- For example, `*p = 100;` would change the value of `a` to 100 if `p = &a`.

## 🔚 Summary
Pointers are the foundation for understanding memory layout, arrays, strings, function parameters, heap memory, and vulnerabilities such as buffer overflows.
This knowledge is essential for both exploit development and reverse engineering.