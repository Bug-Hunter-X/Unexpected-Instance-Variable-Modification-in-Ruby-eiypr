# Ruby Instance Variable Modification Bug

This repository demonstrates a potential issue related to modifying instance variables directly in Ruby using `instance_variable_set`. While functional, this practice can lead to unexpected behavior and make code harder to maintain and debug.  The bug and solution highlight safer alternatives.

## Bug Description:

Directly modifying instance variables using `instance_variable_set` can bypass encapsulation and potentially lead to inconsistent state within an object. It can make tracking changes difficult and introduce subtle bugs that are hard to pinpoint.