# Square-Cube-of-a-number-using-8051
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
MOV R0,#50H
MOV A,@R0 
MOV B,@R0 
MUL AB
INC R0 
MOV @R0,A
END




```

## OUTPUT


<img width="1083" height="612" alt="Screenshot 2026-05-29 at 6 08 36 PM" src="https://github.com/user-attachments/assets/2a182bd4-6c6c-47b0-a8b8-f701189c2d58" />


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



ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END




```


## OUTPUT


<img width="1083" height="612" alt="Screenshot 2026-05-29 at 6 08 36 PM" src="https://github.com/user-attachments/assets/6c636afc-b51c-470c-a9c8-8cbcadc73083" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


