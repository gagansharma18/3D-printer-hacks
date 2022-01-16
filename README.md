# 3D-printer-hacks
small 3d printers hacks

# Anet et4 Laser fixes

LASER - M106
POWER - S0 to S255  (o to max re)
PAUSE FOR 0.1 sec - G04 P100

Add a delay on every laser start and stop

- M106 S0 or M106 S255
```
G04 P100
M106 S0
```

and 
```
G04 P100
M106 S255
```
# VSCODE
find
```
M106
```
and replace with 
```
G04 P100
M106
```
#NEW FIX
Increase Rapid movement speed
```
M106 S0 
G0 X12.69 Y126.11 F0
```
here replace F0 to F3000, it means 50mm/sec or 3000mm/sec
```
M106 S0 
G0 X12.69 Y126.11 F3000
```
