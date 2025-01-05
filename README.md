# Off-by-one error in VHDL counter reset

This repository demonstrates a common off-by-one error in VHDL code, specifically within a counter's reset condition.  The `buggy_counter.vhdl` file contains the erroneous code, while `fixed_counter.vhdl` provides the corrected version.

## Problem
The original VHDL code for a simple counter contains a subtle error in how the reset condition is handled.  Under certain circumstances, the counter may fail to reset correctly, leading to unexpected behavior and potential system errors.

## Solution
The corrected code in `fixed_counter.vhdl` addresses the issue by properly handling the reset condition, ensuring the counter always resets to 0 when the reset signal is asserted.