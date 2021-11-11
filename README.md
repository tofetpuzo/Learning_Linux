# Learning_Linux
Project 5: Learning Linux Admin

Kernel
The core of UNIX system. Loaded at system start-up(boot) Memory resident control program.

Manages the entire resources of the system, presenting them to you and every other user as a coherent system. Provides services to user applications such as device management, process scheduling etc.

Examples function performed by the kernek are:

Managing the machine's memory and allocating it to each process.
Scheduling the work done by the CPU so that the work of each user is out as efficiently as is possible.
Accomplishing the transfer of data from one part of the machine to another
Interpreting and executing instructions from the shell

Enforcing file access permissions



SHELL
Whenever you login to a UNIX system you are placed in a shell program. The shell's prompt is usually visibke at the cursor's position on your screen. To get your work done, you enter commands at this prompt.

The shell is a command interpreter; it takes each command and passes it to the operating system kernel to be acted upon. It then displays the results of this operation to your screen.

Several shells are usualy available on any UNIX system, each with its own strengths and weaknesses.

Different users may use differnet shells, initially your system adminsitrator will supply a default shell, which can be overridden or changed. The most commonly avaliable shells are Bourne shell (sh), c shell(csh) korn shell(ksh) TC shell(tcsh) Bourne Again Shell(bash)

Each shell also includes its own programming lanaguage. Command files called "shell scripts" are used to acoomplish a series of tasks.
