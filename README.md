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
- [This is not your father's Fortran](http://hackaday.com/2015/10/26/this-is-not-your-fathers-fortran/)
- [Who said Fortran is dead?](http://hackaday.com/2015/11/01/who-said-fortran-is-dead/)
- [FortranTutorial.com](http://www.fortrantutorial.com/)
- [Fortran Tutorial at TutorialsPoint.com](http://www.tutorialspoint.com/fortran/)
- [Fortran Tutorial by Stanford](http://web.stanford.edu/class/me200c/tutorial_77/)
