# Java OOP Coursework

Java laboratory exercises covering input, algorithms, encapsulation, interfaces and inheritance.

## Contents

| Folder / file | Topic | Technologies |
| --- | --- | --- |
| `Lab-04` | Temperature conversion with file output, three-value min/max, buffered input, and parity exercises. | Java |
| `Lab-06` | Parity checks, argument parsing, factorial and palindrome programs. | Java |
| `Lab-08` | Employee, rectangle, circle encapsulation, and mortgage demonstration programs. | Java |
| `Lab-07-Account` | Account class validates deposit/withdrawal amounts and a console client exercises two accounts. | Java |
| `Movable-Point` | Movable interface and point implementation support console-selected directional moves. | Java |
| `Lab-10-Police` | Abstract police class and patrolman/sergeant/lieutenant inheritance compute earnings and benefits. | Java |
| `Ship-Inheritance` | Ship, cruise-ship and cargo-ship classes override descriptions and are printed polymorphically. | Java |

Each folder is an independent exercise or project. Original names, source, dependency versions and required project configuration are preserved.

## Getting Started

Use JDK 17 or a compatible JDK. In an exercise folder, create `out`, then run `javac -encoding UTF-8 -d out *.java` and `java -cp out ClassName` for its entry point. For example, in `Lab-06`, run `java -cp out FactorialCalculator`. Other entry points include `AccountTest` (Lab-07), `EmployeeClient` and `TestRectangle` (Lab-08), `TestMovable` and `ShipDemo`. `task1.java` in Lab-04 is a helper rather than an entry point. Lab-07-Account stores source under `src`. For Lab-10-Police, compile the Java files from all five subdirectories together into `out`; run `java -cp out TestPolice`. Do not combine unrelated exercise folders into one Java compilation.

## Validation

Lightweight local checks: Java 17 compilation. Compilation and syntax checks do not verify application behavior. Source is preserved; interactive application behavior was not executed during archival.

## Notes

Original implementation is preserved. Build outputs, dependencies, machine-specific IDE state, backups, submission documents and private runtime data are excluded. No license has been inferred for the original work.
