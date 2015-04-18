We extend TEMU, a whole-system dynamic binary
analysis platform, to perform taint analysis on linux system calls.
we intercept system calls in TEMU’s
instrumentation to obtain real-time system call information
including the system call numbers, arguments, and returns.
We then label the return values and out-arguments of all
system calls as taint sources. Please see our paper:

Towards Ground Truthing Observations in Gray-Box Anomaly Detection
Jiang Ming, Haibin Zhang and Debin Gao
In Proceedings of the 5th International Conference on Network and System Security (NSS 2011), Milan, Italy, September 2011.