# Python — Interview Prep (Beginner to Pro)

Interview-prep docs for **Python**, organized by level: **Beginner** → **Intermediate** → **Advance** → **Expert** → **Pro**. Each level contains nested topic folders with READMEs and content.

---

## Levels and topics

| Level | Topics | Link |
| :--- | :--- | :---: |
| **Beginner** | Fundamentals, Execution Basics, Comments & Docstrings, Input & Output, Operators, Data Types, Data Types Deep Dive, Collections, Control Flow, Conditionals, Loops, Comprehensions, Files, Functions, Command-Line Args, Strings, Modules & Imports, Error Handling, Virtual Environments | [→ Open](Beginner/README.md) |
| **Intermediate** | Object Model, Functions & Decorators, Error Handling | [→ Open](Intermediate/README.md) |
| **Advance** | Context Managers, Iterators & Generators, OOP, Concurrency | [→ Open](Advance/README.md) |
| **Expert** | Metaprogramming, Descriptors, Async Deep Dive | [→ Open](Expert/README.md) |
| **Pro** | Testing, Packaging, Performance, Production Patterns | [→ Open](Pro/README.md) |

---

## Learning path

1. **Beginner** — [Fundamentals](Beginner/Fundamentals/README.md), [Execution Basics](Beginner/Execution-Basics/README.md), [Comments & Docstrings](Beginner/Comments-And-Docstrings/README.md), [Input & Output](Beginner/Input-Output/README.md), [Operators](Beginner/Operators/README.md), [Data Types](Beginner/Data-Types/README.md), [Data Types Deep Dive](Beginner/Data-Types-Deep-Dive/README.md), [Collections](Beginner/Collections/README.md), [Control Flow](Beginner/Control-Flow/README.md), [Conditionals](Beginner/Conditionals/README.md), [Loops](Beginner/Loops/README.md), [Comprehensions](Beginner/Comprehensions/README.md), [Files](Beginner/Files/README.md), [Functions](Beginner/Functions/README.md), [Command-Line Args](Beginner/Command-Line-Args/README.md), [Strings](Beginner/Strings/README.md), [Modules & Imports](Beginner/Modules-And-Imports/README.md), [Error Handling](Beginner/Error-Handling/README.md), [Virtual Environments](Beginner/Virtual-Environments/README.md)
2. **Intermediate** — [Object Model (Identity, Mutability, Memory)](Intermediate/Object-Model/README.md), [Functions & Decorators](Intermediate/Functions-And-Decorators/README.md), [Error Handling](Intermediate/Error-Handling/README.md)
3. **Advance** — [Context Managers](Advance/Context-Managers/README.md), [Iterators & Generators](Advance/Iterators-And-Generators/README.md), [OOP](Advance/OOP/README.md), [Concurrency](Advance/Concurrency/README.md)
4. **Expert** — [Metaprogramming](Expert/Metaprogramming/README.md), [Descriptors](Expert/Descriptors/README.md), [Async Deep Dive](Expert/Async-Deep-Dive/README.md)
5. **Pro** — [Testing](Pro/Testing/README.md), [Packaging](Pro/Packaging/README.md), [Performance](Pro/Performance/README.md), [Production Patterns](Pro/Production-Patterns/README.md)

---

## Quick reference

| If they ask… | Link |
| :--- | :---: |
| Types, namespaces, LEGB, basics | [→ Open](Beginner/Fundamentals/README.md) |
| REPL vs script, how Python runs .py | [→ Open](Beginner/Execution-Basics/README.md) |
| Comments, docstrings, PEP 8 | [→ Open](Beginner/Comments-And-Docstrings/README.md) |
| print(), input(), formatting | [→ Open](Beginner/Input-Output/README.md) |
| Arithmetic, comparison, logical, is, in | [→ Open](Beginner/Operators/README.md) |
| Immutables vs mutables, sequences | [→ Open](Beginner/Data-Types/README.md) |
| int, float, str, bool, type conversion | [→ Open](Beginner/Data-Types-Deep-Dive/README.md) |
| Lists, tuples, sets, dicts — operations and when to use | [→ Open](Beginner/Collections/README.md) |
| Control flow overview, else on loops | [→ Open](Beginner/Control-Flow/README.md) |
| if, elif, else, truthiness, comparisons, ternary | [→ Open](Beginner/Conditionals/README.md) |
| for, while, break, continue, sequences, enumerate, zip | [→ Open](Beginner/Loops/README.md) |
| List/dict/set comprehensions, generator expressions | [→ Open](Beginner/Comprehensions/README.md) |
| File I/O, read/write, modes, text vs binary, encoding | [→ Open](Beginner/Files/README.md) |
| Defining functions, parameters vs arguments, defaults, return | [→ Open](Beginner/Functions/README.md) |
| sys.argv, argparse, CLI, exit codes | [→ Open](Beginner/Command-Line-Args/README.md) |
| String indexing, slicing, methods, immutability | [→ Open](Beginner/Strings/README.md) |
| Modules, imports, __name__ == "__main__", code organization | [→ Open](Beginner/Modules-And-Imports/README.md) |
| Exceptions, try/except/else/finally, raise | [→ Open](Beginner/Error-Handling/README.md) |
| venv, pip, requirements.txt, isolating dependencies | [→ Open](Beginner/Virtual-Environments/README.md) |
| `is` vs `==`, identity, mutability, copies | [→ Open](Intermediate/Object-Model/README.md) |
| Decorators, *args, **kwargs | [→ Open](Intermediate/Functions-And-Decorators/README.md) |
| EAFP, custom exceptions | [→ Open](Intermediate/Error-Handling/README.md) |
| `with`, context managers | [→ Open](Advance/Context-Managers/README.md) |
| Iterators, generators, yield | [→ Open](Advance/Iterators-And-Generators/README.md) |
| Classes, inheritance, dunder | [→ Open](Advance/OOP/README.md) |
| GIL, threading, async intro | [→ Open](Advance/Concurrency/README.md) |
| Metaclasses, class decorators | [→ Open](Expert/Metaprogramming/README.md) |
| Descriptors, property | [→ Open](Expert/Descriptors/README.md) |
| asyncio, event loop, tasks | [→ Open](Expert/Async-Deep-Dive/README.md) |
| pytest, mocking, fixtures | [→ Open](Pro/Testing/README.md) |
| pyproject.toml, packaging | [→ Open](Pro/Packaging/README.md) |
| Profiling, C extensions | [→ Open](Pro/Performance/README.md) |
| Logging, config, production | [→ Open](Pro/Production-Patterns/README.md) |

---

## Folder structure

```
Python/
├── README.md                    ← you are here
├── Beginner/
│   ├── README.md
│   ├── Fundamentals/
│   │   ├── README.md
│   │   └── fundamentals.md
│   ├── Execution-Basics/
│   │   ├── README.md
│   │   └── execution-basics.md
│   ├── Comments-And-Docstrings/
│   │   ├── README.md
│   │   └── comments-and-docstrings.md
│   ├── Input-Output/
│   │   ├── README.md
│   │   └── input-output.md
│   ├── Operators/
│   │   ├── README.md
│   │   └── operators.md
│   ├── Data-Types/
│   │   ├── README.md
│   │   └── data-types.md
│   ├── Data-Types-Deep-Dive/
│   │   ├── README.md
│   │   └── data-types-deep-dive.md
│   ├── Collections/
│   │   ├── README.md
│   │   └── collections.md
│   ├── Control-Flow/
│   │   ├── README.md
│   │   └── control-flow.md
│   ├── Conditionals/
│   │   ├── README.md
│   │   └── conditionals.md
│   ├── Loops/
│   │   ├── README.md
│   │   └── loops.md
│   ├── Comprehensions/
│   │   ├── README.md
│   │   └── comprehensions.md
│   ├── Files/
│   │   ├── README.md
│   │   └── files.md
│   ├── Functions/
│   │   ├── README.md
│   │   └── functions.md
│   ├── Command-Line-Args/
│   │   ├── README.md
│   │   └── command-line-arguments.md
│   ├── Strings/
│   │   ├── README.md
│   │   └── strings.md
│   ├── Modules-And-Imports/
│   │   ├── README.md
│   │   └── modules-and-imports.md
│   ├── Error-Handling/
│   │   ├── README.md
│   │   └── error-handling-fundamentals.md
│   └── Virtual-Environments/
│       ├── README.md
│       └── virtual-environments.md
├── Intermediate/
│   ├── README.md
│   ├── Object-Model/
│   │   ├── README.md
│   │   └── identity-mutability-memory.md
│   ├── Functions-And-Decorators/
│   │   ├── README.md
│   │   └── functions-and-decorators.md
│   └── Error-Handling/
│       ├── README.md
│       └── error-handling.md
├── Advance/
│   ├── README.md
│   ├── Context-Managers/
│   ├── Iterators-And-Generators/
│   ├── OOP/
│   └── Concurrency/
├── Expert/
│   ├── README.md
│   ├── Metaprogramming/
│   ├── Descriptors/
│   └── Async-Deep-Dive/
└── Pro/
    ├── README.md
    ├── Testing/
    ├── Packaging/
    ├── Performance/
    └── Production-Patterns/
```
