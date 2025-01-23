# Instructions for Using the Reverse String Library

To use the `reverseLib` in your project, follow these steps:

1. **Download and Include Files**:  
   - Download the `reverseLib.asm` and `reverseLib.inc` files and include them in your `Irvine` folder where you have the `Irvine32` library.
   - You can download the Irvine library from [this link](https://github.com/Zain-Zameer/irvine).

2. **Modify Your Assembly Code**:  
   - In your assembly code, after the line `INCLUDE Irvine32.inc`, add the following line to include the reverse string functionality:
     ```asm
     INCLUDE reByte.inc
     ```

3. **Add `reByte.lib` in Project Settings**:  
   - Go to **Project Properties** in Visual Studio.
   - Navigate to **Linker > Input**.
   - In the **Additional Dependencies** section, add `reByte.lib`.

Now you can call the `ReverseString` procedure in your project to reverse strings easily.
