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
Recv: echo:  M92 X80.00 Y80.00 Z400.00 E93.00
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z5.00 E25.00
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X500 Y500 Z100 E1000
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P500.00 R500.00 T1000.00
Recv: echo:Advanced: S<min_feedrate> T<min_travel_feedrate> B<min_segment_time_us> X<max_xy_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 S0.00 T0.00 B20000 X10.00 Y10.00 Z0.40 E5.00
Recv: echo:Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:Material heatup parameters:
Recv: echo:  M145 S0 H185 B45 F0
Recv: echo:  M145 S1 H240 B70 F0
Recv: echo:PID settings:
Recv: echo:  M301 P23.81 I1.93 D73.64
Recv: echo:Stepper driver current:
Recv: echo:  M906 X 650 Y 650 Z 650 E0 800
Recv: ok
```
