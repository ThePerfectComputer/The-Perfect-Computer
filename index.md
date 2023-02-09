Dreaming of [The Perfect Computer](https://github.com/ThePerfectComputer)
 - Memory safe kernel written in Rust
 - Rust is the primary application development language.
 - Completely self hosting Rust compiler, enabled by replacing GGC binutils with Cranelift.
 - GUI as beautiful as MacOS
 - Open source Silicon - digital logic components design in Bluespec Haskell
 - Auditable PHY firmware, needed for auditing for backdoors, see:
   1. [Intel Management Engine](https://youtu.be/bfPV4x-HrUI?t=2194)
   2. [Leaking Cryptographic Keys in SGX](https://youtu.be/bfPV4x-HrUI?t=2309)
 - Cargo as package manager.
 - No electron. Anywhere.

# Current Work

Currently building [FastWave](https://github.com/ThePerfectComputer/FastWave), a VCD parser written in Rust intended to be the backend of a digital logic Waveform Viewer(built in [egui](https://www.egui.rs)). The waveform veiwer will support dynmically loading Rust code for analysis of loaded waveforms.
