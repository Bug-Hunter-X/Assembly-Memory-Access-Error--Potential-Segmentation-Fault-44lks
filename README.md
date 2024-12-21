# Assembly Memory Access Bug

This repository demonstrates a common error in assembly programming: an unchecked memory access that can lead to segmentation faults. The `bug.asm` file contains the erroneous code.  The `bugSolution.asm` file shows a corrected version that includes necessary bounds checking. 

**The bug:** The code attempts to access memory without verifying that the calculated address is valid. This can cause crashes if the address falls outside the allocated memory region.

**The solution:** The corrected code adds checks before the memory access to ensure the address is within bounds, thereby preventing segmentation faults.