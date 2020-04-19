# 3D-printer-hacks
small 3d printers hacks

# Anet et4 Laser fixes

LASER - M106
POWER - S0 to S255  (o to max re)
PAUSE FOR 0.1 sec - G04 P100

Add a delay on every laser start and stop

- M106 S0 or M106 S255

G04 P100
M106 S0


and 

G04 P100
M106 S255
