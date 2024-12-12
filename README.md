# Unexpected Behavior from Directly Modifying Instance Variables in Ruby

This repository demonstrates a common yet subtle bug in Ruby: directly manipulating instance variables using `instance_variable_set` and `instance_variable_get`. While functional, this practice can lead to issues with maintainability, debugging, and unexpected behavior.  It's often better to use accessor methods to manage object state.

The `bug.rb` file shows an example of this problem, and the solution is presented in `bugSolution.rb`.