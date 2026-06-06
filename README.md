# Research Paper: REAL-TIME-MELODY-PLAYBACK-ON-FPGA-USING-FSM-DRIVEN-AUDIO-SYNTHESIS
An FPGA-based music synthesis system that generates and plays the Imperial March theme using a Finite State Machine (FSM) and Verilog HDL on an Artix-7 FPGA platform.

# Authors
- Dr. Tammisetti Ashok
- Gandham Saritha
- Chennamsetti Likhitha
- Chintala Akanksha
- Kalavakollu Srinu
- Datti Varun Teja

## Published In
InternationalJournal of Innovative Research in Technology (IJIRT)

## Publication Link
[View Published Paper] (https://ijirt.org/article?manuscript=192655)
  
## Abstract
This paper presents a real-time melody playback system implemented on an FPGA us- infinite state machine (FSM)-driven audio synthesis. The proposed architecture employs Verilog HDL to design dedicated frequency generator modules for musical notes, each producing square waves at precisely calculated intervals. These modules are sequenced through a robust FSM that controls note transitions and timing delays, enabling accurate and synchronized melody generation. The system operates using a single push-button input, stabilized by a hardware de- bounce circuit based on a multi-stage shift register. Cycle-accurate counters generate control flags to regulate note durations and rest intervals, providing fine-grained timing resolution without relying on software processing. The design has been successfully implemented on the Basys 3 FPGA development board with minimal hardware resource utilization. Each FSM state corresponds to a specific musical note or pause, and output signals are selected using a multiplexer-based routing structure to drive the speaker interface. Simulation and experimental hardware results validate the reliability of the proposed system, demonstrating clear tonal output and precise rhythmic spacing. The modular and scalable architecture enables easy reconfiguration and reuse for various embedded audio applications. By implementing melody generation entirely in hardware, this work highlights the efficiency and determinism of FPGA-based audio systems and provides a foundation for future enhancements such as multi-channel synthesis, tempo control, and MIDI interface integration.
  
## Keywords
FPGA Verilog HDL Melody Playback Finite State Machine Audio Synthesis Frequency Generation Real-Time Systems Embedded Audio.

## Features
- Real-time melody playback on FPGA
- FSM-based note sequencing
- Verilog HDL implementation
- Parameterized frequency generation
- Artix-7 FPGA compatible

## Technologies Used
- Verilog HDL
- FPGA (Artix-7)
- Finite State Machine (FSM)
- Vivado Design Suite

