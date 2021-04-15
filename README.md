# StopWatch
to automate time elapsed between tasks

The program uses time module.

Algorithm

1. Press Enter to start and stop watch and ctrl-C to exit program.
2. starttime is set with time.time() and lapnumber is set to 1 which tracks laps.
3. while True loop is run such that when Enter is pressed the lap stops which prints the difference of starttime and current system time(i.e time.time()).
4. lapnumber is incremented by 1 and starttime is set to current system time now.
5. Step 3 to Step 4 will continue until Ctrl-C is pressed which when pressed exit the program handling KeyboardInterrupt exception and printing 'Done'.
