# Linux-Shell
Personal Linux Shell with Job Control

This Project has been undertaken in order to solve the Popular Tiny Shell Project offered in the System Software Course in Carnegie Mellon University (CMU), Pittsburgh.

Files:

Makefile	# Compiles your shell program and runs the tests
README		# This file
tsh.c		# The shell program that you will write and hand in
tshref		# The reference shell binary.

The remaining files are used to test your shell: <br><br>
sdriver.pl	# The trace-driven shell driver
trace*.txt	# The 15 trace files that control the shell driver
tshref.out 	# Example output of the reference shell on all 15 traces

Little C programs that are called by the trace files: <br><br>
myspin.c	# Takes argument <n> and spins for <n> seconds
mysplit.c	# Forks a child that spins for <n> seconds
mystop.c        # Spins for <n> seconds and sends SIGTSTP to itself
myint.c         # Spins for <n> seconds and sends SIGINT to itself

Author:<br>
Shaleen Kumar Gupta<br>
B.Tech. (Hons. in ICT with minors in CS)<br>
Dhirubhai Ambani Institute of Information and Communication Technology, Gandhinagar<br>
E-mail: shaleenx [at] gmail [dot] com
