# Chess Problems For Beginners

The files in this repository contain chess mating problems and
positional problems for beginning players.  The problems are not
geared toward intermediate or advanced players.

The problems are raw positions taken from actual games where the
winning side had an overwhelming advantage.  These are not problem
compositions.  You are welcome to edit the problems to make the
sides more balanced.

The following file names are explained.

blackm1.fen - Black mates in 1

blackm2.fen - Black mates in 2

whitem1.fen - White mates in 1

whitem2.fen - White mates in 2

whitem3.fen - White mates in 3

whitem4.fen - White mates in 4

whitem5.fen - White mates in 5

whitem6.fen - White mates in 6

whitem7.fen - White mates in 7

blackmv.fen - Black to move and gain an advantage

whitemv.fen - White to move and gain an advantage

## Solving the problems.

In Linux, you may solve these problems using xboard.  Under the
file menu, click on load position.  Select one of the files with
a .fen suffix.

The following short-cut keys may be used in xboard.

* Shift-PgDn - go to next problem

* Shift-PgUp - go to previous problem

* Alt-left   - go to previous move

* Alt-right  - go to next move

If there is one good problem in this repository, then the effort to
collect them will have be worthwhile.  Have fun solving them.

## Scramble a problem file

This repository contains three programs to scramble a problem
file.  There are some chess problems in this repository
which are very similar to each other, so it is advisable to
scramble the chess problems before you solve them in random
sequence.  You can also concatenate several problem files together
before you scramble and solve them.

There are three versions of the scramble program.

scrmbl - Linux binary to scramble a problem file.

scrmbl.exe - Windows 10 executable to scramble a problem file.
    This version of scrmbl.exe also works with wine.

scrmbl.py - Python 3 script to scramble a problem file.

Linux example:

cat blackm1.fen | scrmbl >random.fen

Windows 10 example:

scrmbl.exe <blackm1.fen >random.fen

wine example:

wine scrmbl.exe <blackm1.fen >random.fen

Python 3 example:

python scrmbl.py <blackm1.fen >random.fen
