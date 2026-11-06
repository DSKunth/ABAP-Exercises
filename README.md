# ABAP Basics Exercises

Small practice programs from my first steps in ABAP, written as global classes that run in the ADT console (F9) on the SAP BTP ABAP environment (trial).

## Exercises (package `ZS4D100_EXERCISES`)

| Class | Topic |
|---|---|
| `ZCL_S4D100_27_CHAR` | character strings |
| `ZCL_S4D100_27_COND` | conditional branching |
| `ZCL_S4D100_27_DO_ENDDO` | `DO ... ENDDO` loops |
| `ZCL_S4D100_27_EXIT` | leaving a loop on a condition |
| `ZCL_S4D100_27_DUMP` | provoking and analyzing a runtime error |
| `ZCL_S4D100_27_HELLO_WORLD` | Hello World |
| `ZCL_SD400_HELLO_WORLD` | Hello World (first class) |

## How to run

Each class implements `IF_OO_ADT_CLASSRUN`. Open it in Eclipse (ADT), activate it with **Ctrl+F3**, and run it with **F9**. The output appears in the ABAP Console.

## About this repository

- The `src` folder is in abapGit format. Import it with abapGit instead of editing the files by hand.
- These are learning exercises, so the code favors clarity over completeness.
