# C Training
Generic C training for Softnautics.

# C Training document
Go through [training](./docs/training.md) document and complete tasks and assignments as per training document.

# Directory structure
Follow below directory structure for all C excercises.
```
excercises/
├── ch-1
│   ├── ex-1-11
│   ├── ex-1-6
│   │   ├── bin
│   │   │   └── ex-1-6
│   │   ├── build
│   │   │   └── Makefile
│   │   ├── docs
│   │   ├── include
│   │   └── src
│   │       └── ex-1-6.c
│   └── Makefile
├── ch-2
└── Makefile
```
# Important notes:
1. Include directory should only have external header files (common to cross directories). Header files related to src directory must be in src directory only.
1. Individual makefiles to build only specific exercise, all assignments of specific chapter, all assignments of all chapters.
1. Parent makefile should call child makefiles  to perform required operation.
1. Object files should be generated  in src directory only.
1. Output binary should be put in bin directory of respective exercise.
1. Any docs (if required like README) should be put in docs directory.
