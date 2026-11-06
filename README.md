# ABAP Basics Exercises

Small practice programs from my first steps in ABAP, written as global classes that run in the ADT console (F9) on the SAP BTP ABAP environment (trial).

## Exercises (package `ZS4D100_EXERCISES`)

| Class | Topic |
|---|---|
| `ZCL_S4D100_27_CHAR` | Process character strings |
| `ZCL_S4D100_27_COND` | Implement conditional logic |
| `ZCL_S4D100_27_DO_ENDDO` | Implement loop |
| `ZCL_S4D100_27_EXIT` | Implement a DO – ENDDO loop with an abort condition |
| `ZCL_S4D100_27_DUMP` | Use conditional logic to avoid a runtime error |
| `ZCL_S4D100_27_HELLO_WORLD` | Hello World app |
| `ZCL_SD400_HELLO_WORLD` | Hello World (first class) |

## How to run

Each class implements `IF_OO_ADT_CLASSRUN`. Open it in Eclipse (ADT), activate it with **Ctrl+F3**, and run it with **F9**. The output appears in the ABAP Console.

## About this repository

- The `src` folder is in abapGit format. Import it with abapGit instead of editing the files by hand.
- These are learning exercises, so the code favors clarity over completeness.
