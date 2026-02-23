# CVE2009-2585_HP_Power_Manager_BoF
This repository contains a Python proof-of-concept exploit for a stack-based buffer overflow in HP Power Manager’s web interface. A crafted HTTP request can overwrite memory and allow remote code execution, potentially leading to SYSTEM-level access on vulnerable Windows machines.

Now, you can launch the exploit:

python CVE2009-2585_HP_Power_Manager_BoF.py IP 
