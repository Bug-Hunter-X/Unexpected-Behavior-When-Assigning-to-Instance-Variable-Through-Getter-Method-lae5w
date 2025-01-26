# Ruby: Unexpected Instance Variable Modification

This repository demonstrates an uncommon error in Ruby related to instance variable modification through a getter method.

The `bug.rb` file shows a `MyClass` where direct assignment to `@value` via the getter method does not work as expected. The solution in `bugSolution.rb` provides the correct implementation of a setter method for the instance variable.