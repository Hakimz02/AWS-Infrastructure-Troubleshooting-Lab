Lab 3: SSH Access Failure

 What I did
Changed/removed SSH security group rule.

 Result
SSH connection timed out.

 Diagnosis
Security group blocked port 22 access.

 Fix
Restored SSH rule with correct IP /32.
