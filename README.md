# ampy-wsl
Bash Shim to call adafruit-ampy while running under wsl (Windows Linux Subsystem).

Since wsl (Windows Linux subsystem does not allow access to the USB to use the CP210x driver across USB.

This shim will call ampy under powershell to access the COMx port.

Arguments are modeled after idfx:

ampy-wsl command COMx 

  where "command":  
     get   
     ls  
     mkdir  
     put  
     reset  
     rm  
     rmdir  
     run  
