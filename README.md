#My Repository PYTHON
this is my first repository created in GITHUB.
##PYTHON Notes
name = "surya"
print(id(name))
here variable name-A reference (or name) is a variable name that refers to an object in memory.So name is not the object itself. It refers to the object.
"surya": The actual data/entity created in Python's memory.
id() is a built-in Python function that returns the identity of an object.
dir(variable object) shows the names of attributes and methods available on an object.
name="surya"
dir(name)
help(variable or object.method_name) used to describe what it will do.
name="surya"
help(name.upper)
help(print) can know functionality of in built functions
Category	Data types
Numeric  	int, float, complex
Text	    str
Sequence	list, tuple, range
Mapping	    dict
Set  	    set, frozenset
Boolean	    bool
Binary	    bytes, bytearray, memoryview
None	    NoneType
int	Integer (whole number)	10, -5, 100
float	Decimal number	10.5, 3.14
complex	Complex number	2+3j

Legal variable names
A variable name can contain:Letters: a-z, A-Z Numbers: 0-9 Underscore: _
But there is one important rule:
A variable name cannot start with a number.
Illegal variable names
1. Starting with a number 2. Spaces are not allowed 3. Special characters are not allowed 
4. Python keywords cannot be used

name = "surya"
name = "krishna"
print(name) krishna,The second assignment reassigns the name name to the latest new string "krishna".

A function is a reusable block of code that can be called independently, whereas a method is a function associated with an object or class and is normally called using dot notation.

Python determines the object's type at runtime, and that information helps it decide which operations/methods are valid.

type() returns the name of the data types

print(f"My name is {name} and I am {age} years old.") f means formatted string.

String concatination rule-Strings can only be concatenated with strings using +.
"Hello"       → normal string
'Hello'       → normal string
"""Hello
World"""      → multi-line string

Implicit conversion → Python does it automatically.adding int and float will come as float
Explicit conversion → You tell Python to do it.age = "20" age = int(age)

