<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The project takes one 8-bit input. The 8-bit input is split to form two 4-bit inputs. The inputs are put into an array that uses a combination of AND gates and Full Adders to get the individual values of the product. The Full Adders are coded using a combination of AND, XOR, and OR gates. The images containing the array, Figure 1, and the full adders, Figure 2, are shown below. 

<img width="850" alt="Screenshot 2024-10-29 at 8 16 38 PM" src="https://github.com/user-attachments/assets/64130c60-fd63-433f-9c40-c445be1a31ea">

Figure 1: 4-bit array multiplier


<img width="436" alt="Screenshot 2024-10-29 at 8 16 54 PM" src="https://github.com/user-attachments/assets/c14df7a8-e113-4d82-b77b-d3776fec9cfc">

Figure 2: Circuit Diagram of Full Adder

## How to test

Give an 8-bit input and check if the output is the correct product of the first and last 4-bits of the input.

## External hardware

N/A
