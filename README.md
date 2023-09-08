# objective-c-data-structures
A series of data structures I'm creating to start learning `Objective-C` using `Xcode` as an IDE in a `MacOS` environment!

Each data structure will have two versions:
- **"Idiomatic" version:** Utilizes Objective-C's built-in features for efficient data management, helping me grasp the language's standard practices.
- **"Reinventing the Wheel" version:** Constructs the data structures from scratch, offering a deeper dive into the language's fundamentals.

## Development Environment
Due to the constraints of developing on a late 2012 iMac, some of my code may incorporate older practices or APIs. For clarity and transparency, I've outlined my development environment details below.

### Clang Compiler Version
```
Apple clang version 12.0.0 (clang-1200.0.32.29)
Target: x86_64-apple-darwin19.6.0
Thread model: posix
```

### Xcode version
```
Version 12.4 (12D4e)
```

### Operating System
```
OSX Catalina 10.15.7
```


## Data Structures Included

### Stacks

#### `IdiomaticStack`
The implementation of this stack makes use of the `NSMutableArray` class and imitates the functionality of a stack.

#### `ManualStack`
The implementation of this stack is rebuilding the wheel. I implemented this version in order to learn more about how Objective-C works at a lower level.
