# Lain 16

**L**AIN's **A**rchitectural **I**nstructio**N**
16: 16 Bit, 24 bit address
## registers
PC0: (32)24 bit Program Counter
PC1: 32(24) bit Interrupt Handler Program Counter
 
N:4x8 bit Instruction Holder

D0-D15: General Purpose 16 bit Registers
X: 4 bit Set Index Pointer Register
P: 4 bit Set Stack Pointer Register
R: 4 bit Set Return Pointer Register

I: 8 bit Input flag Register
Q: 1 bit Output

CCR: 8 bit Conditional Register
- 0: Z: Zero
- 1: C: Carry Over
- 2: N: Negative
- 3: E: Extended
- 4: O: Overflow
- 5: S: Supervisor
- 6: F: Fence
- 7: N/A

INTR: 16 bit Interrupt Register
- 0~7: 


## instructions

32 bit wide instructions
```
[OPERATION] [REGISTER] [DATA0] [DATA1]
```

LOAD:
- 
