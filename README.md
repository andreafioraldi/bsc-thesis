# Symbolic Execution and Debugging Synchronization

This is my Bsc thesis.

>In this thesis, we introduce the idea of combining symbolic execution with dynamic analysis for reverse engineering.
>The synchronization between a debugger and a symbolic executor can enhance manual dynamic analysis and allow a reverser to easily solve small portions of code without leaving the debugger.
>We implemented a synchronization mechanism on top of the binary analysis framework angr, allowing for transferring the state of the debugged process to the angr environment and back.
>The backend library is debugger agnostic and can be extended to work with various frontends.
>We implemented a frontend for the IDA Pro debugger and one for the GNU Debugger, which are both widely popular among reverse engineers.


ResearchGate page: [https://www.researchgate.net/publication/327655380_Symbolic_Execution_and_Debugging_Synchronization](https://www.researchgate.net/publication/327655380_Symbolic_Execution_and_Debugging_Synchronization)

Advisor: [Prof. Camil Demetrescu](https://github.com/camild)

Co-Advisors: [Dr. Emilio Coppa](https://github.com/ercoppa), [Dr. Daniele Cono D’Elia](https://github.com/dcdelia)

### Cite

You can use the following bibtex entry (it's a workaround to cite a bsc thesis):

```
@mastersthesis{Fioraldi:BscThesis:2018,
    author = {Andrea Fioraldi},
    title = {{Symbolic Execution and Debugging Synchronization}},
    school = {Sapienza University of Rome},
    month = {October},
    year = {2018},
    type = {{Bachelor's thesis}},
}
```

