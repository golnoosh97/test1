# Java documentation test v1.0.0


### Exercises

#### Number 1

* FolderName: basis

A function that takes a number of basis 10 and a number as basis and converts it to the basis form:

For example: 

```java
String result = MyMath.convert(4, 2); // Result is 100 (base 2 is binary)

result = MyMath.convert(3, 2); // Result is 11
```


#### Number 2

* FolderName: inherit

Make a class called Car having private fields of {Srting name, int speed, int doors, int price} and with abstract setter and getter methods (so the class is abstract itself).<br>
Create classes with these values based on Car:

```xml
Lambo {speed=390, name=lambo, doors=2, prince=90000}
Pride {speed=100, name=shit, doors=4, prince=50000}
P206 {speed=140, name=206, doors=4, prince=80000}
Bugatti {speed=430, name=bugatti, doors=2, prince=100000}
```

Make a function that takes a Car as arg.<br>
If the car was a Bugatti it will print `"Hmmmm :)"`
Else if it was P206 it will print `"Good"`
Else if it was lambo it will print `"Hmm :)"`
Else if it was a pride it will print `"D:"`

The function must be **static** with name of `check`, in a class called `CarAnalyzer`.

### How to submit?

Fork this repo.
In the project folder, create a folder called `java`, and create the java files there. Like:<br>

```
/docs
/java
	/number_1
	/number_2
```

And push in a branch (what ever except master), and then create a `pull request` to merge with master.

I will see and merge if it was OK :).

