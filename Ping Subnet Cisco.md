1. **Enter TCL Scripting Mode**:
   ```
   tclsh
   ```

2. **Run the TCL Script**:
   ```
   for {set i 1} {$i < 255} {incr i} { ping 192.168.1.$i }
   ```

This script will ping all IP addresses in the subnet.
