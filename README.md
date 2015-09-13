learning-fortran
================

Repository created to learn basics of Fortran - yet another oldschool language

Preparation on Linux
--------------------

Install GNU Fortran compiler from the GCC, which is a fork of G95:

```
$ sudo apt-get install gfortran
```

Compiling and running programs
------------------------------

Create file with name `hello.f90` and the following content:

```fortran
program hello
  print *, "Hello World!"
end program hello
```

Compile the program with the following command:

```
$ gfortran -o hello hello.f90
```

Run the program:

```
$ ./hello
```

References
----------

- [Hello World in Fortran](https://en.wikibooks.org/wiki/Fortran/Hello_world)
- [Fotran on Wikipedia](https://en.wikipedia.org/wiki/Fortran)
