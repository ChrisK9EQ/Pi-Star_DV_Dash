# Pi-Star_DV_Dash
Pi-Star DV Dashboard (Based on works by Hans-J. Barthen (DL5DI) and Kim Huebel (DG9VH)).
Copyright (C) 2019 Chris Petersen K9EQ

This is the Pi-Star dashboard with modifications to simplify the use of Pi-Star and eliminate bugs.
Specifically:
2019-09-23:
Removed from admin/configure.php automatic setting of SelfOnly and DUPLEX. Logic errors would cause SelfOnly to periodically
set itself and make bridging with WiRES-X only work in one direction.

Removed automatic setting of DUPLEX. When Tx != Rx frequency, DUPLEX would automatically be set indicating that the modem was a
duplex modem. Simplex modems are used when bridging to WiRES-X via a repeater.
