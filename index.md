Dreaming of [The Perfect Computer](https://github.com/ThePerfectComputer)
 - Memory safe kernel written in Rust
 - Rust is the primary application development language
 
   which would include a completely self hosting Rust 

   compiler, enabled by replace GGC binutils with Cranelift.
 - GUI as beautiful as MacOS
 - Open Source Silicon
 - Open source chip and auditable PHY firmware - enabling

   auditing for firmware backdoors, see:
   1. https://youtu.be/bfPV4x-HrUI?t=2194
   2. https://youtu.be/bfPV4x-HrUI?t=2309
 - Cargo as package manager.
 - No electron. Anywhere.

# Current Work

Currently building [FastWave](https://github.com/ThePerfectComputer/FastWave), a VCD parser written in Rust intended to be the backend of a digital logic Waveform Viewer(built in [egui](https://www.egui.rs)). The waveform veiwer will support dynmically loading Rust code for analysis of loaded waveforms.
