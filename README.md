# Core Java: Executable Language Examples

A collection of small Java programs that isolate individual language concepts. Each example can be inspected and run independently, making it easier to connect a language feature with its console output.

## Learning problem

Larger applications combine many concepts at once. These examples reduce that complexity by concentrating on variables, methods, arrays, flow control, or objects in a short program.

## Source map

| Location | Topics |
| --- | --- |
| [CoreJavaDemo/src/](CoreJavaDemo/src/) | Primitive types, casting, method calls, and bitwise operations. |
| [arrays/](CoreJavaDemo/src/arrays/) | One-dimensional arrays, two-dimensional arrays, and arrays of objects. |
| [classesandobjects/](CoreJavaDemo/src/classesandobjects/) | Object state and methods using room and vehicle examples. |
| [flowcontrolandloops/](CoreJavaDemo/src/flowcontrolandloops/) | Conditional branches, switch statements, and loops. |
| [DemoProject/src/Demo.java](DemoProject/src/Demo.java) | Minimal console entry point. |

## Run an example

Install a JDK with `javac` and `java` on the path. From the repository root:

```bash
mkdir -p out
javac -d out CoreJavaDemo/src/MethodDemo.java
java -cp out MethodDemo
```

The method example calculates the square of a number. Other examples can be compiled independently or imported into Eclipse using the committed project files. Some examples use multi-label switch syntax, so select a JDK that supports that syntax when compiling the full collection.

## Portfolio context and attribution

Java fundamentals, program tracing, and basic object modeling. This is a training fork of [DeveloperOneDemo/core-java-demo](https://github.com/DeveloperOneDemo/core-java-demo), with the original example code and Eclipse workspace material retained. It is a collection of exercises, not a single deployable service.
