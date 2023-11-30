## OSX

### javascript

```
// bash
brew install node

// hello.js
const greeting = "Hello, World!";
console.log(greeting);

// bash
node hello.js
```

### typescript

```
// bash
brew install node
npm install -g typescript

// hello.ts
const greeting: string = "Hello, World!";
console.log(greeting);

// bash
tsc hello.ts && node hello.js
```

### bash

```
// hello.sh
echo "Hello, World!"

// bash
bash hello.sh
```

### powershell

```
// bash
brew install --cask powershell

// hello.ps1
$greeting = "Hello, World!"
Write-Host $greeting

// bash
pwsh hello.ps1
```

### go

```
// bash
brew install go

// hello.go
package main
import "fmt"
func main() {
    fmt.Println("Hello, World!")
}

// bash
go run hello.go
```

### clojure

```
// bash
brew install clojure

// hello.clj
(println "Hello, World!")

// bash
clojure hello.clj
```

### python

```
// hello.py
print("Hello, World!")

// bash
python hello.py
```

### cobol

```
// bash
brew install gnu-cobol

// hello.cob
IDENTIFICATION DIVISION.
PROGRAM-ID. Hello.
PROCEDURE DIVISION.
    DISPLAY 'Hello, World!'.
    STOP RUN.

// bash
cobc -x -free hello.cob
./hello
```

### prolog

```
// bash
brew install swi-prolog

// hello.pl
:- initialization(main).
main :- write('Hello, World!'), nl, halt.

// bash
swipl -q -s hello.pl
```

### java

```
// bash
brew install openjdk

// hello.java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

// bash
javac HelloWorld.java
java HelloWorld
```

### kotlin

```
// bash
brew install kotlin

// hello.kt
fun main() {
    println("Hello, World!")
}

// bash
kotlinc HelloWorld.kt -include-runtime -d HelloWorld.jar
java -jar HelloWorld.jar
```

### swift

```
// bash
brew install swift

// hello.swift
print("Hello, World!")

// bash
swift HelloWorld.swift
```

### perl5

```
// hello.pl
print "Hello, World!\n";

// bash
perl HelloWorld.pl
```

### raku

```
// bash
brew install rakudo

// hello.raku
say "Hello, World!";

// bash
raku HelloWorld.raku
```

### ruby

```
// hello.rb
puts "Hello, World!"

// bash
ruby HelloWorld.rb
```

### haskell

```
// bash
brew install haskell

// hello.hs
main :: IO ()
main = putStrLn "Hello, World!"

// bash
runhaskell HelloWorld.hs
```

### lua

```
// hello.lua
print("Hello, World!")

// bash
lua HelloWorld.lua
```

### rust

```
// bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

// hello.rs
fn main() {
    println!("Hello, World!");
}

// bash
rustc main.rs
./main
```

### dart

```
// bash
brew tap dart-lang/dart
brew install dart

// hello.dart
void main() {
  print('Hello, World!');
}

// bash
dart hello.dart
```

### nim

```
// bash
brew install nim

// hello.nim
echo "Hello, World!"

// bash
nim js -d:nodejs hello.nim
./hello
```

### C

```
// hello.c
#include <stdio.h>
int main() {
    printf("Hello, World!\n");
    return 0;
}

// bash
gcc hello.c -o hello
./hello
```

### C++

```
// hello.cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}

// bash
g++ hello.cpp -o hello
./hello
```

### elixir

```
// bash
brew install elixir

// hello.exs
IO.puts "Hello, World!"

// bash
elixir hello.exs
```

### D

```
// bash
brew install dub

// hello.d
import std.stdio;
void main() {
    writeln("Hello, World!");
}

// bash
dub run hello.d
```

### zig

```
// bash
brew install zig

// hello.zig
const std = @import("std");
pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}


// bash
zig run hello.zig
```
