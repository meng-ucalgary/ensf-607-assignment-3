# ENSF-607 Assignment 3

An assignment on updating the Course Registration System done in [Assignment 1](https://github.com/meng-ucalgary/ensf-607-assignment-1) to include a GUI with MVC architecture.
ENSF 607 - Fall 2021

## Folder Structure

- [src](src): source code
- [lib](lib): setup data
- [screenshots](screenshots): GUI screenshots
- [uml](uml): UML diagrams and their source code

## How to build and run

1. JDK version 1.7 or above is required to build and run this program.

2. Clone the repository on your machine, or download the zip file

3. Run the [run.sh](run.sh) or [run.cmd](run.cmd) file to run the program

4. Then follow the onscreen instructions

## UML Diagrams

1. UML diagram - high level

   ![Package CRS](uml/package_crs.png)

2. UML diagram - detailed

   ![CLass CRS](uml/class_crs.png)

## Screenshots

Student entering his/her details

![0.1-Student-Enter.png](screenshots/0.1-Student-Enter.png)

Program menu options

![0.2-Menu-Options.png](screenshots/0.2-Menu-Options.png)

Menu option 1: no search results

![1.1-No-Search-Results.png](screenshots/1.1-No-Search-Results.png)

Menu option 1: search produced some results

![1.2-Search-Results.png](screenshots/1.2-Search-Results.png)

Menu option 2: couldn't register as all registrations are full in this offering

![2.1-No-Space-For-Registration.png](screenshots/2.1-No-Space-For-Registration.png)

Menu option 2: couldn't register as pre-requisites are not met

![2.2-Pre-Requisites-Not-Met.png](screenshots/2.2-Pre-Requisites-Not-Met.png)

Menu option 2: successfully registered

![2.3-Successful-Registration.png](screenshots/2.3-Successful-Registration.png)

Menu option 2: successfully registered but a warning is issued

![2.4-Successful-Registration-With-Warning.png](screenshots/2.4-Successful-Registration-With-Warning.png)

Menu option 2: cannot register for more than 6 courses

![2.5-Maxed-Out-Registration.png](screenshots/2.5-Maxed-Out-Registration.png)

Menu option 3: cannot de-register as registered courses has depedency

![3.1-Unsuccessful-De-Registration.png](screenshots/3.1-Unsuccessful-De-Registration.png)

Menu option 3: successfully de-registered

![3.2-Successful-De-Registration.png](screenshots/3.2-Successful-De-Registration.png)

Menu option 4: view the entire course catalog

![4-View-Catalog.png](screenshots/4-View-Catalog.png)

Menu option 5: show all the registered courses for the current student

![5-All-Registered-Courses.png](screenshots/5-All-Registered-Courses.png)

Menu option 6: exit the program

![6-Exit.png](screenshots/6-Exit.png)
