# This project's aim is to implement a doubly circular linked list with a sentinel along with some basic operations
<br>

> [!NOTE] 
> This is the first homework of data structures and algorithms from UNSTPB ACS faculty, CS field, 1st year.

#### Structs
```c
typedef struct TrCell2 {
    char data;
    struct TrCell2 *next;
    struct TrCell2 *prev;
} TRCell2, *TRL2;

typedef struct Train {
    TRL2 head;
    TRL2 mechanic;
} *TTrain;
```
#### The operations implemented are
- move left/right

```console
It moves the mechanic, which represents the current cell, to one of its adjacent positions.
```
- insert left/right

```console
It inserts a new cell adjacent to the current mechanic position and it moves the mechanic accordingly.
```
> [!NOTE]
> If the mechanic is in the first car, it will be displayed an error message
- search left/right

```console
It searches for a certain character.
```
- clear_cell

```console
It clears the contents of the cell and it removes it completely.
```
- clear_all

```console
It clears all the cells and it restores the train to its initial state.
```
- switch

```console
It moves the mechanic, which represents the current cell, to one of its adjacent positions.
```
- show

```console
It moves the mechanic, which represents the current cell, to one of its adjacent positions.
```
  
