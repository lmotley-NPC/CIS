# Arrays for Introductory Programming (Instructor Reference)

## What Is an Array?

An array is a collection of related values stored under a single variable name.

Instead of creating many separate variables:

```text
score1 = 85
score2 = 92
score3 = 78
```

You can use one array:

```text
scores = [85, 92, 78]
```

Arrays help programmers organize and manage groups of related data.

---

## The Locker Analogy

Think of an array as a row of lockers.

- The locker row is the array.
- Each locker has a numbered location.
- Each locker stores a value.

```text
Locker Row = Array
Locker Number = Index
Item in Locker = Value
```

---

## Understanding Indexes

One of the most confusing concepts for beginners is that array indexes usually start at **0**, not 1.

Example:

```text
grades = [85, 92, 78, 95]
           0   1   2   3
```

| Student | Index | Grade |
|----------|--------|--------|
| First Student | 0 | 85 |
| Second Student | 1 | 92 |
| Third Student | 2 | 78 |
| Fourth Student | 3 | 95 |

This means:

```text
grades[0] = First student's grade
grades[1] = Second student's grade
grades[2] = Third student's grade
```

### Helpful Rule

```text
Student Number = Array Index + 1
```

or

```text
Array Index = Student Number - 1
```

---

## Array Declaration

An array declaration creates a set number of storage locations.

Example:

```text
Declare grades[4]
```

This means:

- Create an array named `grades`
- The array has room for 4 values
- The positions will be:

```text
grades[0]
grades[1]
grades[2]
grades[3]
```

The number in brackets during declaration is the array size, not a grade value.

A useful analogy is an egg carton:

```text
12 slots available
```

The 12 represents capacity, not one of the eggs.

---

## Storing Values in an Array

Once declared, values can be placed into individual positions.

```text
grades[0] = 85
grades[1] = 92
grades[2] = 78
grades[3] = 95
```

Now the array contains:

```text
Index:    0    1    2    3
Grades:  85   92   78   95
```

---

## Displaying a Value from an Array

To display the second student's grade:

```text
Display grades[1]
```

Output:

```text
92
```

Remember:

```text
grades[1]
```

represents the second student because indexing starts at 0.

---

## Complete Pseudocode Example

```text
Declare grades[4]

grades[0] = 85
grades[1] = 92
grades[2] = 78
grades[3] = 95

Display grades[1]
```

Output:

```text
92
```

---

## Common Student Mistake

Students often think:

```text
Display grades[2]
```

will display the second student's grade.

Actually:

```text
grades[2]
```

is the third student's grade.

The index represents a storage location, not the student number.

---

## The Three Array Actions

For introductory programming, arrays can be taught using three simple steps:

### 1. Declare

```text
Declare grades[4]
```

### 2. Populate (Fill)

```text
grades[0] = 85
grades[1] = 92
grades[2] = 78
grades[3] = 95
```

### 3. Process

Display a specific value:

```text
Display grades[1]
```

Or process all values using a loop:

```text
For count = 0 to 3
    Display grades[count]
End For
```

---

## Teaching Summary

A simple way to explain arrays to beginning programming students:

> An array allows you to store multiple related values in memory under one variable name and access each value using its index number.

Key points to emphasize:

- Arrays store multiple related values.
- Each value has an index.
- Indexes typically start at 0.
- Arrays are commonly used for grades, temperatures, sales figures, names, and IDs.
- Students should think of indexes as storage locations rather than item numbers.
- The array workflow is: **Declare → Populate → Process**.
