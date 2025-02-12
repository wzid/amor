# amor
A programming language "construido con amor" (built with love ❤️)

## Progress
I will probably have to add more as I go along the project but this is all I have now.
- [ ] [Syntax Design](#syntax-design)
    - [x] Comments
    - [x] Functions
    - [x] Variables
    - [x] If-Else
    - [ ] Structs
    - [ ] Enums
    - [ ] Loops
    - [ ] Arrays
    - [ ] Pointers
- [ ] Lexer
- [ ] Parser/Grammar Rules
- [ ] LLVM Backend

## Syntax Design

```
// Comments
fn add(a: int, b: int): int {
    return a + b;
}

fn mul(a: int, b: int): int => a * b;

fn main() {
    int a = 10;
    if a > 5 {
        println("a is greater than 5");
    } else {
        println("a is less than or equal to 5");
    }
}
```