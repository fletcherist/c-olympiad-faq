### types conversion

`string` to `int`:


```c++
  string s = '42';
  int a = stoi(s); // 42
```

`char to int`:

```c++
  char a = '5';
  int b = a - '0'; // 5
```

### characters

`islower()` - tests whether char is in lower case

```c++
  char a = 'b';
  islower(a); // true
```

`isupper()` - tests whether char is in upper case

```c++
  char a = 'b';
  isupper(a); // true
```

`toupper()` - 'a' to 'A' uppercase

```c++
  char a = 'a';
  toupper(a); // 'A'
```

`tolower()` - 'A' to 'a' lowercase

```c++
  char a = 'A';
  tolower(a); // 'a'
```

### strings

`erase(a, b)` - remove characters from string

**a** start with

**b** how many characters to erase


```c++
  string s = "hello world";
  s.erase(1, 1); // 'ello world'
```

### numbers

`pow(a, b)`
> return a^b

```c++
  #include <math.h>
  pow(3, 3); // 27
```