# MET-reverse-robot01
MET drivebase unit final deviation test code

NOTE: this robot code assumes that the motors are plugged in standard (left: port 10 and right: port 1) but
that the drive train either contains an even number of gears driving motor to wheel or for some other reason
is flipped.

This is the test code which should be placed on the students drivebase to perform the two class/lab exit tests:
1 - drivebase deviation test
2 - driving obstacle course

The program can trigger two modes via the remote:
Y - button pressed: Robot is under full joystick control
A - button pressed robot will execute a 5m straight drive, robot maybe stopped by pressing the X button on remote eStop)
