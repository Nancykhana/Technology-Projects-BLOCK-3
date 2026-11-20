# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

(Add screenshot here)<img width="1710" height="1318" alt="image" src="https://github.com/user-attachments/assets/38f41d29-0110-453b-89ab-49b35f2a510a" />


### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot <img width="2592" height="1428" alt="image" src="https://github.com/user-attachments/assets/31e1b6bd-bae7-4c39-bcf1-792cda012848" />

(Add screenshot here)

### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot <img width="1568" height="442" alt="image" src="https://github.com/user-attachments/assets/39c6cabe-ea95-400d-96ea-61c300696086" />


(Add screenshot here)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
