1. Polymorphism is a situation where a variable that is declared sometime a compile time can take different compatabile type of run time. Example of polymorphism

2. U is polymorphic and at compile time it is an object but at run time it could be a pointer, scanner or string.So u is dynamically bound at run time.

3. The output is A!!!

4. The output is "~~ B ~~" for the first print statement and the second print statement also as the same output.

5. The output is "A" for both print statements.

6. It will not compile because it was restricted but it was later changed into a private which causes issues.

7. The output is A: 1

8. The output is foo1: B B -- ask kinga about this 

9. - ``` fluffy```  : "Name: fluffy Species: Canis Familaris(pomeranian)"
   - ``` george ``` : "Name: george Species: Canis Familaris"
   - ``` brutus ``` : "Name: brutus Species: Felis Catus(shorthair)"
10.
``` java
    A.1: 42
    A.2: 50
    A.3: Error (no baz() method)
    B.1: 41
    B.2: 50
    B.3: "y"
    D.1: 42
    D.2: 7
    D.3: Error (no baz() method)
```
11.

    - 11. You can never call a construct classs directly you can only  call it using a super. Software engineering: animal intenstine  zoo example

12. For an abstract ``` Car ``` class:
**Abstract methods:**
 ``` startEngine() ``` – Since different types of cars (electric, gas-powered, etc.) may start in different ways, this method would be abstract, forcing subclasses to define how their engines start.
``` fuelType() ``` – Abstract because different cars use different fuels (gasoline, electricity, etc.).
**Concrete methods:**
calculateMileage() – This method might be common to all cars and can be implemented at the abstract class level with logic that applies universally.
displayCarInfo() – This method can be implemented in the abstract class to provide a standard way of displaying essential information about the car, such as its model, year, and color. This method can include common details that are relevant for all car types, ensuring consistency in how car information is presented across different subclasses.
