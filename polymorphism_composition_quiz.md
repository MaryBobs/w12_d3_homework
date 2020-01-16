# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

ANSWER: To be able to be more than one thing.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

ANSWER: Applying polymorphism to OO design means we can make DRYer code and avoid overloading as it allows us to
group objects with a class or interface in common together.

3. What can we use to implement polymorphism in Java?

ANSWER: We can use abstract classes and interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?

ANSWER: An object can take as many forms as we want it to. It can only inherit from one super class, but we can add as many interfaces as we need to.

5. Give an example of when you could use polymorphism.

ANSWER: For example if you had a program to organise a cinema snack bar stock you could have a Beverage super class then a HotDrink class which inherits from Beverage. A Coffee class would inherit from the HotDrink class so you could say a coffee IS A
HotDrink, but also that it IS A Beverage. If you also created an IBrew interface with a brew time then you could also implement IBrew in your Coffee class so it could also be an IBrew object.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

ANSWER: Using different separate objects to make up a class.

7. When would you use composition? Provide a simple example in Java.

8. What is/are the advantage(s) of using composition?

ANSWER: It allows a class to use behaviours from other classes and for that behaviour to change.

9. When an object is destroyed, what happens to all the objects it is composed of?

ANSWER: The objects it is composed of are also destroyed.
