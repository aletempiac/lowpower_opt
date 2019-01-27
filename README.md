# Low Power Optimization

Scripts written in TCL to be run into Synopsys PrimeTime.
The scripts switch cells from low threshold voltage `LVT` to high threshold voltage `HVT` in a synthesized design to meet a power reduction factor. It tries to keep the timing of the design as stable as possible working on the slack and, at the same time, be efficient in the elaboration time.
