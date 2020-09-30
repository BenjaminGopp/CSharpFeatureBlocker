# CSharpFeatureBlocker
C# ist THE best programming language out there!
But wait! Some features make you feel awe, some make you cringe?!

With the C# feature blocker you can disable C# features, when not needed or wanted.
- disable csharp features for the sake of disceplin
- prevent inexpirienced developers to harm 
- enforce coding policies

## How it works
The CSharpFeatureBlocker is a C# compiler (roslyn) analyzer. It diagnoses your code while your typeing. CSharpFeatureBlocker analyzes the c# syntax tree, provided by the c# compilier plattform. It integrates into Visual Studio, Visual Studio Code and Raider. 

You can select a language feature and set its diagnose severity to warning or error.

More information on code analyzers: https://docs.microsoft.com/en-us/visualstudio/code-quality/roslyn-analyzers-overview?view=vs-2019

## Other solutions
There are other solutions out there. But non of them is so powerfull like the C# feature blocker.
### .editorconfig
With the .editorconfig file you can enforce formatting styles and some coding styles. It is possible to disable single csharp features.
Visual Studio Code does not support the .editorconfig file!

### --langversion
With the compiler flag --langversion you can set the c# compiler to an earlier language version. But that an **all or nothing** thing. You can not disable a single feature on its own.

## Supported Versions
With the C# feature blocker you can disable most of the latest C# language features.

supported, ~~not supported~~

- C# 6
  - read-only auto-properties
  - auto-property initializer
  - expression-bodied function members
  - using static
  - null-conditional operators
  - string interpolation
  - exception filters
  - nameof
  - await in catch and finaly blocks
  - initialize associative collections using indexers
  
- C# 7.0
  - inline out variables
  - tuples
  - discards
  - ~~pattern matching~~
  - ref locals and returns
  - local functions
  - expression-bodied constructors, finalyzers, properties, indexers
  - throw expression
  - ~~generalized async return types~~
  - numeric literal syntax _

- C# 7.1
  - async main
  - default literal expression
  - ~~inferred tuple element names~~
  - ~~pattern matching on generic type paramters~~

- C# 7.2
  - in parameter
  - ref readonly
  - readonly/ref struct
  - private protected accessor
  - ~~conditional ref expressions~~
  
- C# 8
  - readonly members
  - default interface members
  - switch expression
  - ~~nullable reference types~~ can be disabled by the compiler
  - ~~pattern matching~~
  - single line using
  - static local functions
  - asynchronous streams
  - asynchronous disposable
  - ~~indices and ranges~~
  - null-coalescing assignment
  - ~~unmanaged constructed types~~
  - ~~stackalloc in nested expressions~~
    
- C# 1-5
  - **not yet supported**

## Versioning
-- table --
Blocker - C# - VS

