# Configuration

```
Send: M503
Recv: echo:  G21    ; Units in mm
Recv: echo:  M149 C ; Units in Celsius
Recv: 
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D1.75
Recv: echo:  M200 D0
Recv: echo:Steps per unit:
Recv: echo:  M92 X80.00 Y80.00 Z800.00 E100.00
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z10.00 E50.00
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X500 Y500 Z100 E5000
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P500.00 R1000.00 T500.00
Recv: echo:Advanced: S<min_feedrate> T<min_travel_feedrate> B<min_segment_time_ms> X<max_xy_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 S0.00 T0.00 B20000 X8.00 Y8.00 Z0.40 E5.00
Recv: echo:Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:Auto Bed Leveling:
Recv: echo:  M420 S1 Z2.00
Recv: echo:PID settings:
Recv: echo:  M301 P14.72 I0.89 D61.22
Recv: echo:Z-Probe Offset (mm):
Recv: echo:  M851 Z-2.20
Recv: ok
```
