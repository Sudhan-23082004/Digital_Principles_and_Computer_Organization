<a name="br1"></a> 

**EXPT. NO: 01**

**DATE:**

**VERIFICATION OF BOOLEAN THEOREMS USING LOGIC GATES**

′

̅̅̅̅

̅

̅

퐃퐞퐦퐨퐫퐠퐚퐧 퐬 퐅퐢퐫퐬퐭 퐓퐡퐞퐨퐫퐞퐦 → 퐀퐁 = 퐀 + 퐁

**Truth Table:**

**A**

0

0

1

1

**B**

0

1

0

1

**AB**

0

̅̅̅̅

̅

̅

̅ ̅

퐀 + 퐁

퐀퐁

퐀

1

1

0

0

퐁

1

0

1

0

1

1

1

1

0

0

1

0

1

1

0

**Circuit Diagram:**

′

̅̅̅̅̅̅̅̅ ̅ ̅

퐃퐞퐦퐨퐫퐠퐚퐧 퐬 퐒퐞퐜퐨퐧퐝 퐓퐡퐞퐨퐫퐞퐦 → 퐀 + 퐁 = 퐀 . 퐁

**Truth Table:**

**A**

0

0

1

1

**B**

0

1

0

1

**A + B**

̅̅̅̅̅̅̅̅

̅

̅

̅ ̅

퐀 + 퐁

퐀

1

1

0

0

퐁

1

0

1

0

퐀 . 퐁

0

1

1

1

1

0

0

0

1

0

0

0

**Circuit Diagram:**



<a name="br2"></a> 

**EXPT. NO: 01**

**DATE:**

**VERIFICATION OF BOOLEAN THEOREMS USING LOGIC GATES**

**(1)** 퐂퐨퐦퐦퐮퐭퐚퐭퐢퐯퐞 퐏퐫퐨퐩퐞퐫퐭퐲: **A + B = B + A**

**Truth Table:**

**A**

0

0

1

1

**B**

0

1

0

1

**A + B**

**B + A**

0

1

1

1

0

1

1

1

**Circuit Diagram:**

**(2)** 퐂퐨퐦퐦퐮퐭퐚퐭퐢퐯퐞 퐏퐫퐨퐩퐞퐫퐭퐲: **A . B = B . A**

**Truth Table:**

**A**

0

0

1

1

**B**

0

1

0

1

**A . B**

**B . A**

0

0

0

1

0

0

0

1

**Circuit Diagram:**



<a name="br3"></a> 

**EXPT. NO: 01**

**DATE:**

**VERIFICATION OF BOOLEAN THEOREMS USING LOGIC GATES**

**(1)** 퐃퐢퐬퐭퐫퐢퐛퐮퐭퐢퐯퐞 퐏퐫퐨퐩퐞퐫퐭퐲: **A + BC = (A + B) (A + C)**

**Truth Table:**

**A**

0

0

0

0

1

1

1

1

**B**

0

0

1

1

0

0

1

1

**C**

0

1

0

1

0

1

0

1

**BC**

0

**A + BC**

**A + B**

**A + C**

**(A + B) . (A + C)**

0

0

0

1

1

1

1

1

0

0

1

1

1

1

1

1

0

1

0

1

1

1

1

1

0

0

0

1

1

1

1

1

0

0

1

0

0

0

1

**Circuit Diagram:**



<a name="br4"></a> 

**EXPT. NO: 01**

**DATE:**

**VERIFICATION OF BOOLEAN THEOREMS USING LOGIC GATES**

**(2)** 퐃퐢퐬퐭퐫퐢퐛퐮퐭퐢퐯퐞 퐏퐫퐨퐩퐞퐫퐭퐲: **A . (B + C) = (A . B) + (A . C)**

**Truth Table:**

**A**

0

0

0

0

1

1

1

1

**B**

0

0

1

1

0

0

1

1

**C**

0

1

0

1

0

1

0

1

**B + C**

**A . (B + C)**

**A . B**

**A . C**

**(A . B) + (A . C)**

0

1

1

1

0

1

1

1

0

0

0

0

0

1

1

1

0

0

0

0

0

0

1

1

0

0

0

0

0

1

0

1

0

0

0

0

0

1

1

1

**Circuit Diagram:**



<a name="br5"></a> 

**EXPT. NO: 02**

**DATE:**

**IMPLEMENTATION OF HALF – ADDER AND FULL – ADDER USING**

**LOGIC GATES**

**(1)** 퐇퐚퐥퐟 − 퐀퐝퐝퐞퐫:

**Truth Table:**

**A**

0

0

1

1

**B**

0

1

0

1

**SUM**

**CARRY**

0

1

1

0

0

0

0

1

**K – Map:**

**SUM**

**CARRY**

**A**

**B**

**A**

**B**

**0**

**1**

**0**

**1**

**0**

**1**

0

1

**0**

**1**

0

0

1

0

0

1

Sum = AB̅ + A̅B = A ⊕ B

**Circuit Diagram:**

Carry = AB



<a name="br6"></a> 

**EXPT. NO: 02**

**DATE:**

**IMPLEMENTATION OF HALF – ADDER AND FULL – ADDER USING**

**LOGIC GATES**

**(2)** 퐅퐮퐥퐥 − 퐀퐝퐝퐞퐫:

**Truth Table:**

**A**

0

0

0

0

1

1

1

1

**B**

0

0

1

1

0

0

1

1

<b>C<sub>in</sub></b>

0

**SUM**

<b>CARRY<sub>out</sub></b>

0

1

1

0

1

0

0

1

0

0

0

1

0

1

1

1

1

0

1

0

1

0

1

**K – Map:**

**SUM**

<b>CARRY<sub>out</sub></b>

<b>BC<sub>in</sub></b>

<b>BC<sub>in</sub></b>

**A**

**00**

**01**

**11**

**10**

**A**

**00**

**01**

**11**

**10**

0

1

0

1

0

0

0

**0**

**1**

**0**

**1**

1

0

1

0

0

1

1

Sum = A̅B̅C + A̅BC̅ + AB̅C̅ + ABC

**Circuit Diagram:**

Carry<sub>out</sub> = AB + AC<sub>in</sub> + BCin



<a name="br7"></a> 

**EXPT. NO: 03**

**DATE:**

**IMPLEMENTATION OF MULTIPLEXER AND DEMULTIPLEXER**

**(1)** ퟒ ∶ ퟏ 퐌퐔퐋퐓퐈퐏퐋퐄퐗퐄퐑:

**Truth Table:**

**S1**

0

**S0**

0

**OUTPUT**

D0

D1

D2

D3

0

1

1

0

1

1

**Circuit Diagram:**



<a name="br8"></a> 

**EXPT. NO: 03**

**DATE:**

**IMPLEMENTATION OF MULTIPLEXER AND DEMULTIPLEXER**

**(2)** ퟏ ∶ ퟒ 퐃퐄퐌퐔퐋퐓퐈퐏퐋퐄퐗퐄퐑:

**Truth Table:**

**SELECTOR LINES**

**OUTPUT**

**S0**

0

**S1**

0

**Y0**

**D**

0

**Y1**

0

**Y2**

0

**Y3**

0

0

1

**D**

0

0

0

1

0

0

**D**

0

0

1

1

0

0

**D**

**Circuit Diagram:**



<a name="br9"></a> 

**EXPT. NO: 04**

**DATE:**

**DESIGN OF D AND JK FLIP FLOPS USING NAND GATES**

**(1)** 퐃 퐅퐋퐈퐏 − 퐅퐋퐎퐏:

**Truth Table:**

**CLOCK**

**D**

0

0

1

1

<b>Q<sub>n</sub></b>

0

<b>Q<sub>n+1</sub></b>

1

1

1

1

0

1

0

1

1

0

1

**Circuit Diagram:**



<a name="br10"></a> 

**EXPT. NO: 04**

**DATE:**

**DESIGN OF D AND JK FLIP FLOPS USING NAND GATES**

**(2)** 퐉퐊 퐅퐋퐈퐏 − 퐅퐋퐎퐏:

**Truth Table:**

**CLOCK**

**J**

0

0

1

1

**K**

0

<b>Q<sub>n+1</sub></b>

Q<sub>n</sub>

0

**STATE**

No Change

Reset (0)

Set (1)

1

1

1

1

1

0

1

1

̅

Q

Toggle

n

**Circuit Diagram:**



<a name="br11"></a> 

**EXPT. NO: 05**

**DATE:**

**IMPLEMENTATION OF SISO AND PIPO SHIFT REGISTER**

**USING FLIP - FLOPS**

**(1)** 퐒퐈퐒퐎 퐒퐇퐈퐅퐓 퐑퐄퐆퐈퐒퐓퐄퐑 퐔퐒퐈퐍퐆 퐃 퐅퐋퐈퐏 − 퐅퐋퐎퐏:

**Truth Table:**

**CLOCK**

Initially

<b>Q<sub>0</sub></b>

0

<b>Q<sub>1</sub></b>

0

<b>Q<sub>2</sub></b>

0

<b>Q<sub>3</sub></b>

0

1<sup>st</sup> falling edge

2<sup>nd</sup> falling edge

3<sup>rd</sup> falling edge

4<sup>th</sup> falling edge

1

0

0

0

1

1

0

0

1

1

1

0

1

1

1

1

**Circuit Diagram:**



<a name="br12"></a> 

**EXPT. NO: 05**

**DATE:**

**IMPLEMENTATION OF SISO AND PIPO SHIFT REGISTER**

**USING FLIP - FLOPS**

**(2)** 퐏퐈퐏퐎 퐒퐇퐈퐅퐓 퐑퐄퐆퐈퐒퐓퐄퐑 퐔퐒퐈퐍퐆 퐃 퐅퐋퐈퐏 − 퐅퐋퐎퐏:

**Truth Table:**

**DATA INPUT**

**OUTPUT**

<b>Q<sub>1</sub> Q<sub>2</sub></b>

**CLOCK**

<b>D<sub>0</sub></b>

1

<b>D<sub>1</sub></b>

0

<b>D<sub>2</sub></b>

0

<b>D<sub>3</sub></b>

1

<b>Q<sub>0</sub></b>

1

<b>Q<sub>3</sub></b>

1

1

2

0

0

0

1

1

0

1

0

1

0

**Circuit Diagram:**



<a name="br13"></a> 

**EXPT. NO: 06**

**DATE:**

**CONSTRUCTION AND VERIFICATION OF 4 – BIT RIPPLE COUNTER**

**(1)** ퟒ − 퐁퐈퐓 퐑퐈퐏퐏퐋퐄 퐔퐏 퐂퐎퐔퐍퐓퐄퐑:

**Truth Table:**

**CLOCK PULSES**

<b>D<sub>3</sub></b>

0

0

0

0

0

0

0

0

1

1

1

1

1

1

1

1

<b>D<sub>2</sub></b>

0

0

0

0

1

1

1

1

0

0

0

0

1

1

1

1

<b>D<sub>1</sub></b>

0

0

1

1

0

0

1

1

0

0

1

1

0

0

1

1

<b>D<sub>0</sub></b>

0

1

0

1

0

1

0

1

0

1

0

1

0

1

0

1

**Initially (0)**

**1**

**2**

**3**

**4**

**5**

**6**

**7**

**8**

**9**

**10**

**11**

**12**

**13**

**14**

**15**

**Circuit Diagram:**



<a name="br14"></a> 

**EXPT. NO: 06**

**DATE:**

**CONSTRUCTION AND VERIFICATION OF 4 – BIT RIPPLE COUNTER**

**(2)** ퟒ − 퐁퐈퐓 퐑퐈퐏퐏퐋퐄 퐃퐎퐖퐍 퐂퐎퐔퐍퐓퐄퐑:

**Truth Table:**

**CLOCK PULSES**

<b>D<sub>3</sub></b>

0

1

1

1

1

1

1

1

1

0

0

0

0

0

0

0

<b>D<sub>2</sub></b>

0

1

1

1

1

0

0

0

0

1

1

1

1

0

0

0

<b>D<sub>1</sub></b>

0

1

1

0

0

1

1

0

0

1

1

0

0

1

1

0

<b>D<sub>0</sub></b>

0

1

0

1

0

1

0

1

0

1

0

1

0

1

0

1

**Initially**

**1**

**2**

**3**

**4**

**5**

**6**

**7**

**8**

**9**

**10**

**11**

**12**

**13**

**14**

**15**

**Circuit Diagram:**



<a name="br15"></a> 

**EXPT. NO: 07**

**DATE:**

**DESIGN AND IMPLEMENTATION OF 2 - BIT ALU USING**

**VARIOUS COMBINATIONAL CIRCUITS**

ퟐ − 퐁퐈퐓 퐀퐑퐈퐓퐇퐌퐄퐓퐈퐂 퐋퐎퐆퐈퐂 퐔퐍퐈퐓:

**Circuit Diagram:**

