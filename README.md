### types conversion

`string` to `int`:


```c++
  string s = '42';
  int a = stoi(s);
```

`char to int`:

```c++
  char a = '5';
  int b = a - '0';
```

### characters

`islower` - tests whether char is in lower case

```c++
  char a = 'b';
  bool b = islower(a) // true;
```

`isupper` - tests whether char is in upper case

```c++
  char a = 'b';
  bool b = isupper(a) // true;
```