# 🔹 C Language Day 1 - Variables and Pointers (Extended)

## 💻 Practice 2 - Reassigning Pointers

```c
#include <stdio.h>

int main() {
    int a = 10;
    int b = 20;
    int *p;

    p = &a;
    printf("p points to a: %d\n", *p);

    p = &b;
    printf("p now points to b: %d\n", *p);

    return 0;
}
```

## ✅ Sample Output

```
p points to a: 10
p now points to b: 20
```

## 📌 What I Learned
- A pointer can be reassigned to point to different variables.
- This allows one pointer to access multiple memory locations over time.
- Understanding this behavior is crucial in managing memory in low-level programming and exploit development.

## 🔚 Summary
This concept lays the foundation for later topics like arrays, pointer arithmetic, dynamic memory, and buffer overflow exploits.