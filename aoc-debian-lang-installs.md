## OSX

### javascript

```
// bash
sudo apt-get install nodejs npm

// hello.js
const greeting = "Hello, World!";
console.log(greeting);

// bash
node hello.js
```

### typescript

```
// bash
sudo apt-get install nodejs npm
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
Download and install PowerShell from the official GitHub repository: PowerShell GitHub Releases

// hello.ps1
$greeting = "Hello, World!"
Write-Host $greeting

// bash
pwsh hello.ps1
```

### go

```
Download and install Go from the official website: Go Downloads


// hello.go
package main
import "fmt"
func main() {
    fmt.Println("Hello, World!")
}

// bash
go run hello.go
```

### closure

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
sudo apt-get install open-cobol

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
sudo apt-get install swi-prolog

// hello.pl
:- initialization(main).
main :- write('Hello, World!'), nl, halt.

// bash
swipl -q -s hello.pl
```

### java

```
// bash
sudo apt-get install default-jdk

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

Install Kotlin using SDKMAN: [SDKMAN](https://sdkman.io/)
```

// hello.kt
fun main() {
    println("Hello, World!")
}

// bash
kotlinc HelloWorld.kt -include-runtime -d HelloWorld.jar
java -jar HelloWorld.jar
```

### swift

Follow instructions on the [Swift.org](swift.org) website.

```
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
Install Rakudo using the official guide: [Rakudo Perl 6](https://rakudo.org/how-to-get-rakudo/)

```
// hello.raku
say "Hello, World!";

// bash
raku HelloWorld.raku
```

### ruby

Install Ruby using Rbenv or RVM:
Rbenv: Follow the instructions on [Rbenv GitHub](https://github.com/rbenv/rbenv#installation)
RVM: Follow the instructions on [RVM.io](https://rvm.io/rvm/install)

```
// hello.rb
puts "Hello, World!"

// bash
ruby HelloWorld.rb
```

### haskell

```
// bash
sudo apt-get install haskell-platform

// hello.hs
main :: IO ()
main = putStrLn "Hello, World!"

// bash
runhaskell HelloWorld.hs
```

### lua

```
// bash
sudo apt-get install lua5.3

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

Install Dart SDK: Follow instructions on the [Dart SDK](https://dart.dev/get-dart) website.

```
// hello.dart
void main() {
  print('Hello, World!');
}

// bash
dart hello.dart
```

### nim

Install Nim using Nimble: Follow the instructions on [Nim Website](https://nim-lang.org/install.html)

```
// hello.nim
echo "Hello, World!"

// bash
nim js -d:nodejs hello.nim
./hello
```

### C

```
// bash 
sudo apt-get install build-essential

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
// bash
sudo apt-get install build-essential

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

You can follow instructions on the [Installing Elixir](https://elixir-lang.org/install.html) page.

```
// hello.exs
IO.puts "Hello, World!"

// bash
elixir hello.exs
```

### D

Install D programming language by following instructions on [Dlang](https://dlang.org/download.html)

```
// hello.d
import std.stdio;
void main() {
    writeln("Hello, World!");
}

// bash
dub run hello.d
```

### zig

Install Zig by following instructions on [Ziglang](https://ziglang.org/download/)

```
// hello.zig
const std = @import("std");
pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}


// bash
zig run hello.zig
```
