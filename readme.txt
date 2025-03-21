Fizbo 2, released on 12/17/2017

It was compiled with MS VC 2017 on Windows 8.

Solution "engine" generates executable that plays games; it includes UCI protocol interface. For that solution to compile, in file chess.h ENGINE has to be defined as 1.

Solution "chess" generates executable used for development work; it includes GUI with benchmarking and training functions. For that solution to compile, in file chess.h ENGINE has to be defined as 0.

