# UniversalFA
A universal finite automata that simulates finite state automatas. Given an input file with a set of states, a set of final states, an alphabet set, and a sequence of transitions, this universal finite automata will be able to recognize whether or not a string belongs to the given language. 

Input File Format:
1) set of states: {state 0, state1}, initial state is 0 (default).
2) set of final state(s): {state 1}
3) alphabet set: {c, d}
4) transitions:
    0 c 0
    0 d 1
    1 c 0
    1 d 1
5) Test strings:
    dccc
    dcccd
    ...

Provided is the main fa.cpp file with implementation of the universal finite automata. Four finite automata files (m1.txt, m2.txt, etc.) are also provided for testing. 
