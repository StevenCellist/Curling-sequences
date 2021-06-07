# Curling-sequences
On curling sequences, trying to find a sequence with infinite repetition. Let's crunch some sequences!

Largest generator length achieved: *n* = 345.

Record values:
| *n* |&Omega;(*n*)| | *n* |&Omega;(*n*)| | *n* |&Omega;(*n*)|
|:---:|:---:|---|:---:|:---:|---|:---:|:---:|
|2    |2    |   |48   |131  |   |133  |342  |
|4    |4    |   |68   |132  |   |149  |343  |
|6    |8    |   |73   |133  |   |154  |356  |
|8    |58   |   |77   |173  |   |176  |406  |
|9    |59   |   |85   |178  |   |197  |1668 |
|10   |60   |   |115  |215  |   |199  |1669 |
|11   |112  |   |116  |228  |   |200  |1670 |
|14   |118  |   |118  |229  |   |208  |1708 |
|19   |119  |   |128  |332  |   |217  |1836 |
|22   |120  |   |132  |340  |   |290  |3382 |

GCC flag instructions for Sequences-negative.cpp:
g++ -std=c++11 -march=native -fno-strict-aliasing -pthread -O3 Sequences-negative.cpp

Contributors: Steven Boonstoppel, Vladimir Feinstein, Levi van de Pol
