# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

(Add screenshot here)

### Questions

1.  How many users exist on the system? 2
2.  Which accounts appear to be system accounts? group3 and group53
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.
to be able to identify potential threats
------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot

(Add screenshot here)

### Questions

1.  Which processes are running as `root`? system processes
2.  Why can processes running as root be dangerous? highest privilege so dangerous if taken over
3.  What could happen if a malicious program ran with root privileges? could steal data, delete files or take control of the system

### Reflection

What did you learn about system processes and security?
i learned that processes have different permissions and root processes need extra security
------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(Add screenshot here)

### Questions

1.  Which ports are open?5353, 53761, 111, 22, 5201
2.  Which services appear to be listening? tcp
3.  Why might open ports represent a security risk? hackers could exploit vulnerable services through open ports

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
