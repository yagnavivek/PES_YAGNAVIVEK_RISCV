<details>
<summary>DAY 3 : Digital Logic With TL Verilog in Makerchip IDE</summary>
<br>

# Example 
Navigate to [makerchip](https://makerchip.com)

### Inverter
- Learn -> Examples -> Makerchip Default Template

#### A) Inverter in TLV using command

- under TLV Section type ```$out = ! $in1```
- Now compile ``` press E -> compile```

#### B) Xor gate using operators

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/8b29750b-b133-4ce8-8326-5ccfd7d87d5a)

#### C) Vectors

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/402438eb-b996-4782-945a-9df8a89030fa)

#### D) Mux (with and without vectors)

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/7795306d-10ba-48f4-a9e8-e490e5fcb102)

#### E) Simple Claculator

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/a09cf5b0-3202-42e0-8762-97cb3581bc61)

### Sequential Logic

- Sequential logic is sequenced by a clock signal
- A D-flip-flop transitions next state to current state on a rising clock edge
- Reset signal helps the circuit come to a known state

#### F) Fibonacci series

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/0e78f120-fb9f-4d24-ba6d-5b3e2485bd61)

#### G) Up-Counter

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/647f822d-008f-48ec-ae93-ade2da37db85)

#### H) Sequential Calculator 
  Input val1 is the previous output of calculator

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/9192605d-1221-46fd-bac3-c1f06352ac16)

#### I) A simple pipeline through Pythagorean example

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/923022a1-7bc4-4fd6-95e8-c0ea41405aba)

#### J) Pipeline Implementation example

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/2a58ccd8-e1ca-42bd-af79-2a277bc72265)


## Validity 
- Easier debug
- cleaner design
- Better error checking
- Automated clock gating

#### K) 2 cycle calculator with validity

![Screenshot from 2023-10-14 18-00-53](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/3e2e5fe1-2cbf-485d-a4e6-a6976e07e755)


#### L) Distance Calculator

![Screenshot from 2023-10-14 18-53-33](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/64701bdb-aa3e-4323-a2f4-2f2fa51a776c)

#### M) Calulator_memory

![Screenshot from 2023-10-14 18-58-48](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/bfc81566-6343-42e7-bfea-4ace15c2bfcf)


</details>

<details>
<summary>DAY 4 : Basic RISC-V CPU Micro Architecture</summary>
<br>

# RISC-V Implementation Blueprint

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/140a5803-8436-47a0-9e84-945284415482)

Link for the starter code [starter code](https://myth.makerchip.com/sandbox?code_url=https:%2F%2Fraw.githubusercontent.com%2Fstevehoover%2FRISC-V_MYTH_Workshop%2Fmaster%2Frisc-v_shell.tlv#) 

Codes for each step reported below can be found here [Day4 Codes](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/tree/main/DAY4)

## 1. Program Counter

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/86ebf67f-95ab-4a2b-8002-3eb1789966c6)

## 2. Instruction Fetch

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/3c9f61c7-124d-4dd7-b6d7-254da8ed16b3)


## 3.Instruction Decode

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/3464a32d-62c8-4a50-aef2-2c7e7000a179)

## 4. Instruction Decode with validity

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/06ea8486-6e91-4524-bff7-1b37cc0ff349)

## 5. Individual Instruction decode

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/e870f9db-de18-4052-b2d4-189dc0eddb92)

## 6. Register file read

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/a9c98216-a816-4fcf-974f-75fceeacbecd)

## 7. ALU

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/6a29d2b9-9354-48fa-8303-b09d90bf8b8c)

## 8. Register File Write

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/0c766dc9-3cd6-4387-bf9f-4167558ec240)

## 9. Branch Instructions

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/5e41c6a7-deac-411a-b439-05ff52215eb8)

## 10. Testbench to check functionality

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/857f16f1-e979-4e0f-a3f1-415392c6c85b)

</details>

<details>
<summary>DAY 5 : Complete Pipelined RISC-V Micro Architecture </summary>
<br>

- Pipelining helps improve the operating frequency by breaking down the micro-arch ito substages that consume lesser time.But this process intriduces some hazards and dependencies such as
  - Data Hazards
  - Structural Hazards
  - Control Hazards
  - Name Dependence
  - Anti Dependence
  - Output Dependence

 ## 3-cycle RISC-V

 - A simple pipeline approach where we divide the arch into 3 stages ie., PC, Decode to ALU, Reg write.
 - This requires a valid signal that is generated every 3 clock cylces

### Generation of 3 cycle valid signal

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/cef37901-c4f9-4382-af6c-f778a1aaaa4a)

- There might be some invalid cycles (invalid operation when valid is on) being encountered in this proccess. SO we have to take care of them.

### 3-cycle RISC-V To take care of invalid signals

- Avoid writing into register file for invalid operations
- Avoid redirecting PC for nvalid instructions(branch)

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/1a2ec7de-4ab5-4e8c-bf8f-4024191dd641)

### Introduce 5 stage pipeline 

- 5 stage pipeline : PC, Decode, Reg Rd, ALU, Reg write

## Solutions to Pipeline Hazards

1. Register file bypass

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/9be47987-9e97-4eed-9c5e-8e65f0f158f2)

2. Correct the branch target path

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/2fffda72-1a4f-4b81-8643-dfa2a7fe8c7a)

3. Complete Instruction Decode

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/4f2127df-b28f-47e0-abac-37e7648f8ef2)

4. Complete ALU

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/dfb54415-4cda-434c-b175-11703f128ec8)

## Completing RISC-V CPU with final touch of Load/Store Instructions

1. Redirecting Loads

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/066cf305-0aa3-41fe-a937-f5ad39095d91)

2. Load Data from Memory to register file

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/f0fee7f9-9bf4-4a38-8386-275a52ebfecf)

3. Instantiate Data memory to CPU

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/03573672-9076-4c12-a8ac-c0fb43c2722d)

4. Add loads and stores to test the program

```
m4_asm(SW r0, r10, 100)
m4_asm(LW r15, r0, 100)
```
5. Lab for jump instructions

![image](https://github.com/yagnavivek/PES_YAGNAVIVEK_RISCV/assets/93475824/ec4d2fcf-143a-40e9-b991-912637bc4372)


</details>

