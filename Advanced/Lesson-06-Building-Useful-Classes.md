# Lesson 06 - Building Useful Classes

## Our goal

I will guide you in turning a real-world record into a useful class with clear constructors, accessors, calculations, and validation.

## What I will teach

An object should keep related data together and provide operations that make sense for that data. A product might store an ID, description, quantity, wholesale price, and markup. Its retail-price function should calculate the price from the stored values rather than store a second value that can get out of sync.

Constructors should initialize every field. Accessors that do not modify state should be `const`. We will choose types that fit our values and check input before creating an object.

## Guided steps

1. Choose a product or sports-player record and list its essential fields.
2. Decide which fields should be private and what operations the object should provide.
3. Write a constructor that initializes every field to a sensible value.
4. Add `const` accessors and a function that calculates a derived value, such as retail price.
5. Validate values such as quantity and price before the object is created.
6. Write a client program that creates two objects, then displays and tests their values.

## Practice

- Model a rugby player with a name, age, and tries scored.
- Add a rule that prevents a negative wholesale price or quantity.
- Store markup as a rate (`0.20`) and write a test that verifies a 20% markup on a $10 item produces a $12 retail price.

## Check for understanding

- Why is a calculated retail price often better as a function than duplicated stored data?
- What should happen if a constructor receives an invalid value?
- Why should a read-only accessor be marked `const`?

## Source connection

The `Prog1/Turn In/Inventory` work models product information and calculates a retail price. `Sept14HW/Rugby` and the `Goldfish` client example explore player/animal-style records. We will use these as modeling exercises and improve on fixed-size character buffers and incomplete validation.
