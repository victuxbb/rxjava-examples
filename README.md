# RxJava Examples

Just a list of examples found in official documentation: http://reactivex.io/documentation/operators.html

## How to execute

```java
./gradlew run -Dexample=example1
```

### Example 1
Create an Observable from scratch, by using create operator and then by calling the observer's ```onNext```,  ```onError``` and  ```onComplete```.

### Example 2
Like Example 1 but using lambdas instead.

### Example 3
Defer observable: do not create the Observable until the observer subscribes, and create a fresh Observable for each observer.