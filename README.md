### VictorPurpura with Custom GUI

**Requirements:** None  
**Limitations:** None  

![VictorPurpura with Custom GUI GUI](Victor-Purpura-TCDS-closed-loop-stimulation-protocol.png)

<!--start-->
<p><b>VictorPurpura:</b><br>QWhatsThis description.</p>
<!--end-->

#### Input
1. input(0) - IV : Fish Voltage(V)

#### Output
1. output(0) - Now : detecting time
2. output(1) - output : stimulus generator input
3. output(2) - bit detected : bit detected in window time
4. output(3) - bin : bin
5. output(4) - res : bin
6. output(5) - wtd : bin
7. output(6) - wa : bin
8. output(7) - windowsend : bin
9. output(8) - lat : lat
10. output(9) - sp : sp

#### Parameters
1. Bin Time (ns) - window time
2. Threshold (V) - minimum voltage to detect a spike
3. Word length - number of bits of the word
4. q - similarity constant
5. Limit - distance limit
6. Word - word to detect

#### States

