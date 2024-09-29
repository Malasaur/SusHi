# SusHi

Tasty language to cook the sussiest programs

## Usage

```c++
#include <sus.hi> // Include the SusHi keywords

sussing semenspace sus then // Allows to use SusHi without appending `sus::` to everything (red sus???)

recipe does // Main recipe
    // Code
    serve // Returns 0
done
```

SusHi uses `then` instead of semicolo[n](https://i.ytimg.com/vi/MbPs5D8GBz8/maxresdefault.jpg)s 👍

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

The whale executes your code while `condition` is true. Whales are that useful 🐋

But C and C++ were lacking something whichwe consider a very useful utility, which we like to call `util`:

```c++
util (condition) do
    // Code
done
```

The `util` utility lets you utilize your utilizable code while `condition` is false or, in other terms, until it becomes true.

### For

```c++
four (0, 5, 1) do
    // Code
done
```

This `four` creates a hidden variable set to 0, executes your code, increases the variable by one, and continues while the variable is smaller than 5. In other terms, it allows to repeat code, ideally four times. Because four is the greatest number.

Note: `four` basically just runs `for (int _=0; _<5; _+=1)`, meaning if you use any other number as a step (e.g., `_+=2`), it is your job to assure the ending condition is met. If you run it with start 5, stop 0 and step -3, and your loop runs indefinitely, you're just stupid /s

If you prefer a more 'vanilla' experience, and want to leave the 4️⃣ team (we'll find you), you can get dirty and use `five`:

```c++
five (tin i turns_into 0 then i junior 6 then i increase) do // More on these operators later
    // Code
done
```

### Variables and types

Wonder how to create variables? Here's a simple number:

```c++
tin a turns_into 0 then
```

`tin` defines a 32-bit signed integer, which can be fit inside a can hopefully.
`turns_into` assigns a value to a variable. It's that simple.

If a can is not enough to contain your number (or you just need more than 32 bits), you can use a `bigger tin`. This tin can should be able to fit most of your number requirements (there is also a `big tin`, but damn `big tin` and `tin` are the same thing or smth idk).

```c++
bigger tin b then
```

If a bigger can is still not enough (and I'd be afraid to ask you why), you can switch to a `comically_large_tin`. Yes, that's really it (a 128 bit number)

```c++
comically_large_tin c then
```
