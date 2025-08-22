# Pointer Operations in C++  

**Name:** Jay Paygude  
**PRN:** 24070123050  
**Batch:** ENTC A2  

This repository contains simple programs that highlight how **pointers** work in C++. The focus is on using pointers to interact with variables, arrays, and strings, along with some basic pointer arithmetic.  

---

## Covered Programs
- Accessing variable values through pointers  
- Performing arithmetic with pointers  
- Reversing an array using pointers  
- Printing a string using a character pointer  

---

## Concept Overview  

A **pointer** is a variable that stores the address of another variable. In C++, pointers are widely used because they:  

- Provide direct access to memory  
- Simplify manipulation of arrays and strings  
- Make dynamic memory allocation possible  
- Form the foundation of data structures like linked lists and trees  

### Key Ideas:
- `int *p;` → declares a pointer to an integer  
- `p = &x;` → assigns the address of `x` to `p`  
- `*p` → dereferences the pointer to access the stored value  
- Pointer arithmetic (`p+1`, `p2-p1`) is useful for iterating arrays  

---

## Algorithms  

### 1. Accessing Variables with Pointers  
**Steps:**  
1. Define variables of different data types.  
2. Create pointers to these variables.  
3. Assign addresses and print:  
   - Variable value  
   - Pointer value (address)  
   - Dereferenced value (`*ptr`)  
   - Original variable address  

---

### 2. Pointer Arithmetic on Arrays  
**Steps:**  
1. Declare an integer array.  
2. Point `ptr1` and `ptr2` to different positions.  
3. Calculate `ptr2 - ptr1` to get element distance.  
4. Use `*ptr1 + *ptr2` to add values.  

---

### 3. Reverse Array using Pointers  
**Steps:**  
1. Initialize an array.  
2. Use a pointer to point to the last element.  
3. Move backwards while printing values.  

---

### 4. Print String using Pointer  
**Steps:**  
1. Define a C-style string.  
2. Set a character pointer to the first character.  
3. Loop until `'\0'` and print using `*ptr`.  

---

## Conclusion  

- Pointers are a key part of C++ memory handling.  
- They provide ways to manipulate values directly.  
- Arithmetic with pointers allows efficient array traversal.  
- They are essential for working with dynamic memory and building data structures.  

---

## Program Summary  

| Program               | Description                                    |  
|-----------------------|------------------------------------------------|  
| Variable Access       | Demonstrates accessing variable data via pointers |  
| Pointer Arithmetic    | Shows operations like difference and addition   |  
| Reverse Array         | Prints array elements in reverse order          |  
| String with Pointer   | Traverses and prints a string character by character |  
