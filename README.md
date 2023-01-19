# Class Allocator

A simple program to allocate students randomly into a number of classes.

## Usage
### Prepare students file
Prepare a file called `students.txt` in the same directory as the class binary. Each line contains a student's name. E.g.
```
Luke
James
Amy
Rebecca
Tom
Jasmin
```

### Run
```
class "classname1 classname2"
```

The class names should be surrounded by quotation marks, separated by one whitespace.

### Example output
```
class "3S 3P"

3S
------------
Tom
Amy
Jasmin


3P
------------
Rebecca
James
Luke
```