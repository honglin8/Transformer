# Transformer
Goal: Implement a simple transformer in Python and from scratch, ie. not use the Transformer(...) function of a high-level library.

Some examples of simple task that can be used to test the transformer are:

* Sequence Reversal: reversing a sequences of numbers, [1,3,2,4,5,3] -> [3,5,4,2,3,1].
* Basic Arithmetic: learning simple arithmetic operation is a surprisingly challenging task for a transformer. For example, given a sequence of numbers and arithmetic operations, the model should output the result of the operations. [1,3,2,"+",9,4,2]->[1,0,7,4]. [1,3,2,"+",9,4,2]->[1,0,7,4]
* Copying Task: A simple task where the model’s objective is to output the same sequence it receives as input. This might seem trivial but is a good starting point: [1,3,2,4,5,3]->[1,3,2,4,5,3]
* Sorting Numbers: This can be very challenging for a transformer, especially if the sequence is long. [1,3,2,4,5,3]->[1,2,3,3,4,5]
* Character-Level Text Generation: Generating text one character at a time, based on a given prompt or starting character.
