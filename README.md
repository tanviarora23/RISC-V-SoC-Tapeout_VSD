# RISC-V-SoC-Tapeout_VSD
This program focuses on learning how to design a System-on-Chip (SoC) starting from RTL and progressing to GDSII using open-source tools. It is a part of India’s largest collaborative RISC-V tapeout initiative, involving over 3,500 participants, aimed at enabling silicon development and strengthening the country’s semiconductor ecosystem.

# Step 1 — Setup & Tools Installation
# 1. Yosys
`$ sudo apt-get update  `

`$ git clone https://github.com/YosysHQ/yosys.git ` 

`$ cd yosys `

`$ sudo apt install make (If make is not installed please install it) ` 

`$ sudo apt-get install build-essential clang bison flex \` 

`libreadline-dev gawk tcl-dev libffi-dev git \ `

`graphviz xdot pkg-config python3 libboost-system-dev \ `

`libboost-python-dev libboost-filesystem-dev zlib1g-dev `

`$ make config-gcc` 

`$ make  `

`$ sudo make install `

![](https://github.com/tanviarora23/vsdbbcud4f/blob/master/Layout/Images/Screenshot%20(5367).png)

# 2. iverilog
` $ sudo apt-get update `

` $ sudo apt-get install iverilog  `

![](https://github.com/tanviarora23/vsdbbcud4f/blob/master/Layout/Images/Screenshot%20(5367).png)


# 3. GTK Wave

` $ sudo apt-get update `

` $ sudo apt install gtkwave ` 

![](https://github.com/tanviarora23/RISC-V-SoC-Tapeout_VSD/blob/main/3.png)

#   Key Outcomes

a. Successfully installed and validated open-source EDA tools.

b. Gained hands-on experience with environment setup for RTL design and synthesis.

c. Configured the system to support upcoming RTL-to-GDSII flow experiments.

# Acknowledgment

I express my sincere gratitude to Kunal Ghosh and the VLSI System Design (VSD) team for giving me the opportunity to be part of the ongoing RISC-V SoC Tapeout Program.

I would also like to acknowledge the contributions of RISC-V International, India Semiconductor Mission (ISM), VLSI Society of India (VSI), and Efabless, whose support has made this initiative possible.



