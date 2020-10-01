# Notes

Just taking some notes as I learn. This will likely be very haphazard and not really organized.

`::` syntax indicates an associated function on a type. ex: `String::new()`. Similar concept in JavaScript would be `Array.map()` or `String.toLowerCase()`

Macros are like functions (seemingly always available to you? This might be wrong but I don't see us ever importing them) that are not associated to any particular type (unlike calling `String::new` for example). They always end with a bang (haha see what I did there?). ex: `println!()`

`&` before a variable indicates that it is a reference to the variable. It allows multiple parts of your code access the variable without having to store copies of it in memory.

**References are immutable by default!** If you need to make a reference mutable, you do `&mut my_var` instead of `&my_var`.
