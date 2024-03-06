
```
  vim welcome.c
```
writting code...
```c
#include <stdio.h>

int main(void){
  char *phrase = "Welcome to my Github profile\n";

  printf(phrase);

  return 0;
}

```
let's compile it...
```
gcc -Wall welcome.c -o welcome
```

Output

## Welcome to my Github profile
