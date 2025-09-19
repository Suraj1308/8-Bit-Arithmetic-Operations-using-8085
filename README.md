# 8-Bit-Arithmetic-Operations-using-8085
## Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.

## Apparatus Required:
•	Laptop with internet connection

## Algorithm:

### For Addition (With Carry Consideration):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Add the contents of registers A and B.
4.	If carry is generated, store carry in 4301H.
5.	Store the sum in memory location 4300H.
   
### Program:
<img width="1816" height="856" alt="image" src="https://github.com/user-attachments/assets/3615d7fe-3f54-4371-bd83-f03759477ace" />
<img width="288" height="420" alt="image" src="https://github.com/user-attachments/assets/6c63219c-62dc-4157-9f15-815f0f369614" />


### Output:
<img width="305" height="432" alt="image" src="https://github.com/user-attachments/assets/c1e1adbb-3a2f-47a6-bfa9-e45e1f8726b6" />


### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

### Program:
<img width="1886" height="835" alt="image" src="https://github.com/user-attachments/assets/83ca4705-33b0-47de-96f8-ddadba5c09d3" />
<img width="297" height="457" alt="image" src="https://github.com/user-attachments/assets/d9a43ace-2afe-4afd-83fd-a73876e697e0" />


### Output:
<img width="295" height="413" alt="image" src="https://github.com/user-attachments/assets/768fc16d-21e4-48a4-a3cc-020fc12806cb" />

### For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).

### Program:
<img width="1880" height="852" alt="image" src="https://github.com/user-attachments/assets/563e7347-351f-4a92-92ce-4b7ed2f5c057" />
<img width="295" height="425" alt="image" src="https://github.com/user-attachments/assets/168877d1-eaa5-45f5-8d38-138f0500ddf8" />


### Output:

<img width="289" height="384" alt="image" src="https://github.com/user-attachments/assets/3c1a86eb-b518-465c-b0bf-acdb9d29aab8" />

### For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.

### Program:
<img width="1878" height="881" alt="image" src="https://github.com/user-attachments/assets/31274e4e-ddf0-4a99-8094-4b915e30280a" />
<img width="292" height="528" alt="image" src="https://github.com/user-attachments/assets/442a8fb4-964e-46d3-9d9c-5216046a371f" />

### Output:
<img width="289" height="465" alt="image" src="https://github.com/user-attachments/assets/2bd23687-b431-47f2-9661-8a557b328eb1" />
### Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.


## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.

