# core_handler
A core file handler that takes a snapshot of /proc/PID before generating core.

## Usage
* Build core_handler
* echo "|/home/kai/program/core_handler/core_handler %p %u %s %t %e /home/kai" > /proc/sys/kernel/core_pattern
* ulimit -c unlimited
