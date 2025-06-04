# dsa-in-cpp-kotlin-dart
This repository helps developers practice and understand Data Structures & Algorithms (DSA) across three programming languages: C++, Kotlin, and Dart. It includes syntax comparisons, code templates, and solved problems for interview preparation and cross-language fluency. Ideal for Flutter developers, Android developers, and competitive programmers who want to sharpen their DSA skills in multiple ecosystems.

 Syntax Comparison Chart

| 🧩 Task / Concept         | 🇨++ C++                              | 🇰 Kotlin                                | 🐦 Dart                                  |
|--------------------------|--------------------------------------|------------------------------------------|------------------------------------------|
| **Print**                | `cout << "Hello";`                   | `println("Hello")`                     | `print("Hello");`                        |
| **Variable (int)**       | `int x = 10;`                        | `var x: Int = 10`                      | `int x = 10;`                            |
| **Variable (string)**    | `string s = "Hi";`                   | `var s: String = "Hi"`                 | `String s = "Hi";`                       |
| **List/Array**           | `int arr[5] = {1,2,3,4,5};`          | `val arr = arrayOf(1, 2, 3)`           | `List<int> arr = [1, 2, 3];`             |
| **List Length**          | `sizeof(arr)/sizeof(arr[0])`         | `arr.size`                             | `arr.length`                             |
| **For Loop**             | `for(int i=0; i<5; i++)`             | `for(i in 0 until 5)`                  | `for(int i=0; i<5; i++)`                 |
| **While Loop**           | `while(i < 5)`                       | `while(i < 5)`                         | `while(i < 5)`                           |
| **If-Else**              | `if(a > b) {...} else {...}`         | `if(a > b) {...} else {...}`           | `if(a > b) {...} else {...}`             |
| **Function**             | `int add(int a, int b)`              | `fun add(a: Int, b: Int): Int`         | `int add(int a, int b)`                  |
| **String Length**        | `s.length()`                         | `s.length`                             | `s.length`                               |
| **Map / Dictionary**     | `map<string, int> mp;`               | `mutableMapOf<String, Int>()`          | `Map<String, int> mp = {};`              |
| **Map Access**           | `mp["age"] = 20;`                    | `mp["age"] = 20`                       | `mp["age"] = 20;`                        |
| **Stack**                | `stack<int> s; s.push(1);`           | `ArrayDeque<Int>().addLast(1)`         | `List<int> s = []; s.add(1);`            |
| **Class**                | `class Person { string name; }`      | `class Person(val name: String)`       | `class Person { String name; }`          |
| **Object Creation**      | `Person p;`                          | `val p = Person("name")`               | `var p = Person("name");`                |

