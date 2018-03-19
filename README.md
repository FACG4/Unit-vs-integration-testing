# Unit-vs-integration-testing
By: Salam-Eman-Ahmed-Abdalsamad
</br>
</br>
</br>


### What is unit testing?
* Unit testing is a software development process in which the smallest testable parts of an application, called units, are individually and independently scrutinized for proper operation.

* Unit testing is a component of test-driven development (TDD), a pragmatic methodology that takes a meticulous approach to building a product by means of continual testing and revision. Test-driven development requires that developers first write failing unit tests. Then they write code and refactor the application until the test passes.

* Unit testing involves only those characteristics that are vital to the performance of the unit under test. This encourages developers to modify the source code without immediate concerns about how such changes might affect the functioning of other units or the program as a whole.


*  The great benefit to unit testing is that the earlier a problem is identified, the fewer compound errors occur. A compound error is one that doesn't seem to break anything at first, but eventually conflicts with something down the line and results in a problem.

Simple example:

This a function that returns the sum of two integers:

```
int CombineNumbers(int a, int b)  {
    return a+b;
}
```


This is the test for the previous function: </br>
```
void TestCombineNumbers() {
    Assert.IsEqual(CombineNumbers(5, 10), 15);
    Assert.IsEqual(CombineNumbers(1000, -100), 900);
}
```


</br>
</br>

### When should you perform unit tests?
They should be done as often as possible. When you are performing tests as part of the development process, your code is automatically going to be designed better than if you just wrote the functions and then moved on. Also, concepts such as Dependency Injection are going to evolve naturally into your code.


### What are the unit testing benefits?
* Unit testing increases confidence in changing/ maintaining code.
* Codes are more reusable.
* Development is faster.
* The cost of fixing a defect detected during unit testing is lesser in comparison to that of defects detected at higher levels.
* Debugging is easy.
* Codes are more reliable.

### Unit Testing Tips
* Find a tool/framework for your language.
* Do not create test cases for everything. Instead, focus on the tests that impact the behavior of the system.
* Isolate the development environment from the test environment.
* Use test data that is close to that of production.
* Before fixing a defect, write a test that exposes the defect.
* Write test cases that are independent of each other.
* Aim at covering all paths through the unit. Pay particular attention to loop conditions.
* Make sure you are using a version control system to keep track of your test scripts.
* In addition to writing cases to verify the behavior, write cases to ensure the performance of the code.
* Perform unit tests continuously and frequently.
