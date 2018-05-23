Polymorphism

1. What does the word 'polymorphism' mean?

Polymorphism means many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Using a single/uniformed interface to group different classes with the same behaviours.

3. What can we use to implement polymorphism in Java?

When you identify 2 or more classes share the same method you can then set up an interface and have all the classes that share the same method implement the interface. It will then force them to share the same method.

4. How many 'forms' can an object take when using polymorphism?

Many forms.

5. Give an example of when you could use polymorphism.

You could use polymorphism in an array of different classes. In this array we can call a certain method to function it's own way depending on the class it's being called on.

Composition

1. What do we mean by 'composition' in reference to object-oriented programming?

Composition is when various objects belong one class.

2. When would you use composition? Provide a simple example in Java.

class Engine {
    private int capacity;
    public void rev() {

    }
}

class Gearbox {
    private String type;
    private int numberOfGears;
}

class Car {
    private String make;
    private String model;
    private Engine engine;
    private GearBox engine;
}

3. What is/are the advantage(s) of using composition?

With composition you can edit your private internal objects without disturbing the

4. What happens to the behaviours when the object composed of them is destroyed?

All of the behaviours stop functioning
