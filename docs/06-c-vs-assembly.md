# C vs. Assembly (LC-4)

One reason 593 teaches C after assembly is that C abstracts patterns you've 
already seen at the register and instruction level. This section makes those 
connections explicit.

All assembly examples use LC-4 and the register conventions from CIS 593:
R5 = frame pointer, R6 = stack pointer, R7 = return address.

## 1. Function Calls

### 1.1 The Prologue
### 1.2 The Epilogue
### 1.3 Return Values

## 2. Local Variables and the Stack Frame

## 3. Parameters
### 3.1 How C Parameters Map to Stack Slots
### 3.2 Right to Left Pushing Order

## 4. Pointers and Addresses

## 5. Stack Trace Example

A side-by-side walkthrough: a short C function and its equivalent LC-4 
assembly, with the stack diagram showing register values at each step.
