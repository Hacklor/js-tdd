# Episode 5; Performance

In [episode4][episode4] we have build a calculator object using the new EcmaScript class syntax. But
there is a reason we have chosen to go in the direction of an object, even though there are many
ways we build a calculator 'object' in Javascript. In this episode we are going to investigate the
different possibilities.

## Using our tests

We are going to use our previous tests as a guide, but will also add tests to see what the
performance is of different implementations. We test the performance by keeping track how many times
the `add` function is declared.






> Todo:
Question: What will happen each time the `makeAddFunction` is called? What impact will this have on
the memory footprint?


> This episode is still **Work in progress**

# Building a calculator, episode 3

After finishing [episode 2][episode2] you should have a small codebase
and test suite, with some functions and an calculator 'object'
experiment.

To provide some more insight into 'objects', this time we are going to
do a little experimentation.

Move the provided `calculator.spec.js` into your experiment codebase.
(that you have set up during [episode 1][episode1])

The file consists of 3 parts.

1. 5 different ways of creating an calculator object
2. Picking our 'makeCalculator' factory
3. Testing our calculator

Goal:

1. Try out each form of implementing the calculator
2. Make sure you understand each form of implementing it
3. Figure out why certain tests fail in certain cases

[episode1]: https://github.com/matthijsgroen/js-tdd/tree/master/episode1
[episode2]: https://github.com/matthijsgroen/js-tdd/tree/master/episode2
