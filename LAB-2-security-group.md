Lab 2: HTTP Port Block

 What I did
Removed HTTP (port 80) rule in AWS Security Group.

 Result
Website became unreachable from browser.

 Diagnosis
Confirmed security group rules blocked traffic.

 Fix
Re-added HTTP rule (port 80 open to internet).
