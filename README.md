Duck Simulator
This Java program demonstrates the use of the Strategy pattern to model different types of ducks with varying behaviors for flying, quacking, and swimming.

Overview
The program consists of several Java classes that implement e Duck simulator. The key components of the p
Main: The main class that contains the main() method to execute the Duck simulator. It creates instances of different duck types, such as MallardDuck, RedHeadDuck, RubberDuck, and DecoyDuck, and invokes their methods to display their behavior.

Duck: An abstract class that serves as the base class for different types of duckstains references to objects of the FlyBehavior, QuackBehavior, and SwimBehavior interfaces, which can be set at runtime to change the behavior of duommon methods such as performQuack(), performFly(), and performSwim() to delegate the behavior to the corresponding behavior objects.

FlyBehavior, QuackBehavior, SwimBehavior: Interfaces that define the behaviors for flying, quacking, and swimming respectively.

Concrete classes such as MallardDuck, RedHeadDuck, and DecoyDuck: These classes extend the Duck class and provide their own implementations for the display() method, which is specific to each duck type. They also set the behavior objects for flying, quacking, and swimming in their constructors.

Concrete classes such as FlyWithWings, FlyNoWay, Quack, MuteQuack, Squeak, Swim, Float, and Drown: These classes implement the behavior interfaces and define the actual behavior for flying, quacking, and swimming.

Usage
To run the Duck simulator, you can follow these steps:

Clone or download the repository to your local machine.

Open the Java file Main.java in a Java development environment or an integrated development environment (IDE) of your choice.

Compile and run the Main class to execute the Duck simulator.

Observe the output, which displays the behavior of different types of ducks, including their display, flying, quacking, and swimming behavior.
