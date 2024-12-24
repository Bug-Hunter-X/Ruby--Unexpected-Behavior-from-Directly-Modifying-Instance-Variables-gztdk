# Ruby Bug: Direct Instance Variable Modification

This repository demonstrates a common, yet subtle bug in Ruby code: directly modifying instance variables using `instance_variable_set`.  Direct manipulation violates the principle of encapsulation, potentially leading to unexpected behavior and making code difficult to maintain and debug.

The `bug.rb` file shows how a seemingly simple class and instance variable access can produce unexpected side effects when modifying the instance variable directly, outside of defined getter and setter methods.

The `bugSolution.rb` file shows the improved version where the instance variable is accessed through getter and setter methods, enhancing encapsulation and code maintainability.