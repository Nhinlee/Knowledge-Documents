# IoC <> DIP <> DI

The terms Inversion of Control (IoC), Dependency Inversion Principle (DIP), Dependency Injection (DI), and IoC containers may be familiar. But are you clear about what each term means?

![](https://www.tutorialsteacher.com/Content/images/ioc/principles-and-patterns.png)

# IoC (Inversion of Control)

### What

- Invert different kinds of **controls** in object-oriented design to achieve **loose coupling**.
- Here, **controls** refer to any **additional responsibilities** a class has, other than its **main responsibility**.

- Exam: [tutorialsteacher.com/ioc/inversion-of-control](https://www.tutorialsteacher.com/ioc/inversion-of-control)

# DIP (Dependency Inversion Principle)

### What
- High-level modules should not depend on low-level modules. Both should depend on the abstraction.
- Abstractions should not depend on details. Details should depend on abstractions.

# DI (Dependency Injection)

### What
- A design pattern used to implement IoC.
- It allows the creation of **dependent objects** **outside of a class** and provides those objects to a class through different ways.
- Types:
  - Constructor Injection 
  - Property Injection (Setter)
  - Method Injection (Implement interface)
- Exam: [tutorialsteacher.com/ioc/dependency-injection](https://www.tutorialsteacher.com/ioc/dependency-injection)

# IoC Container / DI Container

### What
- Is a framework for implementing automatic dependency injection.
- It manages object creation and it's life-time, and also injects dependencies to the class.
- Exam: 
  - Android: Dagger / Hilt, Service locator, ...
    - docs: [Android Dependency Injection Officials](https://developer.android.com/training/dependency-injection)
  - Flutter: getIt, ...

REF: [tutorialsteacher](tutorialsteacher.com/ioc/inversion-of-control)
