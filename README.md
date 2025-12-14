# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:  E.Priyadharshini    RegisterNumber:  25014488
*/

<img width="1910" height="941" alt="Screenshot 2025-12-14 195834" src="https://github.com/user-attachments/assets/ef8e6689-2665-45a1-a3b4-014cdface818" />


**RTL LOGIC FOR FLIPFLOPS**

<img width="1695" height="910" alt="Screenshot 2025-12-14 195814" src="https://github.com/user-attachments/assets/c1142b7a-bf0b-4e7b-88fe-bcf23f8a726d" />


**TIMING DIGRAMS FOR FLIP FLOPS**

<img width="1916" height="390" alt="Screenshot 2025-12-14 195949" src="https://github.com/user-attachments/assets/f8d3c0fe-cbe2-460f-9ccd-a9e2436e96b5" />


**RESULTS**

Thus, implemented the T flipflop using verilog and their functionality using functional tables.
