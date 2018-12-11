# AutoPythonTTY
This script automates the boring part of getting a full TTY in a Linux box with Python after getting a shell with netcat.

Client side command to get a full TTY on reverse netcat connection:

```bash
source autotty <port>
```

*source is required to have job control inside the script for the foreground (fg) trick