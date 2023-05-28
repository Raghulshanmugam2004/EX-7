# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
# DATE :20-04-2023

# AIM :
To write the python program for simulating Traceroute command

# ALGORITHM :

1.Start the program.

2.Get the frame size from the user.

3.To create the frame based on the user request.

4.To send frames to server from the client side.

4.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client. Stop the program

# PROGRAM :
```
# Developed By : RAGHUL.S
# Register Number : 212222040128
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
# OUTPUT :
![image](https://github.com/Raghulshanmugam2004/EX-7/assets/119561118/6ccaa602-5846-4f2c-ab73-9411446800c4)
# RESULT :
Thus, the python program for simulating Traceroute command was successfully executed.
