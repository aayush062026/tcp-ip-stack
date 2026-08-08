# tcp-ip-stack

TCP/IP stack fundamentals and packet processing reference design.

## Overview

Reference implementation of core TCP/IP stack functionality, covering IP header processing, checksum handling, and a TCP connection state machine. Built as a portfolio piece; not derived from any employer or client codebase.

## Planned Features

IP header parsing and checksum verification. IP fragmentation and reassembly basics. TCP connection state machine. Packet buffering and processing datapath.

## Architecture

See docs/ARCHITECTURE.md for the design write-up and docs/BLOCK_DIAGRAM.md for the block diagram.

## Repository Structure

docs/ contains architecture and block diagram documentation. src/rtl/ contains SystemVerilog and Verilog source. src/tb/ contains testbenches and the verification environment.

## Status

Work in progress, portfolio reference implementation.

## Tools

SystemVerilog, Verilog, QuestaSim

## License

MIT, see LICENSE
