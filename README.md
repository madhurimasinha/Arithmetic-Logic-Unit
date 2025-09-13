**Arithmetic Logic Unit**

Arithmetic Logic Unit (ALU) is a digital circuit that performs arithmetic and logical operations within a processor.
This work descirbes the working of an ALU that has been implemented using different arithmetic and logical operations.
It takes two input values and performs the necessary operation depending on the control signal, which will be provided as a third input value and produces the respective result. The control signal describes the type of operation that needs to be performed on the inputs provided.

VLSI techniques allows us to design ALUs that are faster in execution of operation, better in power-efficiency, compact and reliable for the modern processors.

**Specifications**

- _Bit-width_: This project compares the results of 16 vs 32 vs 64-bit ALU
  
- _Inputs_:  
  Operands - A, B  
  Opcode - depending on the number of operations  
  Control Signals
  
- _Operations_: The operations (arithmetic operations, logical operations, shift operations, comparison operations) are selected based on the control signal
  
- _Flags_: The ALU generates flags for decision-making
  Zero(Z) - set when result = 0   
  Carry(C) - set when addition or subtraction generates a carry/borrow         
  Overflow(V) - set when signed arithmetic overflows the representable range   
  Negative(N) - reflects MSB of result (sign bit in two’s complement)   
  Parity (P) - set if the number of 1s in result is even
