# DecimalToRomanNumsRISC
This program is written for a RISC-V processor developed at University of Zagreb Faculty of Electrical Engineering and Computing for learning purposes.<br>

The most important parts of syntax for undestanding this code: <br>
<br><b>lui</b><br>
- used for loading values in a register <br>
- if a value is big, it loads higher 32 bits (%hi), then lower (%lo) and then adds the two values <br>

<br><b>addi</b><br>
- adds a specified value; if a value is stored in a register, a regular add function is used <br>
- also used for subtracting <br>

<br><b>jal</b><br>
- jump and link: used for entering a function

<br><b>jalr</b><br>
- return from a function
  
<br><b>b[condition]</b><br>
- branch, conditions are just as conditions in ARM assembly:<br>
lt - less than<br>
ge - greater or equal to <br>
ne - not equal to <br>
eq - equal to <br>

<br><b>s[b|h|w][condition]</b><br>
- stores a byte/halfword/word

<br><b>halt</b><br>
- terminates the execution of a program
<br><br>

LCDWR is a program written particulary for students' simulator of assembler and its deeper understanding is not relevant for this code. 



