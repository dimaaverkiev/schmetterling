#schmetterling



Sun Jan 19 21:30:51 CET 2025
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.0  21900 13172 ?        Ss   20:27   0:00 /sbin/init
root           2  0.0  0.0   2616  1444 ?        Sl   20:27   0:00 /init
root           6  0.0  0.0   2616   132 ?        Sl   20:27   0:00 plan9 --control-socket 6 --log-level 4 --server-fd 7 --pipe-fd 9 --log-truncate
root          48  0.0  0.1  66824 17784 ?        S<s  20:27   0:00 /usr/lib/systemd/systemd-journald
root          92  0.0  0.0  23980  5888 ?        Ss   20:27   0:00 /usr/lib/systemd/systemd-udevd
systemd+     135  0.0  0.0  21452 11908 ?        Ss   20:27   0:00 /usr/lib/systemd/systemd-resolved
systemd+     136  0.0  0.0  91020  6520 ?        Ssl  20:27   0:00 /usr/lib/systemd/systemd-timesyncd
root         142  0.0  0.0   4236  2680 ?        Ss   20:27   0:00 /usr/sbin/cron -f -P
message+     143  0.0  0.0   9620  5368 ?        Ss   20:27   0:00 @dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation --syslog-only
root         154  0.0  0.0  17976  8232 ?        Ss   20:27   0:00 /usr/lib/systemd/systemd-logind
root         159  0.0  0.0 1756096 15768 ?       Ssl  20:27   0:00 /usr/libexec/wsl-pro-service -vv
root         165  0.0  0.0   3160  1160 hvc0     Ss+  20:27   0:00 /sbin/agetty -o -p -- \u --noclear --keep-baud - 115200,38400,9600 vt220
root         169  0.0  0.0   3116  1212 tty1     Ss+  20:27   0:00 /sbin/agetty -o -p -- \u --noclear - linux
syslog       182  0.0  0.0 222508  5284 ?        Ssl  20:27   0:00 /usr/sbin/rsyslogd -n -iNONE
root         193  0.0  0.1 107012 22912 ?        Ssl  20:27   0:00 /usr/bin/python3 /usr/share/unattended-upgrades/unattended-upgrade-shutdown --wait-for-signal
root         283  0.0  0.0   2620   124 ?        Ss   20:27   0:00 /init
root         284  0.0  0.0   2620   128 ?        S    20:27   0:00 /init
dimi         285  0.0  0.0   7640  6892 pts/0    Ss   20:27   0:00 -bash
root         286  0.0  0.0   6820  4724 pts/1    Ss   20:27   0:00 /bin/login -f
dimi         375  0.0  0.0  20252 11524 ?        Ss   20:27   0:00 /usr/lib/systemd/systemd --user
dimi         376  0.0  0.0  21144  1724 ?        S    20:27   0:00 (sd-pam)
dimi         391  0.0  0.0   6072  5236 pts/1    S+   20:27   0:00 -bash
polkitd      695  0.0  0.0 308160  7140 ?        Ssl  20:44   0:00 /usr/lib/polkit-1/polkitd --no-debug
dimi        1371  0.0  0.0   8280  4132 pts/0    R+   21:31   0:00 ps aux
