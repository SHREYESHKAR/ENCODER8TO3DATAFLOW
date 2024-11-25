# NAME : SHREYESHKAR SEKAR
## REFERENCE NUMBER : 24900622


## EXP 5 : ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

The 8 to 3 line Encoder is also known as Octal to Binary Encode

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3


**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: RegisterNumber:24900622
*/
![WhatsApp Image 2024-11-25 at 11 42 18 AM](https://github.com/user-attachments/assets/913f9879-0679-4d40-9997-154898c181a9)




**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![ENCODER DE DIAGRAM](https://github.com/user-attachments/assets/e6728e16-7e73-4212-899a-d9187282701f)


**OUTPUT** 

![ENCODER DE OUTPUT](https://github.com/user-attachments/assets/e3ab6e30-1c19-48aa-9fef-2ba5a1c53cc3)



**RESULTS**

Encoder 8 To 3 implemented successfully in Dataflow Modelling using verilog and validated their functionality using their functional tables.


