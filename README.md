
# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV A, P0
MOV R0, A
MOV B, R0
MUL AB
MOV P2, A
SJMP $
END

```

## OUTPUT
<img width="843" height="389" alt="Screenshot 2025-11-09 133602" src="https://github.com/user-attachments/assets/7df53710-618b-4b0a-b3e2-5062b89b93a2" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 0000H
MOV A, P0
MOV B, A
MUL AB
MOV R0, P0
MOV B, R0
MUL AB
MOV P2, A
SJMP $
END
```


## OUTPUT
<img width="830" height="402" alt="image" src="https://github.com/user-attachments/assets/9e8a8fd4-9a7c-4f42-821c-8590211afb27" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
