# SusHi

Tasty language to cook the sussiest programs

## Usage

```c++
#include <sus.hi> // Include the SusHi language

sussing semenspace sus then // Allows to use SusHi without appending `sus::` to everything

recipe does // Main recipe
    // Insert code...
    serve // Returns 0
done
```

SusHi uses `then` instead of semicolos 👍

### I/O

```c++
coat insert "Hello, World!" then // Insert "Hello, World!" into your coat (prints some output)
chin extract address a then // Extract some data from your chin to a's address (takes some input)

```

`insert` and `estract` represent, respectively, `<<` and `>>`

### If

```c++
if (condition1) do
    // Code 1
done fi if (condition2) do
    // Code 2
done fi do
    // Code 3
done
```

This code runs `Code 1` if `condition1` is true, `Code 2` if `condition1` is false and `condition2` is true, `Code 3` if `condition1` and `condition2` are false, `Code 4` if you are a 5-dimensional being.

### While/Until

```c++
whale (condition) do
    // Code
done
```

The whale executes your code while `condition` is true. Whales are that useful.

But C and C++ were lacking something whichwe consider a very useful utility, which we like to call `util`:

```c++
util (condition) do
    // Code
done
```

This amazing utility executes your code while `condition` is false or, in other terms, until it becomes true.

### For

```c++
four(0, 5, 1) do
    // Code
done
```

This `four` creates a hidden variable set to 0, executes your code, increases the variable by one, and continues while the variable is smaller than 5. In other terms, it allows to repeat code, ideally four times. Because four is the greatest number.