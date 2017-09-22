# core_handler
A core file handler that takes a snapshot of /proc/PID before generating core.

Usage:
    1. Build core_handler
    2. echo "|/home/kai/program/core_handler/core_handler %p %u %s %t %e /home/kai" > \
       /proc/sys/kernel/core_pattern
    3. ulimit -c unlimited
