# turntable

You need an arduino uno (or similar) to hook this to a continuous servo.

Note, you do have to know what dev/tty the uno hooks up to, but it should be obvious if you do "ls /dev/tty.*"  for me it's "/dev/tty.usbmodem1411".  You need to put that in the server code (along with the ip & port you're using... client just needs ip & port).
