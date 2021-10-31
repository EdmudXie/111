# COMP5911M Coursework 1, Task 1

## Scenario

The code in this directory simulates an industrial process.  The `Machine`
class represents a machine on an assembly line.  Machines perform an
operation on an item of some kind.  The `Robot` class represents a robot.
A robot's job is to move items from one machine to another.  A third class,
`Report`, is used to generate a report on the status of the assembly line,
including details of the machines and the robot that is moving items
between them.  Unit tests are included for the `Robot` and `Report` classes.

## Refactoring

Run the unit tests on Linux or a Mac with

    ./gradlew test

On Windows, just omit the `./` from the start of the command.

**NOTE: This may be very slow the first time that it runs, as it may
need to download Gradle and unit testing libraries.**

All the tests should pass.

Refactor to remove the obvious code smell.  Do this in a stepwise manner,
as a series of refactoring operations.  Make sure that all the tests
still pass after each refactoring operation.  Commit your changes after
each step so that your Git repository shows a development process.

Clean up when you are done with

    ./gradlew clean
