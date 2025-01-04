# DataStructuresJava
Data Structures in Java

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

## Table Of Contents By Concept

- __Union Find(Weighted Quick Union Find)__
  - GameOfLife/src/conwaygame/GameOfLife.java
    - There are multiple classes within the conwaygame folder that have Classes of objects and initializing the Game Board
    - GameOfLife/src/conwaygame/Driver.java is the driver file which should be executed
    - txt files have been provided to test the program and additional input files may be executed after running the driver
  
- __Linked Lists__
  - ClimateEconJustice/src/climate/ClimateEconJustice.java
    - There are multiple classes within the climate folder that have Classes of objects
    - ClimateEconJustice/src/climate/Driver.java is the driver file which should be executed
    - csv files have been provided to test the program

- __Binary Search Tree__
  - ForensicAnalysis/src/forensic/ForensicAnalysis.java
    - There are multiple classes within the forensic folder that have Classes of objects
    - ForensicAnalysis/src/forensic/Driver.java is the driver file which should be executed
    - txt files have been provided to test the program

- __Hash Table__
  - RUHungry/src/restaurant/ForensicAnalysis.java
    - There are multiple classes within the restaurant folder that have Classes of objects
    - RUHungry/src/restaurant/Driver.java is the driver file which should be executed
    - txt files have been provided to test the program
  
- __Spiderverse__
  - Clusters.java
  - Collider.java
  - TrackSpot.java
  - CollectAnomalies.java
  - GoHomeMachine.java
    - Instructions to run using specific inputs listed under "Usage"

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (Version 11 or higher).
- You have installed [Apache Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/).
- You have access to a terminal or command line interface.

### Step-by-Step Installation

1. **Clone the Repository**

    First, you need to clone the repository to your local machine. Open your terminal and run the following command:
    ```bash
    git clone https://github.com/yourusername/yourproject.git
    ```

2. **Navigate to the Project Directory**

    Change into the project directory:
    ```bash
    cd yourproject
    ```

## Usage

3. **Compiling**

   Use this command to compile all the Java files in a folder
   ```bash
    javac FolderName/src/name/*.java
    ```
   
4. **Executing**

   Use to execute the Driver file within a folder with arguments(applicable to the projects that have a Driver.java file:
   ```bash
    java FolderName/src/name/Driver.java argument1 argument2 argumentn
    ```
   **NOTE: When executing, ensure that arguments are added as necessary*
  
5. **Output**
   You could view the output in your terminal for most programs

Compiling and Executing RUHungry and Spiderverse is different from the other programs

**NOTE: Adjust the Menu.java folder to compile and execute RUHungry. Contact me if there are any issues with this** 

3. **Compiling**

  Use this command to compile all the Java files in the spiderman folder
     ```bash
       javac -d bin src/spiderman/*.java
     ```

4. **Executing**

  Use to execute the Clusters.java:
     ```bash
     java -cp bin spiderman.Clusters dimension.in clusters.out
     ```
  Use to execute the Collider.java:
     ```bash
     java -cp bin spiderman.Collider dimension.in spiderverse.in collider.out
     ```
  Use to execute the TrackSpot.java:
     ```bash
     java -cp bin spiderman.TrackSpot dimension.in spiderverse.in spot.in trackspot.out
     ```
  Use to execute the CollectAnomalies.java:
     ```bash
     java -cp bin spiderman.TrackSpot dimension.in spiderverse.in spot.in trackspot.out
     ```
  Use to execute the CollectAnomalies.java:
     ```bash
     java -cp bin spiderman.TrackSpot dimension.in spiderverse.in hub.in anomalies.in report.out
     ```

5. **Output**
  You could view the output in your terminal for most programs
  Spiderverse: You could view your output in the respective filename.out files

## Contributing
Rutgers Computer Science Department
  Authors of certain assignments have their name as a comment at the beginning of the main source file

## License
GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

## Contact
vishalsaran2021@gmail.com
