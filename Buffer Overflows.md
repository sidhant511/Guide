# Buffer Overflows
* Stack

## Vulnerable Code

vuln.c
```c
#include <stdio.h>

int main(int argc, char *argv[])

{
  char buffer[64];

  if (argc < 2)
  {
    printf("syntax error\r\n");
    printf("must supply at least one argument\r\n")
    return(1);
  }
  strcpy(buffer,argv[1]);
  return(0);
}
```

* Supply more than 64 bytes and this crashes

Registers to remember
* ESP - Extended Stack Pointer
  * push and pop values
* EIP - Extended Instruction Pointer
  * holds the current address location for the instruction being executed at any given time

### OllyDbg Layout

Bottom right - shows stack memory at any given moment

Bottom left - Allows us to see memory dumps

Look for where main function begins


## Stack Overflow

## Windows BO Example

## Linux BO Example
