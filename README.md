# Compiling Notes

---

```bash
// Update Arch

$ sudo pacman -Syu
```

```bash
// Search Database

$ sudo pacman -Ss gcc
```

```bash
// Install GCC

$ sudo pacman -S gcc
```

```bash
// Verify Version

$ gcc --version
```

```bash
// Remove GCC

$ sudo -Rns gcc

// Remove GCC/Dependencies

$ sudo pacman -Rcnu gcc
```

---

## C Program Compile

```c
// hello.c
#include <stdio.h>

int main()
{
  printf("Hello, world!\n");
  return 0;
}

```

Default Output

```bash
$ gcc hello.c

$ chmod a+x a.out

$ ./a.out
```

Labeled Output

```bash
$ gcc -o hello hello.c

$ chmod a+x hello

$ ./hello
```

