# RISC-V Tapeout Program
<details>
<summary> Week 0 - Open-Source tools Installation </summary>
  <br>
  <p> In this phase of the program we focus on establishing a robust and efficient development environment. This was accomplished by installing a suite of essential open-source tools to be used for all subsequent Simulation, Synthesis and Physical design. In order to install the open-source tools, it is required to setup Ubuntu in Orcale Virtualbox.
   <h2>Tool includes:-</h2>
  </p>
<ol>
  <li>Yosys</li>
  <li>iverilog</li>
  <li>gtkwave</li>
  <li>magic</li>
  <li>ngspice</li>
  <li>OpenLane</li>
  <li>OpenSTA</li>
</ol>
  
<h2>Yosys Open Synthesis suite</h2>
  Yosys (Yosys Open Synthesis Suite) is a foundational open-source tool for performing digital hardware synthesis. It translates higher-level hardware description languages (HDL), primarily Verilog, into a lower-level, gate-level netlist.
  <p>
 <pre>$ git clone https://github.com/YosysHQ/yosys.git 
$ cd yosys 
$ sudo apt install make # (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \ 
  libreadline-dev gawk tcl-dev libffi-dev git \ 
  graphviz xdot pkg-config python3 libboost-system-dev \ 
  libboost-python-dev libboost-filesystem-dev zlib1g-dev 
$ make 
$ sudo make install </pre>

</p>
<h2>Iverilog</h2>
Icarus Verilog, commonly known as iVerilog, is a popular, open-source compiler and simulation tool for the Verilog Hardware Description Language (HDL). 
  Steps to install iverilog are:
  <p>
    <pre>sudo apt-get update
sudo apt-get install iverilog     </pre>
  </p>

  <h2>gtkwave</h2>
  gtkwave is an open-source, cross-platform waveform viewer used primarily for debugging and verifying digital logic designs. It provides a graphical interface for analyzing the signal data produced by hardware description language (HDL) simulations. Steps to install gtkwave are:
  <p>
    <pre>sudo apt-get update
sudo apt-get install iverilog    </pre>

</details>
