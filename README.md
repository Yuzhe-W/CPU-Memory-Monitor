# CPU-Memory-Monitor
Amonitor CPU and Memory Usage for a given process id:

Use the given process id to get CPU, Memory usage information from /proc system
Then calculate the usage of CPU and Memory and check if the usage exceed the threshold,
If it exceeds, use mailx command to send an email to user.

./monitor.sh {process id} -cpu {cpu usage percentage} {maximum reports} {time interval}
./monitor {process id} -cpu {cpu usage percentage} -mem {maximum memory in kB} {maximum reports} {time interval}
