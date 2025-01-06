This repository contains a demonstration of a common error in VHDL code: an integer overflow in a counter. The `buggy_counter.vhdl` file shows the erroneous code, and `fixed_counter.vhdl` provides a corrected version.

The bug arises from the lack of handling for the scenario when the counter reaches its maximum value.  A simple solution involves adding a check to prevent this overflow.

This example highlights the importance of careful consideration of boundary conditions in digital design.