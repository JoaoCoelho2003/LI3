# LI3 - Efficient Data Parsing and Query Execution in C

## Overview

LI3 is a project focused on parsing large datasets and executing queries over the data. Developed during the second year of the Software Engineering degree at the University of Minho, during the first semester as part of the Laboratórios de Informática III subject, this project aims to efficiently handle and process substantial volumes of data.

For detailed information about the project's requirements and specifications, please refer to the project report provided by the professors.

[Access Project Report](docs/project.pdf)

## Dependencies

- **gcc**: The project requires the GNU Compiler Collection (GCC) for compiling the C source code.

- **glib-2.0**: The project relies on GLib, a library providing data structure handling for C, as well as portability wrappers and interfaces for runtime functionality such as event loops, threads, and dynamic loading. Make sure to have GLib installed to build and run the project successfully.

Both can be installed using various package managers depending on your Linux distribution. Here are some examples:

### Debian/Ubuntu-based distributions (using apt):

#### GCC

```
$ sudo apt update
$ sudo apt install gcc
```

#### GLIB2

```
$ sudo apt update
$ sudo apt install libglib2.0-dev
```

### Fedora-based distributions (using dnf):

#### GCC


```
$ sudo dnf install gcc
```

#### GLIB2

```
$ sudo dnf install glib2-devel
```

### Arch-based distributions (using pacman):

#### GCC

```
$ sudo pacman -S gcc
```

#### GLIB2

```
$ sudo pacman -S glib2
```

### Manjaro Linux (using pamac):

#### GCC

```
$ sudo pamac install gcc
```

#### GLIB2

```
$ sudo pamac install glib2
```


Feel free to choose the appropriate command based on your Linux distribution and package manager.

## Cloning the Repository

To clone the repository, run the following command in your terminal:

```
$ git clone https://github.com/JoaoCoelho2003/LI3.git
```

Once cloned, navigate to the repository directory using the cd command:

```
$ cd LI3
```

## Compiling and Running

To compile the project, you can use the provided Makefile. Simply navigate to the root directory of the project where the Makefile is located and run the following command:

```
$ make
```

This command will compile the project and generate the executable files. The Makefile includes rules for both the main program and the test program.

To run the compiled main program, use the following command:

```
$ ./main-program
```

To run the compiled test program, use the following command:

```
$ ./test-program
```

Once you run the compiled program, it will prompt you to enter the path to the datasets. Please provide the path to the folder `test_files`, which is located in the repository.

### Cleaning Up

To clean up the compiled files and reset the project to its initial state, you can use the following command:

```
$ make clean
```

This command will remove all compiled object files and executable files.

Additionally, if you want to clean only the output files generated during testing, you can use the following command:

```
$ make out_clean
```

## Project Reports

- [Phase 1 Report](reports/relatorio-fase1.pdf)
- [Phase 2 Report](reports/relatorio-fase2.pdf)


## Conclusion

We hope you find working with the LI3 project both educational and rewarding! If you have any questions, suggestions, or feedback, please don't hesitate to reach out. Happy coding!

## Developed by

**A100596** João Coelho
**A100692** José Rodrigues
**A100750** Duarte Araújo




