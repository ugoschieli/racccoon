# Home of the raccoon programming language

## Syntax demo

```raccoon
import io;

// the program entrypoint
fn main() {
    const a: int = 69; // immutable variable
    var b: int = 92;   // mutable variable

    b += 2;

    const sum: int = add(a, b);

    io::print("Hello, world!\n"); // print a string to console
    io::print($"{sum}\n");        // print a templated string
}

// a function that takes two ints (32 bits) and return their sum
fn add(a: int, b: int) -> int {
    return a + b;
}
```
