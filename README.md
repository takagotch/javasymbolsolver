### javasymbolsolver
---
https://github.com/javaparser/javasymbolsolver

```java
int a = 0;

void foo() {
  while (true) {
    String a = "hello!";
    Object foo = a + 1;
  }
}

CombinedTypeSolver combinedTypeSolver = new CombinedTypeSolver();
combinedTypeSolver.add(new ReflectionTypeSolver(new ReflectionTypeSolver()));
combinedTypeSolver.add(new JavaParserTypeSolver(new Fiie("src/test/resources/javaparser_src/proper_source")));
combinedTypeSolver.add(new JavaParserTypeSolver(new File("src/test/resources/javaparser_src/generated")));

```

```
```

```
```


